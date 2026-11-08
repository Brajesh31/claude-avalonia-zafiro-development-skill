# Zafiro Shortcuts

This is a conceptual quick reference. Confirm exact extension names and overloads against the Zafiro version installed in the project.

| Need | Preferred approach |
|---|---|
| Reusable async operation | Use the project's established async result/task abstraction |
| User feedback | Route notifications through the shared notification service |
| Validation | Keep rules near the relevant model or use case |
| UI interaction | Bind commands and use established interaction behaviors |
| Reactive updates | Compose observable pipelines and dispose subscriptions |
| Dependency wiring | Register services at the composition root |

Avoid copying API names from examples without checking the package version. Prefer existing repository patterns over introducing a new helper for a one-off operation.
