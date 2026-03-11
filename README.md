# Agentic Flutter Client

## Purpose

This starter provides the Flutter client foundation for Agentic platform projects.

It is intended for multi-platform client development across mobile, web, and desktop, while remaining modular and independent from backend and runtime composition details.

---

## Install target

This starter installs into:

app/client

---

## Included

- Flutter client foundation
- Multi-platform project bootstrap
- Base structure for Flutter UI development
- Deterministic client-side project organization

---

## Not included

This starter intentionally does not include:

- Business-specific screens
- Authentication flows
- API integration implementation details
- Observability tooling
- Production store/deployment configuration

Those concerns are handled by other starters or feature modules.

---

## Prerequisites

Typical runtime prerequisites:

- Flutter SDK
- Dart SDK
- Platform toolchains as needed
- Optional Docker runtime for integration scenarios

---

## Expected structure after installation

app/client

---

## Installation

1. Create a project using AGENTIC-TEMPLATE.
2. Install this starter into:

app/client

3. Install Flutter dependencies.
4. Run validation checks.

---

## Post-install validation

Verify that:

- Flutter dependencies install successfully
- flutter analyze runs
- flutter test runs
- flutter build or run command is valid

---

## Compatibility

Compatible with:

- agentic-clean-backend
- agentic-api-contracts-api
- agentic-fullstack-composition

---

## Exit criteria

Installation is successful when:

- app/client exists
- Flutter dependencies install successfully
- flutter analyze runs
- flutter test runs
- no unresolved placeholders remain

---

## Notes

This starter is intentionally minimal.

Screens, navigation, state management, and integration with backend contracts should be extended through project-specific features.
