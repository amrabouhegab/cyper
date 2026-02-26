<!-- 
Sync Impact Report:
- Version change: Initial → 1.0.0
- List of modified principles: Initial template placeholders replaced with project-specific principles.
- Added sections: Code Quality, Testing, UX, Performance, Documentation.
- Removed sections: N/A
- Templates requiring updates: 
  - ✅ .specify/templates/plan-template.md
  - ✅ .specify/templates/spec-template.md
  - ✅ .specify/templates/tasks-template.md
- Follow-up TODOs: None.
-->

# Cyper Constitution

## Core Principles

### I. Code Quality & Technical Integrity
Every feature MUST adhere to the established architectural patterns (Angular standalone components, signal-based state management). Code MUST be readable, idiomatic, and free of redundant logic. Structural integrity and maintainability are prioritized over speed of delivery.

### II. Rigorous Testing Standards
Automated testing is non-negotiable. Every bug fix MUST be preceded by a reproduction test case. Every new feature MUST include unit and/or integration tests verifying behavioral correctness. Tests MUST be run and pass before any change is considered complete.

### III. User Experience & Design Consistency
Interfaces MUST be production-grade, visually polished, and responsive. Styling SHOULD prefer Vanilla CSS for flexibility. Components MUST provide interactive feedback and maintain a consistent aesthetic across the application.

### IV. Performance & Resource Efficiency
Applications MUST be optimized for speed and responsiveness. This includes efficient change detection (OnPush), lazy loading of routes, and minimizing bundle sizes. Performance impacts MUST be considered for every architectural decision.

### V. Documentation & Clarity
Code MUST be self-documenting where possible, with clear naming and structure. Complex logic or non-obvious architectural decisions MUST be explained in comments or README files.

## Technology Stack & Standards
The project uses Angular (v20+) with TypeScript. Styling is handled via SCSS/Vanilla CSS. State management leverages Angular Signals. SSR and Hydration are enabled by default for optimal performance and SEO.

## Development Workflow
Development follows a Research-Strategy-Execution lifecycle. Validation is mandatory through testing, linting, and type-checking. All changes must be verified in the full project context before finality.

## Governance
This constitution supersedes all other informal practices. Amendments require a version bump and updated documentation. Compliance is verified during code reviews and automated CI gates.

**Version**: 1.0.0 | **Ratified**: 2026-02-26 | **Last Amended**: 2026-02-26
