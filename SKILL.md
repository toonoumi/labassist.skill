---
name: labassist
description: Use when the user wants to develop black and white film or prints — asking for development parameters, times, dilutions, or a "recipe" for a given film stock and developer (optionally pushed or pulled N stops), or for a paper/print developer. Produces a complete step-by-step table (developer, stop, fix, wash) with times, temperatures, dilutions, and agitation.
---

# B&W Development Assistant

Give the user a complete, practical development recipe — for a roll of
black and white film, or for a print in the darkroom — as a table they can
tape to the wall.

## Step 0 — film or paper?

If the request is about developing a **print** (paper, enlarger, "print
developer" by name like Dektol/Multigrade/Selectol/LPD, RC vs fiber), use
`references/paper-developers.md` instead of the film workflow below — look
up the developer/dilution, pick RC or fiber time, and output that file's
process table directly. Paper has no push/pull and no reel agitation math;
don't apply Steps 1-3 below to it.

Otherwise, assume film and continue.

## Step 1 — identify the parameters

From the user's request, extract:

1. **Film stock** (e.g. Ilford HP5+, Kodak Tri-X 400, Kodak T-Max 100...)
2. **Developer** (e.g. HC-110, D-76, Rodinal, Xtol, Microphen...)
3. **Push/pull** (e.g. "push 1 stop", "rate at 800", "pull 1"). Default:
   box speed / no push/pull if not mentioned.
4. **Dilution**, if the developer supports more than one common dilution
   (HC-110, D-76, Rodinal, Ilfosol 3...). If not specified, pick the most
   common default dilution for that developer (see `references/dev-times.md`)
   and say which one you assumed.
5. **Temperature**, if not 20°C/68°F. Default to 20°C if unstated.
6. **Tank/reel format** only matters for chemical *volume*, not time — skip
   unless the user asks about volume.

Only ask a clarifying question if the film or developer is genuinely
ambiguous (e.g. "HP5" could mean HP5+ — just assume HP5+ and say so) or
missing entirely. Otherwise, fill reasonable defaults and state the
assumptions plainly rather than blocking on a round trip.

## Step 2 — compute the developer time

1. Look up the box-speed base time for the film/developer/dilution in
   `references/dev-times.md`.
2. If pushing or pulling, apply the multiplier from
   `references/push-pull.md`, and flag if the chosen developer pushes
   poorly (e.g. Rodinal beyond 1 stop).
3. If temperature isn't 20°C, apply the compensation in
   `references/full-process.md` and note the adjustment explicitly.
4. If the exact combo isn't in the table, say so, give the closest
   analogous estimate, and recommend the user cross-check the Massive Dev
   Chart (digitaltruth.com) before committing a whole roll. Never present a
   guessed time with unwarranted precision.

## Step 3 — pick the agitation scheme

Use `references/agitation.md`. Default to the standard scheme (initial
10-30s continuous, then 5s inversions every 30s) unless the user asks for
stand/semi-stand or names a very dilute Rodinal ratio.

## Step 4 — output

Produce **one markdown table** covering the whole process (pre-rinse
optional → develop → stop → fix → wash → Photo-Flo → dry), using
`references/full-process.md` as the template, with the developer row filled
in from steps 2-3. Columns: Step, Chemical, Dilution, Time, Temp, Agitation.

After the table, add a short "Notes" section (2-5 bullets, terse) covering
anything the user should know: assumptions made (dilution/temp defaults),
push/pull tradeoffs, fix-time caveat (clip test), and a one-line reminder
that B&W has decent exposure/dev latitude so this is a strong starting
point, not a law of physics.

Keep the response focused on the table + notes — no long preamble, no
restating the request back at the user.
