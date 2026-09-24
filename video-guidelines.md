# BiztechCS Video Guidelines

Brand rules for BiztechCS explainer videos (YouTube, LinkedIn). The written companion to the
[Brand Guidelines](brand-guidelines.md); where the two differ, this file wins for video.

Reference build: *Fixed-Price Odoo Upgrades* (September 2026, 1:58).

---

## 1. Format

| | |
|---|---|
| Canvas | 1920 × 1080, 30 fps, H.264 |
| Length | 1:45 – 2:00 of narration, then the standard logo end credit (6.9 s, always played in full) |
| Voice | One narrator, conversational, second person. BiztechCS is named once, in the third person |
| Structure | Problem hook → "here's how" roadmap → 3–4 proof beats → proof block → conditional bridge → "Let's connect." |

## 2. Colour

Video uses the live-site palette so the film matches biztechcs.com, not the print palette.

| Role | Value |
|---|---|
| Ground (navy) | `#002E74`, rendered as one radial gradient: lighter `#0A3F92` top-right, deeper `#001D52` bottom-left. No blurred glow discs, no full-screen linear gradients (they band under compression) |
| Structure (teal) | `#35B0BF` — bars, boundaries, links, lit tiles. Light teal `#7FE3EE` for lit icons |
| Risk / action (orange) | `#E85C0D` — overflow bars, stamps, the CTA button |
| Accent text | `#FF9A5C` (orange lifted for AA contrast on navy) |
| Type | `#FFFFFF` headlines · `#B9C6E4` sub-lines · `#DFE7F7` labels |
| Paper (documents) | `#F6F8FC` with navy text and icon teal `#176C76` |
| Dot grid | 44 px spacing, white at 16 % |

Every text colour must pass WCAG AA against what is actually behind it. Orange-filled chips with
white text fail; use an orange outline with a 22 % fill instead.

## 3. Typography

Inter only.

| Element | Spec |
|---|---|
| Headline | Inter 800, 70 px, line-height 1.08, letter-spacing −0.025em. Two lines; the second (payoff) line in accent `#FF9A5C`. Never wraps |
| Eyebrow | Inter 700, 22 px, letter-spacing 0.18em, uppercase, accent colour, with a 34 × 4 px orange bar to the left |
| Sub-line | Inter 400, 32 px, `#B9C6E4`, sentence case, ends with a full stop |
| Chips | Inter 600, 24 px, pill, teal outline (facts) or orange outline (risk) |
| Card UI | Inter 500–700, 20–30 px. Code in the system monospace at 16 px |
| Counters / figures | tabular numerals |

## 4. Layout

- **Text column** left: x = 120, width 800. Eyebrow at y 356, headline at y 414, sub-line at y 612, chips at y 690.
- **Object zone** right: x 980–1820, **centred vertically on y = 540**. Cards, documents and diagrams sit on the frame's mid-line.
- **Logo** white wordmark, 210 px wide, at (80, 54). Static; never animated. Hidden only during the end credit.
- Headline and object never overlap; nothing is placed over a person's face.

## 5. On-screen copy (the slide system)

Every slide, no exceptions:

| Layer | Rule |
|---|---|
| Eyebrow | 1–3 words naming the section (`THE PROBLEM`, `HOW IT WORKS`, `THE PROOF`, `NEXT STEP`). Same label for the whole section |
| Headline | 2–6 words, Title Case, no full stop. Compresses the spoken line, never repeats it. Parallel forms welcome: "Same on a Call, Not on a Timesheet" |
| Sub-line | Optional. Sentence case, ends with a full stop, ≤ 12 words |
| Chips | Specifics: numbers, names, short lists. Title Case |
| Symbols | Only `%` and `+` inside figures. No ticks, no "VS", no exclamation marks, no arrows in text, no typing cursors left on screen |
| Stats | A number appears once per slide — in the headline **or** in the graphic, never both |
| Claims | No duration or cost claims that read as delivery promises ("under 2 minutes") |

Text on every slide, so the video works on mute. The only exception is a product screen recording whose picture already carries the line.

## 6. Cards, documents, shadows

- Glass cards on navy: `rgba(255,255,255,0.08)` fill, 1.5 px `rgba(255,255,255,0.22)` border, 26–28 px radius.
- **Cards over footage are solid** (`rgba(0,27,74,0.9)` or more). Glass over footage makes numbers unreadable.
- Documents are paper (`#F6F8FC`) with a navy title rule, icon-led rows and a stamp in the empty part of the title row.
- Shadow is a layered contact shadow — `0 1px 2px 35 %`, `0 10px 22px 32 %`, `0 26px 48px 22 %` in navy-black. Not one large blur.
- No film grain or noise overlays.

## 7. Iconography

Flaticon **Uicons, regular rounded** — the same family as the website. Icons appear only where they label something: a card header, a module badge, a tile in a map. Never on chips, headlines or eyebrows. Lit state = light teal `#7FE3EE`.

## 8. Footage

- Stock only for human moments (a call, a review, a signature). Product and UI moments are designed, not filmed.
- Casting for a UK/US audience; check the downloaded clip, not the thumbnail, including hands-only close-ups.
- 1080p sources, transcoded to 1920 × 1080 H.264 30 fps with audio removed.
- Treatment: full-bleed, navy wash from the left (97 % → 0 % at 78 % of the width), soft vignette, a slow push-in (1.05 → 1.11) over the scene. Natural skin tones must survive the wash.
- Proof beats use footage that matches the words spoken (production line, retail floor, service desk).

## 9. Motion

- Premium/editorial register. Entrances 0.5–0.8 s (`power3.out` / `expo.out`), card deals `back.out(1.4)`, flips 0.7 s `power2.inOut`. Exits are faster than entrances.
- Headlines rise word by word through a mask; sub-lines fade up; chips pop in.
- One ambient move per scene (push-in on footage, a float on cards, a breathe on a glow). Stillness after motion is allowed.
- Two transitions only, alternated: a zoom-through into designed scenes, a directional blur push into footage. 0.4–0.5 s.
- Every spoken number lands on its visual at the word: the bar reaches 20 on "twenty", the counter ticks on "difference", tiles light on "Sales, inventory, accounting".
- One visual motif develops across the film (for example a scope document that writes itself, is stamped, and returns in the CTA).

## 10. Sound

- Narration first; a soft corporate bed under it, ducked and EQ-carved so the voice stays clear, faded out before the end credit.
- Sound marks on the beats that snap: a whoosh on every transition (peak on the cut), a slide on card entrances and flips, a soft pop on chips and tiles, a tick on counters, one low impact on the stamp. Two to three marks per scene, not more.
- No sound effect on headline text.

## 11. CTA and end credit

- CTA slide: eyebrow `NEXT STEP`, headline "Book Your [X] Assessment" (or the offer), sub-line with the promise, an orange **Let's Connect** button that pops on the spoken "Let's connect."
- Then the standard **Biztech logo animation** (6.9 s, white ground, its own sound), played in full. The corner logo and the music fade out just before it.

## 12. Delivery checklist

1. Every slide has an eyebrow, a headline, and readable text with the sound off.
2. Copy checked: Title Case / sentence case, no stray symbols, no repeated stat, no duration claim.
3. Nothing overlaps; nothing covers a face; right-side objects are on the mid-line.
4. Contrast passes AA on every text element against its real background.
5. Frames pulled from the **rendered file** (not the preview) reviewed at every text beat.
6. End credit present and complete; audio present to the last frame.

---

*Video guidelines v1.0 · September 2026*
