# eXAVERO — Intelligent Exam Management

> **Graduation project · In development · Public case study (no source code)**

**eXAVERO** explores a more traceable workflow for university **written examinations**, connecting exam preparation and secure paper identification with a future human-supervised assessment workflow.

This is a **showcase of the project concept and documented architecture**, not a public software release or a claim that every planned feature is complete.

## The problem

Paper-based essay exams involve multiple stages — preparing the exam, generating answer booklets, collecting and identifying papers, and evaluating written answers. Disconnected workflows can make tracing an individual paper and reviewing decisions harder.

## Product direction

1. **Exam preparation:** structure exam forms, questions, parts, model answers and marking rubrics.
2. **Paper identity:** use sheet identifiers and per-page QR verification to connect printed pages to their intended records.
3. **Print workflows:** generate booklet templates and track print batches.
4. **Assessment roadmap:** explore scanning and AI-assisted support for written-answer marking **with mandatory human review and sign-off**.

**Current focus:** exam preparation and print-ready outputs. Scanning, automated handwriting processing and AI-assisted marking are planned later phases, not features presented here as finished.

## High-level architecture

| Layer | Technology / approach |
|---|---|
| API | Python, FastAPI |
| Web app | React, TypeScript, Vite |
| Database | PostgreSQL |
| Job processing | Redis / worker |
| Development environment | Docker Compose |
| Integration | Contract-first APIs and JSON schemas |

## My role

**Ahmed Abdelkhaleq — Team Lead / Architecture.** The internal team ownership document assigns this role responsibility for system integration, core infrastructure, authentication and audit boundaries, API contracts, design tokens, code review and coordination. This describes **assigned scope**, not individual authorship of all project code.

## Engineering considerations

- Versioned contracts across backend, frontend and print-rendering workflows
- Stable identifiers and QR verification for paper traceability
- Defined boundaries between automated assistance and final human decisions
- Test fixtures and reproducible environments for development

## Visibility and status

The implementation repository is **private** while the graduation team develops and reviews the system. No source code, live credentials, institution data or actual exam papers are published in this showcase.

**Status:** Work in progress · October 2026

## Explore

- [Ahmed's GitHub profile](../../README.md)
- [Design & software portfolio](https://portfolio.ajcore.net/ar)

---
*This case study will be expanded with approved screenshots, verified demonstrations and measured results as the project progresses.*
