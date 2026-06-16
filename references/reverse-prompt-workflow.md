# Reverse Prompt Workflow

This workflow applies to both single-image and multi-reference tasks.

## Single-image workflow

1. Identify the task type.
2. Analyze visible facts.
3. Separate facts from assumptions.
4. Create Visual Lock or Product Lock.
5. Write a Universal Prompt.
6. Add model-specific versions if needed.
7. Add a negative prompt.
8. Add manual check notes.

## Multi-reference workflow

1. Identify that the task is template extraction.
2. Analyze each reference briefly.
3. Identify recurring visual patterns.
4. Separate fixed visual rules from variable fields.
5. Create a master template prompt.
6. Add specialized templates if the user has a known use case.
7. Add quality-control notes.

## Decision rules

Use single-image workflow when:

- one reference image is provided
- the user wants a prompt for that exact image style
- the user asks for one final prompt

Use multi-reference workflow when:

- multiple references are provided
- the user asks for shared style, style DNA, common template, style board, or reusable prompt framework
- the final output should work with future products, subjects, or scenes

## Evidence weighting

- elements repeated across most references are strong style rules
- elements repeated in some references are optional accents
- elements appearing once are unique details unless the user says that image is primary
- user-provided parameters override image inference
- user-confirmed colors override image color estimation

## Avoid overfitting

A reusable template should describe the logic that makes the reference set coherent rather than every reference-specific object.
