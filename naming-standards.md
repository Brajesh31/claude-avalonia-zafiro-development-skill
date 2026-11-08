# Naming and Coding Standards

Use names that communicate domain intent and remain consistent across the solution.

## Naming
- Types and public members: PascalCase.
- Private fields: follow the repository's established convention consistently.
- Interfaces: use the project's convention; avoid adding prefixes inconsistently.
- Async methods: use an Async suffix when it improves clarity and matches local conventions.
- Booleans: phrase as meaningful predicates, such as `IsEnabled` or `HasChanges`.

## Code quality
Prefer small methods, explicit error handling, and immutable values where practical. Avoid abbreviations unless they are established domain terms. Keep comments focused on why, not restating what the code already says.
