# Usability Review

## Summary

v4 is designed for users who want to upload several reference images and extract a reusable template rather than receiving separate prompts for each image.

## Best-fit tasks

- multi-image style reference analysis
- reusable image prompt template creation
- product visual system extraction
- style board prompt frameworks
- SKU and variant template creation
- single-image reverse prompting when needed

## Expected strengths

- Distinguishes shared style from one-off details.
- Makes output reusable through variable fields.
- Supports product consistency through Product Lock and Product Variable Lock.
- Works for future products, subjects, scenes, and format requirements.

## Expected limitations

- Visual models may misread small or unclear text.
- Product structure still needs manual checking when references are low-resolution or inconsistent.
- Multi-reference extraction depends on reference quality.
- Final image quality depends on the downstream image-generation model.

## Recommended usage

Use 3 to 10 related references when possible. Similar references produce stronger templates. If one image matters more than the others, tell the agent which reference is primary.
