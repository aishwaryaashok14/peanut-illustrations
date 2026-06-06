# Image Generation Prompt Template

Generate each image on its own. Replace the variables from the user's prompt. Do not combine several ideas into one image.

```text
Generate one standalone 16:9 horizontal concept illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. A single warm-orange accent color used sparingly for one point of emphasis (no other colors). Clean, deadpan, slightly absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring character required:
A peanut — a whole in-shell peanut with the pinched figure-8 shell shape, light hand-drawn cross-hatch shell texture, small white dot eyes, two tiny thin legs, a blank serious expression, and a slightly uneven hand-drawn outline. The peanut must perform the core conceptual action, not decorate the scene. Keep the peanut deadpan, calm, unbothered, and only slightly absurd — never cute.

Theme:
{the idea to illustrate}

Structure type:
{Workflow / System slice / Before-after / Character state / Concept metaphor / Layered method / Map-route / Mini comic}

Core idea:
{the single thing this image must express}

Composition:
{the concrete scene: where the peanut is, what it is doing, the main object, how things flow}

Suggested elements:
{element 1} / {element 2} / {element 3}

Handwritten English labels:
{label 1} / {label 2} / {optional label 3}

Color use:
Black for all line art and the peanut. One warm orange as the single accent, used only for the one most important thing (the main flow, the key arrow, the result, or the critical word). Use no other colors.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten English labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Invent a fresh visual metaphor for this specific prompt. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## Image edit prompts

Remove a top-left title:

```text
Edit the provided image. Remove only the handwritten title "{text to remove}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: the peanut, labels, paths, line style, the single orange accent, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Make the peanut more central:

```text
Regenerate this illustration with the same core meaning and simple layout, but make the peanut more central to the conceptual action. The peanut should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, single warm-orange accent, and not cute.
```

Swap the accent color:

```text
Regenerate this illustration unchanged except for the accent color: replace the warm orange with {new color}, used in exactly the same restrained way for the single point of emphasis. Keep everything else identical — black line art, the peanut, composition, labels, and whitespace.
```
