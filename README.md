# claude-avalonia-zafiro-development-skill

A Claude Code skill for developing cross-platform Avalonia applications with Zafiro conventions and a functional-reactive MVVM architecture.

## Overview

This skill defines practical development rules for Avalonia UI projects using Zafiro, ReactiveUI, and DynamicData patterns. It focuses on maintainability, predictable state, reusable composition, and separation between application logic and visual presentation.

## Core Principles

- Functional-reactive MVVM.
- Explicit error handling and predictable results.
- Cross-platform ViewModels.
- Composition over inheritance.
- Reuse of established Zafiro abstractions.
- Consistent naming and coding standards.
- Reactive data pipelines with clear ownership.

## Main Capabilities

- Organize Avalonia application architecture.
- Build reactive ViewModels.
- Manage DynamicData collections.
- Compose Views and ViewModels.
- Apply naming and coding conventions.
- Use result-based error handling.
- Implement reusable UI patterns.
- Review application structure for maintainability.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-avalonia-zafiro-development-skill.git ~/.claude/skills/avalonia-zafiro-development
```

## Usage

Invoke the skill when developing or refactoring an Avalonia application:

```text
/avalonia-zafiro-development
```

Provide the .NET and Avalonia versions, relevant packages, application structure, and intended behavior.

## Reference Guide

| File | Focus |
|---|---|
| `core-technical-skills.md` | Core architecture and implementation principles |
| `naming-standards.md` | Naming and coding conventions |
| `avalonia-reactive-rules.md` | Avalonia, Zafiro, and reactive patterns |
| `zafiro-shortcuts.md` | Common Zafiro and reactive operations |
| `patterns.md` | Reusable implementation patterns |

## Recommended Workflow

1. Inspect the project and existing conventions.
2. Search for existing helpers and patterns before adding new code.
3. Define the responsibility of the ViewModel or component.
4. Keep ViewModels independent of concrete UI elements.
5. Use reactive pipelines deliberately.
6. Represent expected failures explicitly.
7. Compose Views and ViewModels through the established application structure.
8. Add tests for business logic and state transitions.
9. Verify the behavior in the target desktop environment.

## Quality Checklist

- ViewModels remain testable and UI-independent.
- Reactive subscriptions have clear lifetimes.
- Collections are updated through predictable pipelines.
- Errors are handled explicitly.
- Naming follows project conventions.
- Existing Zafiro abstractions are reused appropriately.
- Composition and dependency injection remain clear.
- Cross-platform behavior is considered.

## Repository Contents

- `SKILL.md`: Main development rules and workflow.
- `references/`: Core skills, naming, reactive rules, shortcuts, and patterns.
- `README.md`: Installation and implementation guidance.

## Practical Principle

Do not fight the framework or duplicate its abstractions. Follow the project's established composition and reactive patterns, and introduce new helpers only when they remove meaningful duplication.
