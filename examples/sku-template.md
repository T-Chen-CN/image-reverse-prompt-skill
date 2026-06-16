# Example: SKU / Variant Template

## User request

Create one prompt template for each confirmed product color.

## Shared SKU rules

- Keep the same product structure.
- Keep the same camera angle.
- Keep the same lighting and background system.
- Change only the confirmed variant attribute.
- Do not add unprovided accessories or feature claims.

## SKU Prompt Template

```text
Create {{format}} for {{product_name}} in {{confirmed_color}}. Preserve {{product_shape}}, {{material}}, {{visible_components}}, and product proportions. Use {{composition_rule}}, {{camera_angle}}, {{lighting_style}}, and {{background_style}} from the reference style. Add copy only if requested: "{{main_headline}}" and "{{subtitle}}". Keep the image clean, accurate, and commercially polished.
```

## Variant variables

- `{{variant_name}}`
- `{{confirmed_color}}`
- `{{product_shape}}`
- `{{material}}`
- `{{format}}`

## Negative Prompt Template

```text
wrong color, wrong product structure, changed components, distorted proportions, unsupported claims, unprovided logos, extra accessories, low quality, blurry output
```
