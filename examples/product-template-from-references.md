# Example: Product Template From References

## User request

Analyze these product images and create a reusable template that I can apply to another product.

## Output pattern

### Product / Creative Type

Marketplace product image set with product hero, feature highlight, lifestyle use, and variant presentation.

### Shared Product Presentation Rules

- Product remains clearly visible and structurally accurate.
- Product color follows user-confirmed color.
- Lighting is clean and commercial.
- Copy is concise and does not add unsupported claims.
- Background supports the product instead of competing with it.

### Product Variable Lock

Required future inputs:

- `{{product_name}}`
- `{{product_category}}`
- `{{product_shape}}`
- `{{confirmed_color}}`
- `{{material}}`
- `{{visible_components}}`
- `{{format}}`

Optional inputs:

- `{{main_headline}}`
- `{{subtitle}}`
- `{{feature_labels}}`
- `{{scene_context}}`

### Product Hero Template

```text
Create {{format}} for {{product_name}} as the main subject. Preserve {{product_shape}}, {{confirmed_color}}, {{material}}, and {{visible_components}}. Use the extracted reference style: {{style_direction}}, {{composition_rule}}, {{lighting_style}}, and {{background_style}}. Add concise copy only if requested: "{{main_headline}}" and "{{subtitle}}". Keep the product accurate, clean, and commercially polished.
```

### Feature Highlight Template

```text
Create {{format}} in the same visual system for {{product_name}}. Show the product clearly with {{feature_focus}} as the visual emphasis. Use {{feature_labels}} only if supplied by the user. Keep the background, lighting, and copy hierarchy consistent with the reference style. Do not add unsupported feature claims.
```
