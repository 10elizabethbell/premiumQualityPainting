# Premium Quality Painting — handoff at ~60%

**Live:** https://10elizabethbell.github.io/premiumQualityPainting/ · **Repo:** https://github.com/10elizabethbell/premiumQualityPainting · **Built:** 2026-10-20 from Muse brief 2026-10-20 (cabinet-painting ad in three NJ contractor groups) · **Call Sheet:** site set (the script added a new entry; Muse hadn't put them on the sheet)

## What's built
- One page, calm band style: paper header (their gold serif lettering re-coloured navy, stacked on two lines; `(848) 667-3925` top right) → photo hero → "The finish is only as good as the prep." + their three ✅ lines → "What we paint" rows (navy) → before/after (light) → How it works (deep navy, texture) → "What color would you choose?" form (paper) → close (navy, gold lettering, big number) → footer (Facebook only; no email exists).
- Palette: deep navy `#0f1d38` (ink, deep bands), mid navy `#1c3157`, paper `#f4f6fb`, one gold `#e4b95c` sampled from their flyer (fills only; `#7a5812` when it must be text on light).
- Hero: their finished green room (the desk shot), upscaled and blurred under navy. On phones the overlay is even; from 1024px it fades left to right so the green cabinets show beside the copy. Sampled behind the actual text: white ≥6.9:1, gold ≥3.8:1 (large text) at 390, 760, 1024, 1440, 1920.
- H1 "Monmouth County cabinets, beautifully repainted." bounces in letter by letter; `.rise` fade-up below the first screen; both off under reduced motion and without JS (checked in Chromium and WebKit).
- Proof: two before/after cards. The big picture is the "after"; the "before" sits in a corner thumbnail (bottom left, gold "⇄ Before" label). Tapping the thumbnail or the big picture swaps them. Then "Click to see more of our work." → Facebook.
- Form: their own hook "What color would you choose?" as the heading; job chips, colour chips (Timeless white / Elegant green / Bold navy / Not sure yet, from their caption; picking green adds "That's the green in our photos above."), name, town, notes → pre-written text to (848) 667-3925, with Open in Messages / Copy ("Press and hold to copy" if the in-app browser blocks the clipboard) / call fallback. Tapping a service row ticks its chip.
- Floating text circle: hidden on the hero, shows below it, steps aside for row arrows and the Facebook arrow, hidden while the form is on screen.
- Favicon / home-screen icon: the gold "P" from their lettering on navy. `og.jpg` 1200×630 with the desk before/after.

## Assumptions I made
- **Navy ground** instead of the flyer's black (house rule: never black). Navy is the wall colour in their own job photos and "bold navy" is in their caption.
- **"Built-ins and shelving" and "Islands and desks"** as services come from the photos, not their words. Their words only say kitchen cabinet painting.
- **The care paragraph** ("The doors come off, the tops get wrapped and taped…") is written from the before photo (doors off and stacked on the desk, top wrapped in plastic and blue tape). Owner should approve.
- **"We go over the job with you and give you a price"** (step 2) is generic; I don't know whether they quote from photos or visit.
- **We/us voice:** the ad says "Send us a message".
- **Photos are a study/library, not a kitchen.** The page never calls them a kitchen; the heading is "Same room, new color."
- **Facebook link** goes to Fernando Oliveira's personal profile (the only place their work is posted). No business page exists.
- **"Monmouth County"** and "and surrounding areas" are theirs; the form's placeholder "e.g. Freehold" is my example of a Monmouth County town.

## Placeholders and gaps
- **Owner unconfirmed:** the ad came from Fernando Oliveira's personal profile; the page names nobody.
- No email (footer has none), no reviews, prices, hours, years in business, insurance or licence: the page says nothing about them.
- Photos: one flyer, ~290px per panel, upscaled 2×. Soft on a phone at 2×. The before and after in each pair are shot from different spots, so there's no drag slider.
- The "after" desk has a new dark stone top that wasn't in the "before"; worth confirming the after photos are real finished work and not a rendering.
- No kitchen photos at all, though kitchens are what they advertise.

## Questions for the owner
1. Is Fernando the owner? Can the page say "I'm Fernando…"?
2. Original, full-size photos, and any kitchen jobs (before and after from the same spot would allow a drag slider).
3. A business Facebook page, Instagram or email to link?
4. Do you quote from photos by text, or come out to look?
5. Which towns do you cover most?
6. Insured? Any customer reviews we can quote word for word?
7. Other things you paint (vanities, furniture, trim)?

## Ideas not built (yours to pick)
- Worlds from the trade, for an opt-in signature motion: (1) **a colour-swatch fan** — drag across the hero cabinets and the doors re-colour white → green → navy (best: it's their own "what color would you choose?" hook); (2) a brush stroke that paints wood to green across the hero as you drag; (3) painter's tape peeling off the headline; (4) cabinet doors that swing open on the services rows; (5) a fan deck of paint chips as the form's colour picker.
- A drag slider once there's an aligned before/after pair.
- Name the owner in the hero promise once confirmed.
- Review suggestions not taken: the finish reviewer proposed "Pick a color, get a quote" for the hero button; I used "Get a quote" (shorter, still honest that it goes to the form). It also noted the calm kit's header shadow on scroll; not built because the header isn't sticky.
- Impeccable findings kept by choice: the craft floor bans eyebrow pills (kept, your call). The finish reviewer flagged the missing concept-roll seed (the calm style is the house default). the detector flags the band texture ("repeating-gradient stripes") and a "flat type hierarchy" (it only counts small UI sizes). Both are suppressed for `index.html` in `.impeccable/config.json` with reasons.

## Not verified
- Real-device touch (tested with Playwright Chromium and WebKit, touch contexts).
- Real SMS handoff on iOS/Android and inside Facebook's in-app browser (message body decodes correctly in tests).
- Frame rate on old phones (motion is short CSS only).
