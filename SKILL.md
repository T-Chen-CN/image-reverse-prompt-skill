---
name: image-reverse-prompt
description: Use this skill when the user provides one or more reference images and asks to analyze them into structured image-generation prompts or reusable prompt templates. Supports single-image analysis, multi-reference style DNA extraction, Visual Lock, Product Lock, variant prompts, and model-specific prompt adaptation.
version: 4.0.0
---

# image-reverse-prompt Skill

Convert reference images into structured, reusable image-generation prompts.

## Modes

1. Single-image reverse prompt mode
2. Multi-reference style template mode
3. Product prompt mode
4. Variant prompt mode

## Core rules

- Analyze visible facts before writing prompts.
- Separate fixed visual rules from variable fields.
- Use Visual Lock for non-product visual references.
- Use Product Lock for product references.
- Use Product Variable Lock when the future product may change.
- User-confirmed facts override image assumptions.
- User-provided product parameters override image assumptions.
- Do not invent product features, logos, certifications, claims, or specifications.
- Keep market, platform, language, and format neutral unless the user specifies them.

## Multi-reference workflow

1. Summarize the reference set.
2. Briefly analyze each image.
3. Extract shared style DNA.
4. Identify fixed visual rules.
5. Identify variable fields.
6. Write a reusable master prompt template.
7. Add specialized templates when useful.
8. Add quality-control notes.

## Standard output

- Task Understanding
- Reference Set Summary
- Per-Image Briefs
- Shared Style DNA
- Fixed Visual Rules
- Variable Fields
- Reusable Master Prompt Template
- Specialized Templates
- Negative Prompt Template
- Quality Control Checklist
- Manual Check Notes
