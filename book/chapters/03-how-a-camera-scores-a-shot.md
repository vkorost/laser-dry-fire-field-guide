# Chapter 3: How a Camera Scores a Shot

*Every camera-based trainer in this report does the same four things in the same order. It needs light of a kind it can see, it has to work out where your target is, it has to pick your dot out of everything else in the room, and then it turns a pixel into a number and a time. That order is how you read a product page, and it is also the order to work through when a setup is misbehaving.*

## Step one: light the camera can see

The first requirement is the one most often discovered after buying, and it is about the laser rather than the software.

Mantis Laser Academy works with red and green visible lasers and will not work with infrared.<sup>[1]</sup> LaserHIT rules out infrared as well.<sup>[2]</sup> Dry Fire Online rules out both infrared lasers and USB webcams, so it wants a visible dot and a phone or tablet camera to see it with.<sup>[3]</sup>

Then iMarksman goes the other way entirely. It is built around an infrared training handgun, and its calibration sensor camera carries an infrared filter to match.<sup>[4]</sup>

Read those together and the rule is clear enough to shop by. Infrared is not a brighter laser or a better one. It is a different arrangement, and the camera has to have been built for it, which is why a cartridge that works well with one product can be invisible to the next.

Brightness is the other half of the same question, and chapter 8 is where it belongs, because a cartridge too dim for the camera is the commonest reason a trigger pull leaves nothing behind.

## Step two: where the target is

Software that has found a red dot in a photograph still has no idea which part of your target that dot landed on. Four answers to that are documented in this category, and the one your product uses decides what happens every time the camera shifts.

**Marks printed on the target.** Mantis, LaserHIT and Strikeman all work from registration marks printed on the target face, which chapter 5 sets out product by product.<sup>[1, 2, 6]</sup>

**Zones you line the target up inside.** G-Sight's grouping mode is the example here, and it wants the bullseye and the corner dots placed before it will start.<sup>[7]</sup>

**No marks at all.** iTarget Pro locates the target and follows it, which removes the alignment step completely.<sup>[8]</sup>

**The display's own edges.** Dry Fire Online turns the screen green to find its borders, and iMarksman uses a separate calibration sensor camera.<sup>[3, 4]</sup>

With that comes a condition worth checking before you decide where the camera goes. Dry Fire Online will take it from any side of the screen as long as the whole display stays in view, and notes that extreme angles cost precision at the corners.<sup>[3]</sup> Its manual is equally plain about the consequence of a knock: move the camera and you calibrate again.<sup>[3]</sup>

Which of the four you end up with decides what a knocked tripod costs you, and chapter 5 draws that difference out for the products you are most likely to start with.

## Step three: your dot against everything else

Now the hard part, and the part the vendors hand straight back to you.

**Exposure.** Dry Fire Online runs two calibration stages, one for the screen boundary and one for the laser and the exposure, each automatic with a manual fallback.<sup>[3]</sup> Interactive Gun Range documents resetting camera exposure through Logi Tune or OBS Studio on macOS, and notes that low-light performance on iOS is limited by Apple's own camera interface.<sup>[5]</sup>

**Sensitivity.** iTarget Pro hands you a slider for it.<sup>[8]</sup> Interactive Gun Range's calibration includes a phase where you shoot the screen while watching a variance figure, with separate options for reducing false positives and false negatives.<sup>[5]</sup>

Those controls say something the marketing does not. The vendors know this is a trade-off with two bad ends, because a detector made more willing to see your dot becomes more willing to see a ceiling light, and chapter 8 is what that costs in practice.

The surface your target lives on belongs to this step as well, which is why three screen-based vendors give three different instructions about film, and why chapter 6 takes that apart on its own.

## Step four: a pixel becomes a score and a time

What comes out of the far end is a position, the ring that position falls in, and a time. Chapter 9 is the first two and chapter 10 is the third.

Exactly one vendor in this report publishes how precise that time is, and chapter 10 sets the figure against what a camera is able to resolve at all.

The thing to carry out of this chapter is that all four steps have to succeed before any number appears. A product page is usually written about step four, which is the step that tells you least about whether the thing will work in your room.

## Key takeaways

- Four steps: light it can see, the target's position, your dot, then a number.
- Infrared is a different arrangement rather than a brighter or better laser.
- Most products here refuse infrared, and one projector system is built on it.
- Printed marks re-align themselves, while a moved camera means calibrating again.
- Exposure and sensitivity are handed to you because both have two bad ends.
- All four steps have to succeed before the app can show you a single number.

## Endnotes for this chapter

All product statements in this chapter were checked against the vendor's own pages in October 2026.

1. Mantis Laser Academy, mantisx.com product and support pages, for the red and green visible-laser requirement, the exclusion of infrared, and the printed Smart Targets with corner markers and no electronics.
2. LaserHIT, laserhit.com, for the exclusion of infrared lasers and the Reload Mark accepted on a target the user prints.
3. Dry Fire Online, dryfireonline.com FAQ and manual, for the exclusion of infrared lasers and USB webcams, the screen-boundary and laser-and-exposure calibration stages with their manual fallbacks, the camera positions and the four-corner condition with its note on extreme angles, and the instruction to recalibrate after moving the camera.
4. iMarksman, shop.imarksman.com, for the infrared training handgun, the infrared filter and the calibration sensor camera.
5. Interactive Gun Range, its FAQ and support pages, for the calibration phase using a variance figure with options for reducing false positives and false negatives, the exposure reset through Logi Tune or OBS Studio on macOS, and the note on iOS low-light performance.
6. Strikeman, strikeman.com, for the four black and white corner squares used to calibrate its targets.
7. G-Sight, gsightsolutions.com, for the grouping-mode alignment of the bullseye and four corner dots into marked zones on the phone display.
8. iTarget Pro, itargetpro.com, for automatic target location and tracking and the manual laser sensitivity control.
