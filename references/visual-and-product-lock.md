# Visual Lock, Product Lock, and Product Variable Lock

Use locks to keep image generation aligned with the reference and user-provided facts.

## Visual Lock

Use for style references, mood boards, scenes, posters, portraits, and non-product images.

Fields:

- subject type
- composition system
- camera angle and focal feel
- lighting system
- background system
- color palette
- material or texture language
- graphic or typographic layout if present
- mood and quality level
- fixed visual rules
- variable fields
- uncertain points

## Product Lock

Use for exact product image reverse prompting.

Fields:

- product category
- product silhouette
- visible product components
- body shape
- surface finish
- color
- material
- component placement
- proportions
- variant-specific details
- visible accessories
- unknown details that need confirmation

Product Lock protects product accuracy. Do not let style rules override confirmed product structure.

## Product Variable Lock

Use when extracting a reusable template from product references but the future product may change.

Fields:

- `{{product_category}}`
- `{{product_shape}}`
- `{{confirmed_color}}`
- `{{material}}`
- `{{visible_components}}`
- `{{variant_attribute}}`
- `{{main_headline}}`
- `{{feature_labels}}`
- `{{format}}`

Product Variable Lock defines which product facts must be supplied later and prevents the template from inventing product structure.

## Lock priority

1. User-confirmed facts
2. Parameter table
3. Clear visual evidence
4. Repeated reference pattern
5. Inference
6. Optional style suggestion

Never put uncertain assumptions into the final prompt as facts.
