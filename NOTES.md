# Transcription Notes

Notes on how [README.md](README.md) was produced from the photographs, and what in it is inferred rather than read.

## Source photos

The four sheets are kraft paper, hand-lettered, taped up in layers and photographed flat on a concrete floor on 2026-09-18.

| Photo | Sheet |
| --- | --- |
| `PXL_20260918_121040631.jpg` | Stainless Steel Machine Screws |
| `PXL_20260918_120913287.jpg` | Stainless Steel (nuts, washers, set screws) |
| `PXL_20260918_120938474.jpg` | Real Steel |
| `PXL_20260918_121002068.jpg` | Classic Brass |

Two photos came off the camera rotated relative to the writing — the brass sheet by 90° and the stainless machine-screw sheet by 180°. Both have since been rotated upright in place with `jpegtran -perfect`, which transforms the JPEG coefficients directly, so the image data is unchanged rather than re-encoded. The as-shot versions remain in the first commit.

## Conventions of the original sheets

Headings are in red, sizes in green or pencil, bin numbers prefixed `#`. Sizes are written smallest to largest, in the form `thread × length` where a length is given at all. Grouped sizes sharing one bin are bracketed in a vertical stack; alternative sizes are separated by slashes.

The sheets are inconsistent about the inch mark on thread sizes — the nuts sheet writes `1"-14` while the machine-screw sheet writes `1-8 × 8` — so README.md marks every whole-inch diameter and leaves gauge numbers bare, which is what the washer rows (`0 → 1"`) already did. No size was changed, only its notation.

Fastener names in README.md are normalized to one spelling per fastener, so the same item reads the same way in every material: the Real Steel sheet's `Hd.` is expanded to `Head`, which is how the other three sheets write it. Wording is otherwise left as the sheets have it, including the order of the words — `Fillister Head Slotted Machine Screws` is the catalog's order, not a garbled one. No name was given a qualifier its sheet does not carry, which is why `Slotted` and `Finished` appear on the stainless rows but not on the Real Steel and brass rows that name the same head styles.

Row order in README.md is by bin number. Two sheets do not run in that order — the Real Steel sheet puts Hardened Washers and Wing Nuts out of sequence near the bottom, and the brass sheet leads with Hex Head Cap Screws — so those rows were moved. No row was added, dropped, or merged.

## Inferred or uncertain readings

- **The Nylock line.** On the stainless nuts sheet this is squeezed between Wing Nuts and the rule above Finished Full Nuts, in a smaller hand than anything else on the page. The sheet spells it `NY-LOCK`; README.md uses `Nylock`, the common generic spelling for a nylon-insert lock nut. (The registered brand is spelled Nylok, without the `c`, and nothing on the sheet claims that brand.) It is an annotation rather than a heading: a bracketed stack of four sizes against bin 3361, then a slash-separated list of three against 3362.
- **Top entry of the 3361 stack.** Partly obscured by a line written over it. Read as `6-32` from the stroke shape and from sitting directly above `8-32`. Least certain character on any of the four sheets.
- **The inverted inequality.** Faint pencil above the Nylock line reads `>1/4-20  3361`. Under magnification the glyph is unambiguous as drawn — two strokes converging to a vertex on the right, a greater-than sign, not an arrow. But as `>` it contradicts the line below it, since the sizes above 1/4-20 are the ones assigned to 3362, whereas as `<` it is a consistent shorthand for the bracketed stack, all four of whose sizes fall below 1/4-20. Taken as an inverted sign in a hurried marginal note and read as "below 1/4-20 → 3361". This changes no bin assignment; the stack and the pencil note then say the same thing.
- **Round Head Slotted start size.** The leading digit of `1-72 × 3/16` sits on the torn bottom edge. `1-72` is inferred from the two rows above, which both start at 1-72.
- **`#3288`.** The Finished Full Nuts start bin is written in red and traced over in green. Both tracings read 3288 — re-inking, not a correction.

## Physical condition

The brass and stainless machine-screw sheets are taped over further sheets beneath them, and both carry ruled tick marks down one margin with no text beside them. There may be more sheets than these four photos captured.

The stainless nuts sheet is torn at the Finished Jam Nuts row and the Real Steel sheet is torn across the Hex Socket Set Screws row. No characters are lost in either tear.
