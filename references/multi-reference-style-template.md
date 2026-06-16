# Multi-Reference Style Template Mode

Use this mode when the user provides multiple reference images and wants a reusable prompt template rather than a prompt for each image.

## Goal

Extract the visual system behind the reference set:

- shared composition logic
- recurring lighting pattern
- background system
- color relationship
- subject treatment
- copy or graphic hierarchy if present
- mood and commercial intent
- reusable variables

## Process

1. Count and classify the references.
2. Briefly summarize each reference.
3. Identify repeated visual patterns.
4. Separate fixed visual rules from optional accents.
5. Define variable fields for future reuse.
6. Write a master prompt template.
7. Add specialized templates only when useful.
8. Add manual check notes.

## Shared Style DNA fields

- Composition
- Camera
- Lighting
- Background
- Color palette
- Material and texture language
- Typography or graphic layout
- Mood
- Commercial or creative intent

## Fixed visual rules

Fixed rules should be stable across future generations. Examples:

- product or subject remains the visual focus
- background stays low-noise
- lighting stays controlled and intentional
- text hierarchy stays short and readable
- product structure is not redesigned

## Variable fields

Variables are parts that can change for future usage:

- `{{subject}}`
- `{{product_name}}`
- `{{product_shape}}`
- `{{confirmed_color}}`
- `{{background_style}}`
- `{{main_headline}}`
- `{{feature_labels}}`
- `{{format}}`

## Master template requirement

The final master template must be reusable. It should not depend on any one reference image unless the user marks a primary reference.
