---
name: kitty-explain
description: Turn source content into a humorous sketchnote-style explanation featuring photorealistic cats based on the cat images in the references folder.
---

# Purpose

Explain user-provided content as a single humorous sketchnote-style image in the "Kitty Explain" meme style.

The finished image must combine:

1. Photorealistic cat cutouts whose appearance closely matches the supplied cat reference images.
2. Hand-drawn sketchnote annotations, diagrams, arrows, labels, and visual metaphors.
3. A concise and accurate explanation of the source content.

# Reference-image workflow

Complete this workflow before constructing the image-generation request.

1. Locate all cat images in the `references` folder.
2. Open and visually inspect every available reference image.
3. Confirm that at least one reference image was successfully opened and is readable.
4. Select one or more references that best match the roles needed in the sketchnote:
   - Use one primary reference for each featured cat.
   - Use additional references only when the scene requires multiple cats with visibly different roles.
5. Supply the selected reference images to the image-generation request as visual character references. 
6. For each generated cat, closely preserve the selected reference cat's:
   - fur color and pattern
   - facial structure and muzzle shape
   - eye size, color, and spacing
   - ear shape and proportions
   - body proportions
   - realistic fur texture
   - photorealistic cutout appearance
7. The cat may have a new pose, expression, prop, or costume appropriate to the explanation, but the cat must remain recognizably consistent with the selected reference.
8. If the reference images cannot be accessed, generate the highest-quality photorealistic cute kittens possible that match the intended "Kitty Explain" aesthetic. Maintain:
    - realistic fur texture and natural lighting
    - realistic kitten anatomy and proportions, including proportionally large bright eyes and large ears
    - expressive, meme-like poses and facial expressions
    - photographic cutout appearance
    - consistent visual style across all cats in the image
Do not substitute with cartoonish, doodled, mascot-like, simplified, clip-art, illustrated, low-detail, or obviously AI-generic cat designs. The cats should still feel like authentic "Kitty Explain" characters even when the original references are unavailable.

# Content workflow

1. Read all user-provided source material before generating the image.
2. Identify the central topic and three to five essential ideas.
3. Rewrite those ideas in short, plain-language phrases suitable for a sketchnote.
4. Preserve factual meaning. Do not invent claims, statistics, quotations, or conclusions.
5. Choose a simple visual sequence, grouping, comparison, or cause-and-effect structure.
6. Assign an appropriate role to each cat, such as teacher, learner, researcher, business presenter, banker, chef, etc.
7. Construct one complete image-generation request using the selected reference images and the visual rules below.

# Visual rules

## Cats

- Cats must be photorealistic photographic cutouts.
- Cats must visually match their selected reference images.
- Expressions and poses may be playful and meme-inspired.
- Use props only when the props reinforce the explanation:
  - eyeglasses for analysis or intellectual concepts
  - lab coat or safety goggles for experiments
  - briefcase for business topics
  - coins, calculator, or ledger for finance
  - magnifying glass for investigation
  - pointer for teaching
- Props must not obscure defining facial features or important fur markings.
- Do not draw, sketch, outline, or cartoonize the cats.
- Do not use visually inconsistent cat styles within the same image.

## Sketchnote treatment

- Use a clean white or warm-white paper background.
- Surround the photorealistic cats with hand-drawn sketchnote elements.
- Use loose black pen lines with a small number of accent colors.
- Use scribbled arrows, rough bullet points, simple block diagrams, speech balloons, underlines, circles, and playful labels.
- Keep the hand-drawn treatment on the annotations and supporting visuals, never on the cats themselves.
- Use simple visual metaphors appropriate to the topic, such as:
  - charts for data
  - balance scales for legal concepts
  - gears for processes
  - bridges for connections
  - road signs for decisions
  - magnifying glasses for investigation
- Keep the composition spacious, readable, and intentionally imperfect.
- Do not overcrowd the image.
- Use a maximum of three to five major explanatory ideas.

## Text

- Always include a short title.
- The title should end with "Explained by Cats" or a natural close variant.
- Use friendly, informal, hand-lettered comic-style text.
- Prefer short labels and phrases instead of sentences or paragraphs.
- Keep every text element large enough to read.
- Check spelling, terminology, numbers, and labels before finalizing.
- Do not use placeholder text, gibberish, or invented quotations.
- If reliable text rendering is not possible, reduce the amount of text rather than creating dense or illegible writing.

## Source attribution

- If the user supplied a source URL, include a small source label near the bottom edge of the image.
- Use the domain name plus a shortened path when possible.
- Remove query strings, tracking parameters, fragments, and credentials.
- Never expose private tokens or sensitive URL parameters.

# Image-generation prompt requirements

The final image-generation request must explicitly state:

- which reference image is assigned to each cat
- that the selected image is a visual character reference
- which physical characteristics must be preserved
- that the cats are photorealistic photographic cutouts
- that annotations are hand-drawn sketchnote elements
- that the cats themselves must not be illustrated or cartoonized
- the title and exact short labels that should appear
- the intended arrangement of cats, concepts, diagrams, and text
- that the final output is one cohesive sketchnote image

# Quality check

Before returning the result, verify that:

1. At least one reference image was successfully accessed and supplied to the image-generation request.
2. Every cat is recognizably consistent with its selected reference.
3. Cats are photorealistic, while annotations are hand-drawn.
4. The explanation is factually faithful to the source.
5. The title ends with "Explained by Cats" or a close variant.
6. Important text is readable and correctly spelled.
7. The composition is not overcrowded.
8. Any displayed source URL is safely shortened.
9. No generic or cartoon substitute cat was introduced.

# Output

Return the generated sketchnote image as the primary output.

If image generation cannot use the selected reference images, clearly state that limitation instead of claiming that the generated cats match the references.