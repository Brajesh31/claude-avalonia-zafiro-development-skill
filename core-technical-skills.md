# Core Technical Skills and Architecture

## Engineering principles
- Separate UI, application, domain, and infrastructure responsibilities.
- Prefer explicit dependencies and small cohesive modules.
- Keep business rules independent of Avalonia controls.
- Use asynchronous I/O and cancellation for long-running operations.
- Make errors observable and recoverable.

## Quality
Use nullable reference types, analyzers, consistent formatting, and automated tests. Validate inputs at boundaries. Avoid abstractions that obscure straightforward behavior.

## Delivery
Build and test in CI, keep configuration environment-specific, protect secrets, and document how to run and package the application.
