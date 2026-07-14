# Push / pull processing

Pushing = rating the film at a higher EI than box speed (underexposing) and
compensating with extra development time, which builds contrast and
apparent speed. Pulling = rating lower than box speed (overexposing) and
cutting development time, which lowers contrast.

## Time multipliers

Apply to the box-speed base time from `dev-times.md`. These are the widely
used rule-of-thumb multipliers — real answers vary by developer and film, so
prefer a developer-specific note below when one exists.

| Adjustment      | EI relative to box speed | Multiply base time by |
|-----------------|---------------------------|------------------------|
| Pull 2 stops     | 1/4×                      | 0.60 |
| Pull 1 stop      | 1/2×                      | 0.75 |
| Box speed        | 1×                        | 1.00 |
| Push 1 stop      | 2×                        | 1.40 |
| Push 2 stops     | 4×                        | 1.85 |
| Push 3 stops     | 8×                        | 2.50 |

Round to the nearest 15 seconds. Don't chase false precision — a 15-30s
difference in an 8-10 minute development is within normal variance.

## Developer-specific pushability

- **Solvent developers (D-76, ID-11, Xtol, HC-110):** Push cleanly up to 2
  stops, acceptable to 3 with a contrast/grain penalty. Use the multiplier
  table as-is.
- **Rodinal / high-acutance developers:** Pushes poorly — grain and contrast
  increase fast. Cap recommendations at push 1 stop and warn the user.
- **Microphen, Ilfotec DD-X, and other "speed-increasing" developers:** built
  for pushing. They push 2-3 stops with comparatively little grain/contrast
  penalty — use the low end of the multiplier range, or the film's specific
  higher-EI time if listed in `dev-times.md` (e.g. HP5+/Microphen or Delta
  3200/Microphen).
- **Pulling:** most useful for reducing contrast in high-contrast/bright-sun
  scenes. Rarely needed beyond 1 stop for typical shooting.

## Example calculation

HP5+ (box 400) pushed 1 stop → shoot at EI 800. In HC-110 dilution B, base
time is 6:00. Push 1 multiplier ×1.40 → 8:24, round to **8:30-9:00**.
(Commonly published charts list ~9:30 for this combo — within normal
variance; either is a reasonable starting point.)
