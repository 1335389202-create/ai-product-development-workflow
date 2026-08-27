# Changelog

All notable changes to this repository are documented in this file.

## [1.1.0] — Unreleased

### Changed

- **6 Core Stages** — Lifecycle reorganized from 16 operational stages to Discover / Define / Design / Build / Validate / Release &amp; Learn with each stage framed by one core question. Detailed operational steps preserved as the Playbook.
- **4 Human Gates** — Scope, Design, Build, and Release Gates repositioned as explicit decision points between stages. Lite depth permits G1+G2 and G3+G4 joint approval; no gate is delete-able.
- **Progressive Disclosure** — README restructured into Layer 1 (overview + at-a-glance), Layer 2 (per-stage goal / activities / outputs / gate), and Layer 3 (detailed playbook + preserved controls).
- **Risk-driven Workflow Depth** — Depth is selected by reversibility, existing users, data impact, and production risk — not by project size. Lite / Standard / Extended replace the prior implicit "run everything" model.
- **Detailed Steps → Playbook** — Former first-class operational stages (Requirement Clarification, Benchmark, PRD, UX, Prototype Spec, Prototype Validation, Scope Freeze, Implementation Planning, Implementation, QA, RC, CI/CD, Production Smoke, Release, Retrospective) are now mapped under the 6 Core Stages as execution-reference material.
- **Extended Controls** — Migration/backup/rollback, production protection, and safety-copy rules (previously presented as universal) are now gated behind explicit Extended Controls triggered only when the matching risk exists.

### Added

- **AI Stage Contract** — Six-field, Agent-agnostic contract template (Context / Goal / Inputs / Allowed &amp; Forbidden / Exit Criteria / Stop &amp; Report) for handing any stage to Codex, Trae, Cursor, Claude, or equivalent.
- **Lite / Standard / Extended depth matrix** — Three-tier depth model with use-case table, upgrade factors, downgrade-rationalization requirement, and real-world depth example via What-to-Eat V1.0 (Standard) vs V2.0 (Extended).

### Preserved

- **Evidence Model** — Full 7-type evidence table retained in detailed section; three-sentence Engineering ≠ User ≠ Business Value boundary promoted to Layer 1.
- **Stop Conditions** — Full 10-condition Stop &amp; Report list preserved in detailed section; not reduced.
- **Scope Freeze** — Frozen-scope reopen rules preserved; new rules and non-scope-change bypasses explicitly excluded.
- **Change Propagation** — Rule plus PRD→Design→Prototype→Impl→Tests→README impact chain preserved; abridged matrix removed but rule + judgment requirement intact.
- **Test Gates** — Prototype / Production / Release distinctions preserved implicitly through Build and Validate stages.
- **Version Management** — Workflow Version / Product Version / Git Release Tag three-namespace separation preserved and clarified.
- **Human Release Authority** — G4 Release Gate retains explicit human-authorization requirement; auto-release forbidden.

## [1.0.0] - 2026-08-27

### Added

- Initial independent release of the AI Product Development Workflow.
- Complete artifact-driven lifecycle from idea through production and retrospective.
- Human Decision Gate, Scope Freeze, Test Gate, Stop Conditions, and Change Propagation protocols.
- Engineering Evidence vs Product Evidence boundary.
- Real-world What to Eat V2.0 case study.
- Independent workflow versioning strategy.
