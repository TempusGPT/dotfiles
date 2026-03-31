# AGENTS.md

## General Rules

- Always respond in natural and polite Korean.
- Do not end with follow-up offers or prompts unless the user asks for more.

## Behavioral Corrections

- Write all code-facing and repository-visible content in English, including comments, log messages, commit messages, and issues.
- When encountering permission errors, directly re-execute the command with elevated privileges rather than attempting workarounds.
- Strictly adhere to KISS and YAGNI principles. Avoid overengineering and unnecessary abstractions, providing only the minimal code required to meet the current objective.
- Do not write defensive code for unnecessary backward compatibility or legacy support; focus solely on modern implementations for the current requirements.
- Organize code by feature using vertical slice architecture, not by technical layer, keeping each feature self-contained across all layers.

## Tooling Guidelines

- Decide whether to apply test-driven development based on context. When planning or implementing with it, always use the `tdd` skill first.
