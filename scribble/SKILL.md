---
name: scribble
description: A quick pen sketch on cream paper, tone made only of zigzag scribbles and light left as blank paper; use for night streets, rain, crowds and loose figure studies drawn in code.
---

# Scribble

A quick pen sketch in a sketchbook: one warm black ink on cream paper, tone made only of zigzag scribbles, light left as blank paper, and figures that are dense scribbles with loose edges.

## Rules
1. One ink. Tone is never filled: it is small zigzag patches, and their spacing is the value (13 px apart is light grey, 3.6 px apart and four layers deep is nearly black).
2. Where the tone is light, the zigzag opens into separate, nearly parallel strokes, so it never shows a sawtooth.
3. Direction is material: the night sky is hatched along the rain, walls stand upright, a wet street lies flat in long horizontal strokes.
4. Light is paper left blank: a halo, a cone through the rain, a pool on the ground, a long streak of reflection. A thin ochre wash under the ink is the only colour.
5. Figures are dense back-and-forth scribbles that overshoot their outline, with thin tapered legs and a reflection of flat scribbles. Faces never show.
6. The drawing stops before the page does: it dissolves into ragged stray strokes and blank paper. Figures come out of that paper and go back into it.
7. In motion it is a flip book: what moves is re-scribbled 8 times a second with a new seed; the rest stays still.

## Palette
| Name | Hex | Use |
|---|---|---|
| paper | #EDE4D0 | the page, with fine grain |
| paper, lit | #F4EDDD | scraped-back windows, rain against the dark |
| ink | #1E1A16 | every line and scribble |
| wash | #E9BE62 | lamplight, multiplied under the ink, at most 50 % |

## Texture
Pen strokes taper at both ends and wobble in pressure. Loose lines are drawn twice and miss a little, with overshoot. Scribbles are 1.5–1.9 px at 1080 px width, slightly bowed, with rounded turns.

## Never
- grey fills, gradients on objects, blur or glow
- one hatching angle for everything
- clean outlines, faces, small details on figures
- hatching right up to the edge like a frame
- text in the picture

## Code
Draw on an HTML canvas. One `params` object at the top with a `seed`: same seed, same image. Examples are in the folders next to this file.
