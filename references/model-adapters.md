# Model Adapters

Use model adapters only when the user asks for a target image-generation model or when the output would benefit from a dedicated version.

## Universal prompt

Use natural language, clear visual hierarchy, and complete constraints. This is the safest default.

## GPT Image / natural-language image models

- Write complete sentences.
- Emphasize what must stay accurate.
- Put product or subject constraints before style flourishes.
- State text requirements clearly if text is needed.

## Midjourney-style prompt

- Use compact visual language.
- Emphasize composition, lighting, mood, and material.
- Keep variables readable.
- Avoid overloading the prompt with unsupported details.

## SDXL / FLUX-style prompt

- Use structured keywords plus natural phrases.
- Put subject and product accuracy first.
- Add lighting, camera, background, and quality terms after the subject.
- Keep negative prompt targeted to likely failure points.

## Adapter priority

1. Preserve user-confirmed facts.
2. Preserve Product Lock or Visual Lock.
3. Preserve the shared style DNA.
4. Then adapt syntax to the target model.
