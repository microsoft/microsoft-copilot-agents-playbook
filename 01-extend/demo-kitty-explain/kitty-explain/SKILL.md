---
name: kitty-explain
description: Generate a "Kitty Explain" meme-style cat visual explainer for summarized content of documents, articles, URLs, or concepts. Use when user asks something similar to "explain by cats".
---

## Role 

Explain about a given content as a sketchnote-like humorous image of the "Kitty explain" meme style featuring photorealistic kittens/cats. 

## Cat rendering rules

- Before generating the final image, inspect the file in references/ and prepare to generate kitten images that closely resemble the reference kittens. Pick most suitable cat image from the reference images to generate each cat. 
- Each generated cat image should be in a photorealistic cutout style. And it must visibly preserve the selected reference cats' fur pattern, face shape, eye shape, pose, and lighting. The generated cats should not be cartoonish, doodled, mascot-like, simplified, or visually disconnected from the reference images.
- Use props with cats where appropriate: make a cat wear eyeglasses for intellectual ideas, lab coats for experiments, briefcase for businesses, coins for things related to finance, or use other appropriate items.
- Keep playful meme-like expressions. 

## Overall visual styles

- Use white background.
- Use the instructions above to make cats look photorealistic.
- Use a hand-drawn sketchnote style with scribbled arrows, rough bullet points, messy block diagrams, loose pen lines, speech balloons, and playful labels, but never to the cats themselves.
- Use a Comic Sans-like lettering style for all text.
- Draw visual metaphors like charts for data, the scale of justice for legal, etc. that match the source content.
- Always include a title, and it should end with "explained by cats" or a close variant.
- Include the source URL if the user attached. Truncate long URL then end with "...", especially if the URL comes with query strings.
- Keep the tone playful, comedic and meme-inspired energy, while preserving the meaning of the source.
- Keep visuals simple, not too dense. Don't overdo.

## Steps

1. Identify the summarized source content into the most important ideas, keeping the explanation accurate and concise, but simple.
2. Create a single sketchnote-style image in the style that described above.
3. If the source content is missing or unclear, ask the user before generating the final image.

## Output

A single sketchnote-style explainer image featuring photorealistic cutout cats resembles the reference images.