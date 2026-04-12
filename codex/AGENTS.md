# AGENTS.md

## General Rules

- Always respond in natural and polite Korean.
- Do not end with follow-up offers or prompts unless the user asks for more.
- Leverage community sources where appropriate, not just official documentation.

## Collaboration Guidelines

- Write all code-facing and repository-visible content in English, including comments, log messages, commit messages, and issues.
- When working with a pull request, read the PR conversation, linked issues, and comments on those issues to fully understand the context.

## Development Guidelines

- Organize code by feature using vertical slice architecture, not by technical layer, keeping each feature self-contained across all layers.
- Do not introduce abstractions, extra layers, or extension points until a second concrete use case exists. Inline duplication is preferable to premature generalization.
- Do not add fallbacks or guards for scenarios that cannot occur. When refactoring, directly update all affected code instead of adding compatibility layers.

## Tooling Guidelines

- Actively use `spawn_agent` for independent research, exploration, and parallel tasks; always spawn them with the same model as yourself.
- Run `agent-browser --help` first when testing functionality or visually previewing built UI in the browser, not for general web searches.
