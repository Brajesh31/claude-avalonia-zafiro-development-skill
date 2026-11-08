# Avalonia, Zafiro, and Reactive Rules

## UI boundaries
Keep visual concerns in Views and presentation state in ViewModels. Use the application's established Zafiro and Avalonia patterns rather than introducing competing abstractions.

## Reactive pipelines
- Keep observable pipelines understandable and composed from small operators.
- Define subscription lifetime and dispose subscriptions.
- Avoid unbounded subscriptions from transient views.
- Use explicit scheduling when crossing UI and background threads.
- Handle errors in the pipeline; an unhandled stream error can terminate downstream observers.

## DynamicData
Apply filtering, sorting, and transformation close to the source when practical. Dispose change-set subscriptions and avoid repeatedly materializing large collections without need.

## Validation
Test empty streams, errors, rapid updates, cancellation, and view disposal. Never update UI-bound state from an arbitrary worker thread without the required dispatcher/scheduler.
