# LedgerFlow AI Engineering Rules

## Goal

Write production-quality Spring Boot code while teaching the underlying framework concepts.

## Before Writing Code

Always:

1. Explain the Spring concept involved.
2. Explain the design decision.
3. Keep changes focused.
4. Update tests.
5. Update documentation when needed.

## Architecture

- Prefer feature-based packaging.
- Do not create packages before they are needed.
- Avoid placeholder classes.
- Do not introduce unnecessary abstractions.

## Java

Prefer:

- Constructor injection
- Immutable DTOs
- Meaningful names
- Small classes
- Small methods

Avoid:

- Field injection
- Static mutable state
- Business logic inside controllers
- Magic strings

## Spring

Use:

- @Service
- @Repository
- @Configuration
- @ConfigurationProperties

Explain every new annotation introduced.

## Testing

Every new feature should include tests whenever appropriate.

## Git

Use Conventional Commits.

Examples:

- feat:
- fix:
- docs:
- test:
- refactor:
- build:
- ci:
- chore:

## AI Constraints

Never:

- Rewrite unrelated files
- Rename packages without approval
- Introduce dependencies without justification
- Generate large features in one step

Prefer incremental development.
