# Research Decisions Log

Records non-obvious choices with rationale. Append-only; don't rewrite history.

Format: `## YYYY-MM-DD -- <short title>` with **Context**, **Decision**, **Why**.

---

## 2026-04-19 -- Repository restructure to DDD-style layout

**Context**: Flat layout with paper/, outline.md, review.md at root; paper/main.pdf tracked despite gitignore coverage of other artifacts.

**Decision**: Adopt bounded-context layout. outline.md -> planning/drafts/; review.md -> planning/. main.pdf untracked. Skeletons for experiments/ and literature/ added even though the paper is currently a position paper without empirical work.

**Why**: Uniform structure across the paper portfolio; room to grow if empirical work is added later.
