# Chapter 10: Timers, Par Times and Splits

*Measured time is the clearest thing the software adds. It is also where the published method is most specific, and the contrast is worth drawing: in that method the timer does not detect your shots at all, because it only beeps and the shooter judges the hits.*

## The par time is yours to set

In the published method most par times are set by the shooter rather than supplied, because a printed number cannot account for your gun, your gear or your starting position. The exception is the Standards drills, where the times come with the drill and are the whole point of it.<sup>[1]</sup>

Two rules make a par useful rather than decorative.

A properly set par is not your maximum speed, and it is not one you always make. If you never miss it, it is too slow.<sup>[1]</sup> There is no target failure rate to aim at, so do not invent one.

And the timer comes in after the basics rather than before them, which is a sequence chapter 14 follows through in the order the method sets out.<sup>[2]</sup>

## What the software adds

Four things, and each of them is a real addition rather than a dressed-up version of the beep.

**A measured shot time**, where the method's own timer only brackets the string. **Splits**, the interval between consecutive shots, which is where a flinch or a lost grip shows up. **Draw time**, from the beep to the first shot. And **reaction time**, from a target appearing to the hit.

Of those, splits are the one worth the money. A string's total tells you it was slow, and the splits tell you where it went wrong.

Before you compare two products on this, check which tier the timing features sit in. Dry Fire Online keeps split times on its highest tier, and chapter 11 sets out the rest.<sup>[3]</sup>

Every par feature in these products is set by you. None of them tightens the par as you succeed, so the progression is yours to run, which is what the method asks for anyway.

## How accurate is any of this

One vendor publishes a figure, and publishes it honestly.

Dry Fire Online's manual states that the estimated average precision of its shot timer is plus or minus a tenth of a second, and it uses the word estimated.<sup>[3]</sup> That is the only timer figure in this report accompanied by its own qualification, and it is the right way to state one.

The arithmetic sets the floor. A camera resolves an event no more finely than the gap between two of its frames, which is about 17 milliseconds at sixty frames a second and about 33 at thirty. A tenth of a second is three frames at thirty, so Dry Fire Online's figure reads as the right territory for a camera-based timer rather than an optimistic one.

### One project steps around the floor entirely

The frame interval only binds a timer that reads the clock off the picture. An open-source project called opendryfire, published in August 2026 under the Apache licence, takes the draw from the sound instead: it plays the start beep and records the striker's click on the same audio stream, and takes the draw time as the distance between the two samples divided by the sampling rate.<sup>[4]</sup>

At 48,000 samples a second the granularity of that measurement is about 20 microseconds, against 33 milliseconds for a thirty-frame camera -- better by three orders of magnitude. And because the beep and the click are recorded on one stream, the measurement has no clock-synchronisation problem to get wrong: it is a distance between two marks on the same ruler, not a comparison of two devices.

It is one small, very young project and nothing here has tested it. But the idea is sound, it is free to read, and it is the only approach in this report that is not limited by the frame rate of a camera.

## What a timer cannot do for you

A timer cannot tell you the shot was good, only that it was quick.

That is why the method pairs every timed drill with a standard for the hit, and why the sentence from chapter 1 belongs here too: if you are perfect, you are not pushing. A par time you always make is a par time that has stopped teaching you anything, and an app that shows you only the clock will let you get faster at missing.

Set the par so you miss it sometimes. Watch the splits rather than the total. And check the hit standard has not quietly slipped while the clock improved.

## Key takeaways

- Most par times are yours to set, and a standards drill is the exception.
- If you never miss your par, the par is too slow.
- Splits are the number worth paying for.
- A camera resolves an event no more finely than the gap between its frames.
- Timing a draw from the audio instead sidesteps that limit by three orders of magnitude.
- One vendor publishes its timer precision as an estimate, which is the honest way.
- Bring the timer in only once the basics are smooth, and withdraw it again whenever you change a technique.

## Endnotes for this chapter

All product statements in this chapter were checked against the vendor's own pages in October 2026.

1. Ben Stoeger, *Dryfire Reloaded* (2017), for shooter-set par times, the Standards drills whose times are supplied, and the principle that a par you always make is too slow.
2. Stoeger, *Dryfire Reloaded*, Part 3, "Ingraining Technique", for introducing the timer after the basics and removing it while changing a technique.
3. Dry Fire Online, dryfireonline.com manual, for the stated estimated average shot-timer precision of plus or minus a tenth of a second, and for split times on its highest tier.
4. opendryfire, its public repository and README as checked in October 2026, for the Apache licence, the August 2026 first publication, and the acoustic draw time taken as the distance in samples between the start beep and the striker click recorded on one 48 kHz stream.
