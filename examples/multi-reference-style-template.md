# Example: Multi-Reference Style Template Extraction

## User request

Use these 6 reference images to extract a reusable style template. I want to apply this style to future product images.

## Recommended response pattern

### Task Understanding

You want a reusable prompt template extracted from multiple references, not one prompt per reference. I will identify the shared visual system and convert it into a template with variables.

### Reference Set Summary

- Reference count: 6
- Visual category: commercial product creative set
- Best-fit use cases: product hero images, feature highlight images, SKU images, social commerce creatives
- Overall style direction: soft premium commercial product style with clean background, clear subject focus, controlled lighting, and concise copy hierarchy

### Shared Style DNA

- Composition: product-dominant layout with simple visual hierarchy
- Camera: clear product-facing angle, minimal distortion
- Lighting: soft commercial lighting with controlled highlights
- Background: clean studio-like background, low visual noise
- Color: restrained palette based on product color and soft supporting tones
- Graphic layout: short headline, supporting text, optional feature labels
- Mood: polished, accessible, marketplace-friendly

### Fixed Visual Rules

- Keep the product or subject as the primary visual focus.
- Use clean commercial lighting and controlled shadows.
- Keep text short and legible.
- Use background colors that support the subject color without overpowering it.
- Do not add features not provided by the user.

### Variable Fields

- `{{product_name}}`: product name or model
- `{{product_shape}}`: exact visible product structure
- `{{confirmed_color}}`: confirmed product color
- `{{material}}`: visible or confirmed material
- `{{main_headline}}`: main copy line
- `{{subtitle}}`: short supporting copy
- `{{feature_labels}}`: optional feature callouts
- `{{format}}`: requested image format

### Reusable Master Prompt Template

```text
Create {{format}} in a soft premium commercial product style. Feature {{product_name}} as the main subject, preserving {{product_shape}}, {{confirmed_color}}, and {{material}}. Use a clean product-dominant composition with controlled studio lighting, soft shadows, clear product edges, and a refined background that supports the product color. Add concise text only if requested: main headline "{{main_headline}}", subtitle "{{subtitle}}", and optional feature labels "{{feature_labels}}". Keep the visual hierarchy clean, modern, and easy to read. Do not add unsupported product features, logos, claims, accessories, or visual elements not provided by the user.
```
