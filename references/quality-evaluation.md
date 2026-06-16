# Quality Evaluation

Use this checklist before returning output.

## Single-image reverse prompting

- The prompt reflects visible facts.
- The subject or product structure is preserved.
- Color and material are not guessed beyond evidence.
- Uncertain details are outside the final prompt.
- The final prompt is usable without extra explanation.
- The negative prompt targets likely failure points.

## Multi-reference style template extraction

- Each reference was considered.
- Shared patterns were distinguished from one-off details.
- Fixed visual rules are clear.
- Variable fields are reusable.
- The master template does not overfit a single reference.
- Specialized templates are only included when useful.
- The final template can accept a new subject or product.

## Product and variant work

- User parameters override image assumptions.
- Confirmed colors are used consistently.
- Product structure is not redesigned.
- Variant prompts change only the confirmed variant attribute.
- Copy does not include unsupported claims.

## Warning signs

Revise if output contains:

- vague style words without structure
- missing variables in a reusable template
- product features not provided by the user
- mixed visual systems with no explanation
- uncertain text treated as fact
- model-specific parameters added without user need
