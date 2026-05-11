# GoodVibeDevelopment — Centralized Dev Planning Workflow

This document details the authoritative approach to planning all Software Development projects
under the GoodVibeDevelopment (GVD) platform.

## Workspace Structure

```
/ (Workspace Root)
├── src/                          # Source code for all packages
└── .dev/                         # Centralized Planning (Source of Truth)
    ├── ROADMAP.md                # High-level release list of major features
    ├── planning/
    │   ├── EXECUTION_PLAN.md     # THE source of truth. All workstreams, deps, status
    │   ├── SPEC_INDEX.md         # Index of all specs with status across all packages
    │   └── specs/                # Workspace-local specs
    └── research/
        ├── RESEARCH_INDEX.md     # Summary of all research topics + decisions
        └── <topic>/
            └── findings.md       # Detailed research findings
```

## Workflow Phases

### Phase 1: Research

Understand the problem space, existing code, and available options before committing to a design.

### Phase 2: Planning

Define workstreams, dependencies, estimates, and parallelization waves.

### Phase 3: Spec Building

Turn each workstream into a self-contained spec that any agent can implement without guessing.

### Phase 4: Implementation

Execute specs in dependency order, validating each workstream before moving to the next.
