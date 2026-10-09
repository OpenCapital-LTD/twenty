# OBJECTIVE — twenty (LOCAL REFERENCE ONLY)
<!-- Magic Quadrant = sprint_plan.md + todo.md + lessons.md + OBJECTIVE.md. This copy is a local, reference-only Quadrant for an
     external-owned clone. It is NOT to be pushed to the upstream/vendor remote. No OCA roadmap is asserted here. -->
**Status:** REFERENCE (no build objective) · **Classification (2026-10-01 audit):** external-owned clone — https://github.com/OpenCapital-LTD/twenty.git

## 1. The Objective (one sentence)
> Reference copy of an open-source CRM that OCA looked at; nothing in the repo says what OCA wants from it.

**7-year-old test:** not applicable — nothing is being built.

## 2. Why
- Observed role: Local clone of OpenCapital-LTD/twenty, a GitHub fork of twentyhq/twenty (open-source CRM). Last commit 2025-09-01 by an upstream author; 7,806 commits; no OCA commits observed; upstream ships its own CLAUDE.md.
- Sponsor: none — OCA does not own the remote; no OCA purpose is evidenced in the tree.

## 3. Who it is for
| User | What they need from it | How often |
|---|---|---|
| OCA engineers | a local read-only reference | when a question about the upstream arises |

## 4. The How
- `git fetch` to refresh; read; never commit or push from this clone.

## 5. What DONE looks like
| # | Done-when | How we prove it | Target date |
|---|---|---|---|
| 1 | Clone stays read-only: no local commits ahead of upstream | `git status`/`git log origin/HEAD..HEAD` empty | standing |

## 6–9. Milestones · Risks · Limitations · Non-goals
- Milestones: none (reference). Risk: someone mistakes this clone for an OCA project and plans work here. Limitation: no OCA changes. Non-goal: any roadmap.

## 10. Data & evidence sources
- README.md, `git remote -v`, `git log -1` at audit: `main` @ `2af611e938864ab3ae6d2d22729c8b434937fdb6` · 2025-09-01 Thomas Trompette

## 11–12. Dependencies · Cost
- None. Budget: none.

## 13. Local sources read
- README.md (title/purpose lines), git metadata. No other file opened.

---
*Document control:* v0.1 REFERENCE · 2026-10-01 · author Vincent Wachira · prepared by W2 (assignment 14B).
