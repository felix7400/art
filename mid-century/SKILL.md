---
name: mid-century
description: Flat, angular mid-century figures on black with huge hands in front, small heads behind, thin deliberate lines and chalk grain; use for bold poster-like scenes and loops drawn in code.
---

# Mid-Century

Flat, angular figures on black: huge hands in front, small heads behind, thin deliberate lines and chalk grain, like a mid-century jazz poster.

## Rules
1. Near is huge, far is small. Hands and objects in front are about twice as wide as the face.
2. Crop hard: the biggest object runs off two edges of the picture. One long diagonal tips the composition from corner to corner.
3. Flat areas, no shading. At most three tones per shape (light, mid, shadow) with hard edges; a black wedge separates two shapes of the same colour.
4. Every line has a job: only where two areas of the same colour meet, or for a fold, seam or joint. No outlines around shapes that already stand out.
5. Lines are 2.2–4 px at 1000 px width, even, tapered at both ends. Edges wobble up to 1.8 px like a hand-pulled brush.
6. Build a hand from shapes: back of the hand, lit knuckles, shaded fingertips, the thumb across.
7. Flying bits stay abstract: strokes, squares, triangles. Show only what belongs to the action.

## Palette
| Name | Hex | Use |
|---|---|---|
| black | #07070a | ground, always |
| ink | #050506 | lines, shadow wedges, hair |
| chalk white | #f3efe6 | steam, cuffs, highlights, the only light |
| cobalt | #3a55c2 | clothing |
| vermilion | #d4482a | fire, glove, scarf |
| ochre | #d8a443 | wood, rice, posts, inner flame |
| skin (one family per figure) | #94532f #6d3820 #4a2414 · #d99a6c #c27f55 #94573a | light, mid, shadow |

## Texture
Chalk grain over everything: light areas slightly blotchy, with diagonal dry-brush streaks and specks; black carries faint blue wipes at 5 %. In a loop the grain stays fixed on the paper, only the moving shapes change.

## Never
- green, violet, pastels, gradients, soft shadows, transparency (except faint wipes and camera flashes)
- an outline around every shape, black lines on black, crossing contours
- everything whole and centred
- recognisable miniatures as flying bits, text in the picture

## Code
Draw on an HTML canvas. One `params` object at the top with a `seed`: same seed, same image. Loops run at 12 drawings per second, every motion a whole number of periods. Examples are in the folders next to this file.
