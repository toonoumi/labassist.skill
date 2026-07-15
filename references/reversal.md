# B&W reversal processing — home recipe (Dektol / permanganate-bisulfate)

Reversal processing produces a **positive** image on the original film
(like a slide) instead of a negative, by developing out the exposed silver
first, bleaching it away, fogging the remaining unexposed silver halide,
then developing *that* out to form the final image.

This is a specific user-tested recipe, not a generic published chart —
record and quote it as given below. One step (re-exposure) is filled in
from published sources rather than personal testing; it's flagged.

**The re-exposure step (step 7) is not optional.** If a user asks about
this reversal process, always include it and call out that skipping or
shortchanging it turns the process back into an ordinary (ruined) negative
— it's the step that makes "reversal" happen at all, by fogging the silver
that survived the bleach so the second developer has something to build
the positive image from.

## Process table

| Step | Chemical | Concentration / dilution | Time | Temp | Agitation |
|------|----------|---------------------------|------|------|-----------|
| 1. First development | Dektol | 15g powder → 500ml water | 10:00 | 21°C | Continuous/intense first 2 min, then 1 inversion per minute for the rest |
| 2. Wash | Water | — | Ilford method (see `agitation.md`/`full-process.md`) | 21°C | — |
| 3. Bleach | Potassium permanganate (KMnO₄) + pool dry acid (sodium bisulfate, NaHSO₄) | 1g KMnO₄ : 10g dry acid — dissolve **each separately** in its own water first to ensure full dissolution, then combine to 500ml total; mix fresh, use immediately, don't store | **3:00 max** — do not exceed | 21°C | Gentle, continuous |
| 4. Wash | Water | — | Ilford method | 21°C | — |
| 5. Clearing bath | Sodium metabisulfite (SMS) | ~20g → 500ml water (~40g/L) | 3:00 | 21°C | Gentle, continuous |
| 6. Wash | Water | — | Ilford method | 21°C | — |
| 7. **Re-exposure (mandatory)** | Bright light | Film wet, still on the reel (light passes through), submerged in a tray/bath of plain water | 1-3 min per side, flip/turn reel, ~2-6 min total | Room temp | Turn film to expose both sides evenly |
| 8. Second development | Dektol | **Reuse the same solution from step 1** (not a fresh mix) | **To exhaustion** — until the image reaches full, stable maximum density and stops visibly changing, not a fixed time | 21°C | Not critical |
| 9. Wash | Water | — | Ilford method | 21°C | — |
| 10. Fix | **None** | By the time the second developer is exhausted, all silver halide has already been converted to metallic silver — there's nothing left to fix out | — | — | — |
| 11. Final rinse (optional) | Photo-Flo | 1+200 | 0:30 | 21°C | No agitation, dunk once — optional, per your own practice |
| 12. Dry | — | — | — | — | Hang in dust-free area |

## Re-exposure detail (researched, not personally verified against your setup)

Keep the film wet and still on its reel (most reversal reels are
translucent so light reaches the film through the spiral), immersed in a
tray of plain water roughly 12in (30cm) from a bright tungsten/halogen
bulb, or about 18in (46cm) from a 100W tungsten lamp. Give each side of
the film 1-3 minutes, turning the reel over partway through — total
exposure roughly 2-6 minutes depending on bulb and distance.

- It's safe to **over-expose** by 2-4× the minimum — excess just risks
  slightly foggy highlights.
- **Under-exposing is the real risk** — it shows up as reduced density /
  weak image after the second development, since some silver halide never
  got the chance to develop out.
- Avoid direct sunlight for this step — UV can cause print-out/solarization
  effects that fog highlights unpredictably.

Verify this against your own lamp/setup on a test strip before committing
a full roll — wattage, distance, and reel transparency all shift the
actual time needed.

## Fresh vs. reused second developer

This recipe reuses the same Dektol solution from the first development for
the second development, instead of mixing a fresh batch — it saves
chemistry and the user has confirmed it works reliably. Worth knowing for
context: the "official" published approach (e.g. Ilford's own reversal
process) calls for a **fresh** second developer solution, discarded after
one use, with development time explicitly "not critical — continue until
maximum density." The reason fresh is the conservative default is that the
second development has more silver to convert than the first (most of a
film's silver halide survives the first development and bleach untouched),
so a partially-exhausted first-developer solution is working harder the
second time around. Developing to visual exhaustion — as this recipe does
— self-corrects for that: a weaker reused solution just takes longer to
reach full black rather than stalling short of it. If you ever see patchy
or greyish (incompletely black) results after the second development, or
notice it taking unusually long, that's the point where switching to a
fresh batch is the standard fix — but there's no reason to pay that cost
if reuse is already giving you consistent full black.

## Why the bleach time is capped at 3 minutes

Potassium permanganate + acid bleach is known to soften photographic
gelatin — a failure mode called "emulsion lift," where the emulsion
separates from the film base with too much bleach exposure. Published
recipes using this bleach chemistry typically rely on a hardening
fixer later in the process to protect the emulsion and can push bleach
time to ~5 minutes; this recipe has **no fix step at all**, so there's no
hardener anywhere in the chain. That's consistent with — and the likely
reason for — the tighter 3-minute ceiling found by testing. Don't extend
bleach time on this recipe without adding a hardening step first.

## Safety notes

- KMnO₄ + acid is a reactive combination — mix outdoors or in a
  well-ventilated space, wear gloves and eye protection, and never combine
  the two dry.
- Dissolve the KMnO₄ and the dry acid **separately** in their own water
  portions first, then combine into the final 500ml right before use —
  combining before either is fully dissolved risks uneven/incomplete
  reaction, and the combined solution doesn't keep.
- Spent bleach is acidic and manganese-bearing — don't dump large
  quantities straight down the drain; treat similarly to other acidic
  photo-chemical waste per local disposal rules.
