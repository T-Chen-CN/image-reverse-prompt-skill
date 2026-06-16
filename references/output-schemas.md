# Output Schemas

Use these schemas as structure references. Do not force JSON unless the user asks for JSON.

## Single-image output

Fields:

- task_type
- image_type
- visual_analysis
- visual_lock_or_product_lock
- universal_prompt
- model_specific_prompts
- negative_prompt
- uncertain_points
- manual_check_notes

## Multi-reference template output

Fields:

- task_type
- reference_set_summary
- per_image_briefs
- shared_style_dna
- fixed_visual_rules
- variable_fields
- master_prompt_template
- specialized_templates
- negative_prompt_template
- quality_control_checklist
- manual_check_notes

## Product template output

Fields:

- set_name
- style_dna_summary
- product_variable_lock
- shared_negative_prompt
- templates
- manual_check_notes

## Variant prompt output

Fields:

- template_set_name
- shared_structure_lock
- shared_camera_lighting_background
- variant_variables
- prompt_template
- negative_prompt_template
- manual_check_points

## Copyable template block

Template Name: {{template_name}}
Best For: {{use_case}}
Required Inputs: {{required_inputs}}
Optional Inputs: {{optional_inputs}}
Prompt Template: {{prompt_template}}
Negative Prompt Template: {{negative_prompt_template}}
Manual Check: {{manual_check_points}}
