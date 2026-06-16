# Template Variable System

Use variables when the user wants reusable prompts or multi-reference style templates.

## Common variables

### Subject variables

- `{{subject}}`
- `{{product_name}}`
- `{{product_category}}`
- `{{character_type}}`
- `{{scene_subject}}`

### Visual variables

- `{{format}}`
- `{{composition_rule}}`
- `{{camera_angle}}`
- `{{lighting_style}}`
- `{{background_style}}`
- `{{color_palette}}`
- `{{material_texture}}`
- `{{style_direction}}`
- `{{mood}}`

### Product variables

- `{{product_shape}}`
- `{{confirmed_color}}`
- `{{material}}`
- `{{visible_components}}`
- `{{variant_attribute}}`
- `{{product_scale}}`

### Copy variables

- `{{target_language}}`
- `{{main_headline}}`
- `{{subtitle}}`
- `{{small_text}}`
- `{{feature_labels}}`
- `{{cta_text}}`

### Constraint variables

- `{{must_keep}}`
- `{{must_not_change}}`
- `{{manual_check_points}}`

## Variable rules

1. Use variables for parts that should change between future images.
2. Keep fixed style rules as normal prompt text.
3. Do not create too many variables; a template with too many placeholders becomes hard to use.
4. Use plain, readable variable names.
5. If a variable is required, list it under Required Inputs.
6. If a variable is optional, list it under Optional Inputs.

## Recommended template format

```text
Template Name: {{template_name}}
Best For: {{use_case}}
Required Inputs: {{required_variables}}
Optional Inputs: {{optional_variables}}
Prompt Template:
{{prompt_template}}
Negative Prompt Template:
{{negative_prompt_template}}
Manual Check:
{{manual_check_points}}
```
