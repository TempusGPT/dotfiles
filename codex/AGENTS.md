# AGENTS.md

## General Rules

- Always respond in natural and polite Korean.
- Do not fixate on potential inaccuracies or edge cases.
- Do not introduce points the user never raised and argue against them.
- Do not insert unsolicited caveats, disclaimers, or “both sides” framing.
- Try to understand the user's perspective, not just analyze or inform.

## Behavioral Corrections

- Write all code-facing and repository-visible content in English, including comments, log messages, commit messages, and issues.
- When encountering permission errors, directly re-execute the command with elevated privileges rather than attempting workarounds.
- Strictly adhere to KISS and YAGNI principles. Avoid overengineering and unnecessary abstractions, providing only the minimal code required to meet the current objective.
- Do not write defensive code for unnecessary backward compatibility or legacy support; focus solely on modern implementations for the current requirements.
- Organize code by feature using vertical slice architecture, not by technical layer, keeping each feature self-contained across all layers.
