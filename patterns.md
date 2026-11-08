# Common Zafiro and Reactive Patterns

## Refreshable collections
Model refresh as an explicit operation with loading, success, and error states. Prevent overlapping refreshes when unsafe, preserve useful existing data during refresh where appropriate, and support cancellation.

## Validation
Keep validation deterministic and testable. Return actionable validation results rather than throwing exceptions for expected invalid user input. Revalidate when dependent values change.

## Async commands
Disable unsafe duplicate execution, propagate cancellation, and surface errors through a shared presentation mechanism. Do not block the UI thread.

## Mapping
Map between domain and presentation models at clear boundaries. Avoid leaking persistence-specific types into the View.

## Subscription ownership
Every subscription must have an owner and a disposal point. Prefer scoped subscriptions tied to a ViewModel or service lifetime.

## Testing
Cover initial state, successful updates, validation failures, cancellation, disposal, and concurrent refresh attempts.
