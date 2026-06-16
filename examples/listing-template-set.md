# Example: Listing Prompt Template Set

## User request

Use this reference set to create a reusable product listing image template set.

## Shared Style DNA

- product-focused commercial design
- clear hierarchy
- controlled background
- short copy
- consistent lighting
- accurate product structure

## Shared Negative Prompt

```text
wrong product structure, wrong variant color, distorted proportions, unreadable copy, unsupported claims, unprovided logos, extra accessories, low quality, blurry output, cluttered background
```

## Template 1 — Product Hero

Purpose: primary product presentation

```text
Create {{format}} for {{product_name}} as the main subject. Preserve {{product_shape}}, {{confirmed_color}}, {{material}}, and {{visible_components}}. Use the extracted reference style: {{style_direction}}, {{composition_rule}}, {{lighting_style}}, and {{background_style}}. Add concise copy only if requested: "{{main_headline}}" and "{{subtitle}}". Keep the product accurate, clean, and commercially polished.
```

## Template 2 — Feature Highlight

Purpose: show key feature or benefit

```text
Create {{format}} in the same visual system for {{product_name}}. Show the product clearly with {{feature_focus}} as the visual emphasis. Use {{feature_labels}} only if supplied by the user. Keep the background, lighting, and copy hierarchy consistent with the reference style. Do not add unsupported feature claims.
```

## Template 3 — Lifestyle Use

Purpose: show product in context

```text
Create {{format}} showing {{product_name}} in {{scene_context}} while preserving {{product_shape}}, {{confirmed_color}}, and {{material}}. Keep the extracted style direction: {{style_direction}}, with clean composition, controlled lighting, and a background that supports the product. Add short copy only if requested.
```
