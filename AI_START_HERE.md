# AI Start Here — Alina Horb Preview

## Purpose
Deterministic entrypoint for a fresh session working on `proaiexpert/alina-horb-preview`.

## Required First Actions
1. Fetch current `main` and record SHA.
2. Read `AGENTS.md`.
3. Read `AI_CURRENT_HANDOFF.md`.
4. Read `README.md` when present.
5. Read only task-specific files named by the owner.

## Role Selection
- Strategy or preview planning → `Control`.
- Preview implementation → `Builder`.
- Audit or comparison → `Reviewer`.
- Merge/publication → `Publisher`, only when explicitly authorized.
- Ambiguous request → `Control`, read-only.

## Preview Boundary
- This repository is a preview/review surface, not automatic production truth.
- Do not replace or publish to the canonical Alina Horb website without explicit owner authorization.
- Preserve truthful professional positioning and language intent.

## Risk Routing
- Tier 1: one ChatGPT chat for small scoped work.
- Tier 2: separate Builder and Reviewer chats for production-facing or medium-risk work.
- Tier 3: Codex only when local runtime, browser automation, screenshots, complex testing, broad debugging, or a large refactor is materially required.

## First Response Contract
Report repository, role, risk tier, main SHA, files read, current state, task interpretation, branch, permissions, blockers, and next action before editing.

## Handoff Rule
After meaningful merged work, update `AI_CURRENT_HANDOFF.md`.
