# Claimed features

What each product's own documentation says it does, side by side, as of
**October 2026**.

**These are claims, not findings.** Nothing here was bought, borrowed or tested.
A cell says what the vendor publishes; it does not say the product does it, or
does it well. Where owners contradict a vendor the book says so — chapter 8 is
the whole account of that gap, and it is the chapter to read before buying
anything on the strength of a table.

**Blank means undocumented, and that is often the useful part.** "Not
documented" below never means "does not do it". It means the vendor's own pages
do not say, which is a fact about what you can know before you buy. Several of
the gaps are consistent across the whole category, and they are collected at the
end.

---

## Where the target is

The first question, because it decides everything else — the room you need, what
you aim at, and which failures you will meet.

Platforms are given only where the pages consulted name them. "Mobile app" means
the product is distributed through app listings without this book having recorded
which stores.

| Product | Target | What watches | Platforms |
|---|---|---|---|
| Mantis Laser Academy | Printed card target, corner markers, no electronics | Phone or tablet camera on a tripod, 1–3 yards | Mobile app |
| Strikeman | Vendor's own marked target; Open Target mode on the paid tier | Phone camera, up to about 3 feet | Mobile app |
| LaserHIT | Printed target; custom targets via a Reload Mark | Phone camera, 2–3 feet | Mobile app |
| G-Sight Laser Training Pro | Printed target, bullseye plus four corner dots | Phone camera | Mobile app |
| iTarget Pro | Printed target | Phone in a sled | iOS (App Store version history consulted) |
| iShooter | Target printed from the app | Camera | Mobile app |
| iDryfire | Any paper target | USB camera-sensor unit | Windows, macOS |
| Dry Fire Online | Targets drawn in a web browser, shown on a screen or projection | Its own phone or tablet camera app — **USB webcams excluded** | Browser, plus a phone or tablet camera app |
| Interactive Gun Range | Targets drawn by the game, on a projector, a matte monitor, a matte TV, or a glossy TV with anti-glare film | A webcam on a computer; the device camera on mobile | Windows via Steam; its own site also lists Mac, Android and iPhone |
| Laser Ammo Smokeless Range | Projected image; a television requires filter material taped over the screen | Its own tracking camera, supplied | Windows |
| iMarksman | Projected image | Calibration sensor camera with an infrared filter | Not documented here |
| PlinkPal | Phone-based | Phone | iOS, plus Apple Watch |
| iMarksmanTV + iDryfirePath | Game shown on a television | An iPhone clamped to the pistol — **no laser, no projector** | iPhone plus a computer |

## Hardware that needs no camera at all

| Product | What it is | App required |
|---|---|---|
| Laser Ammo LaserPET II | Standalone electronic target | No camera, phone or app |
| G-Sight Electronic Mini Target | Self-contained target | No phone or app |
| VPDOT | Reactive target | Stated: none required |
| Shooter Make Ready | Wireless laser targets | Reports each hit to a phone app |
| MantisX | Rail-mounted gyroscope and accelerometer — measures the press, not the hit | Yes |
| Next Level Training SIRT | Inert training pistol, red take-up laser and green shot laser | None |

## Laser type

Worth checking before buying a cartridge, because the exclusions are hard ones.

| Accepts visible red | Excludes infrared | Requires infrared |
|---|---|---|
| All camera systems listed above | Mantis Laser Academy, LaserHIT, Dry Fire Online, Interactive Gun Range | iMarksman (infrared handgun and filter) |

Mantis additionally accepts green. Laser Ammo's camera is offered with red or
infrared filtering. Interactive Gun Range states plainly: do not buy an
infrared laser.

## The screen surface, where a screen is the target

The one requirement in this group that cannot be adjusted away in software, and
the three vendors who address it do not agree.

| Product | What it asks for |
|---|---|
| Interactive Gun Range | A projector gives the best experience; modern matte computer monitors work, with small targets; a matte television works; a glossy television works with an anti-glare film applied |
| Dry Fire Online | Recommends a projector *instead of* a flat screen, on the grounds that anti-glare and polarizing filters reduce the dot's visibility; for a flat screen, a thin frosted film |
| Laser Ammo | A white projection screen, or a flat non-glossy white wall; for a television, filter material taped over the screen — a vinyl tablecloth — and it names a case that cannot be made to work at all |

Chapter 6 explains why these can all be right at once. The variable none of them
states is where the camera stands.

## Calibration

| Product | How it is set up |
|---|---|
| Dry Fire Online | Two stages — screen boundary, then laser and exposure — each automatic with a manual fallback; recalibrate after moving the camera |
| Interactive Gun Range | A phase in which you shoot the screen while watching a variance figure, with separate false-positive and false-negative options |
| Strikeman | Four black and white corner squares |
| G-Sight | Bullseye and four corner dots aligned into marked zones |
| Mantis Laser Academy | Printed corner markers |
| LaserHIT | A Reload Mark, which allows custom targets |
| iTarget Pro | Automatic target location and tracking, plus a manual sensitivity control |
| Laser Ammo | Not documented in the pages consulted |

## Scoring and timing

| Product | What it reports |
|---|---|
| Mantis Laser Academy | Hit locations, split times, scores |
| LaserHIT | Hit factor, defined as total score divided by total time; Virtual Spotter speaks split time, group, windage and elevation |
| iShooter | Hit factor; a local competition mode |
| PlinkPal | Hit factor |
| Dry Fire Online | Shot timer, stated as ±0.1 s and labelled an estimate; split times and hit scores on the top tier |
| Interactive Gun Range | Statistics written to a CSV file at the end of each mode |
| MantisX | Movement before, during and after the shot — a diagnostic of the press, which Mantis states Laser Academy does not do |
| opendryfire | Draw time from the audio: beep and striker click on one 48 kHz stream |

Chapters 9 and 10 are the account of what these measurements can and cannot
tell you, including why "hit factor" means different things on different pages.

## How they charge

No prices appear anywhere in this book or this file. Amounts in this category
move faster than any document can; the shape of the deal outlives them.

| Shape | Products |
|---|---|
| Free to play | Interactive Gun Range (personal, revocable, non-commercial licence) |
| Open source | opendryfire (Apache licence) |
| Free app, paid unlocks | Mantis Laser Academy; Strikeman (Open Target on Pro) |
| Subscription | Dry Fire Online (free tier limited to two shots per round); iShooter |
| Bought outright or bundled | iDryfire (licence, no subscription); Laser Ammo Smokeless Range (camera and software, add-ons separate, projector and PC yours) |

---

## What nobody documents

These gaps are consistent enough across the category to be a finding in their
own right, and each one is something a buyer would reasonably expect to be told.

**Where to put the camera.** Of the systems whose target is a screen, only Dry
Fire Online states a rule: anywhere, provided all four corners of the display
stay in view, with extreme angles costing precision at the corners. Laser Ammo
gives practical advice about reflections rather than a limit. Interactive Gun
Range's FAQ, setup page, download page and store listing contain nothing at all
on camera position, angle or distance. For a category defined by a camera
looking at a surface, that is a remarkable silence.

**Detection rate.** No vendor publishes one. Not a single page consulted states
what fraction of trigger pulls its system registers, under any conditions. The
only figures in this report of that kind come from individual owners, and they
are reported as single accounts because that is all they are.

**More than one shooter at a time.** Rarely addressed. Where multi-shooter
features exist they are generally separate targets or separate turns rather
than two people shooting one surface at once.

**What happens in a bright room.** Almost every product recommends controlling
the light; almost none quantifies it. "A consistently lit, dark or dim room" is
as specific as this category gets.

**How long setup takes.** Not stated by anyone — and chapter 12 finds that
setup friction, not thin content, is what ends most of these purchases.

---

*Compiled from the chapter endnotes. Every claim above is attributed to the
vendor page it came from in [SOURCES.md](./SOURCES.md), and argued in the
chapter that cites it.*
