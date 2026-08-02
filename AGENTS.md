# AGENTS.md

## Required Read Order
1. `AI_START_HERE.md`
2. `AI_CURRENT_HANDOFF.md`
3. `README.md` when present
4. exact files named by the owner
5. current branch/PR metadata when active work is referenced

Do not begin broad repository exploration before completing this read order.

## Default Execution Model
- ChatGPT direct GitHub work is the default route for planning, code, content, documentation, branches, commits, pushes, and PR preparation.
- Use one ChatGPT chat for small, scoped, reversible work.
- Use a separate ChatGPT Reviewer chat for production-facing or medium-risk work.
- Use Codex only when a local dev server, browser automation, screenshots, complex testing, broad debugging, or large refactoring is materially required.
- Gemini and other third-party or weak substitute models are not default workflow tools.

## Chat Lifecycle
- One Builder chat normally owns one task and one implementation branch.
- One Reviewer chat normally owns one independent review pass.
- Start a new chat for a new major phase, repository, architecture, or independent review.
- Preserve continuity through `AI_CURRENT_HANDOFF.md`, branch, base SHA, head SHA, and exact files.

## Preview Repository Rules
- Treat this repository as a preview or review surface, not as automatic production truth.
- Do not publish, merge to production, or replace the canonical website repository without explicit owner authorization.
- Preserve Ukrainian/Russian language intent and truthful professional positioning.
- Prefer minimal targeted changes and read current files before editing.

## Git and Review Safety
- Work in a dedicated branch.
- Never modify `main`, merge, publish, roll back, force-push, delete, or perform destructive operations without explicit owner authorization.
- Builder must report base SHA, head SHA, changed files, checks, unverified behavior, and risks.
- Reviewer checks the actual GitHub diff and returns `ACCEPT`, `TARGETED CORRECTION`, or `REJECT`.

## External Model Policy
- Do not route ordinary work to Gemini, OpenCode, Telegram agents, or other third-party models.
- Any exception requires a unique capability reason and explicit owner approval.

## Handoff Maintenance
After meaningful merged work, update `AI_CURRENT_HANDOFF.md`.
