# GVD Workspace Template

This is the GVD workspace template; Jarvis will customize it on clone.

## About

This repository serves as the canonical template for new workspaces managed by the
GoodVibeDevelopment (GVD) platform. When you onboard a project with GVD, this template
provides the initial `.dev/` planning structure and `.kiro/steering/` files.

## Structure

```
.dev/                    — Centralized planning (gitignored in your project)
  ROADMAP.md             — High-level feature roadmap
  planning/
    EXECUTION_PLAN.md    — Authoritative workstream tracker
    SPEC_INDEX.md        — Quick-reference status board
    specs/               — Individual spec folders
  research/
    RESEARCH_INDEX.md    — Research topics and decisions
.kiro/
  steering/
    CONTEXT.md           — Project identity and context (customized by Jarvis)
    DEVELOPMENT.md       — Development workflow reference
```

## Usage

This template is used automatically by `gvd workspaces onboard <repo-url>`.
You do not need to clone this repo manually.
