# Whetstone

Research Program: 6 (Analogy / theory layer)
Status: Concept note
Relationship to other work: Companion to [pythia](https://github.com/heznpc/pythia) and [analogic-appropriation](https://github.com/heznpc/analogic-appropriation) — Program 6 papers that work through metaphor as theoretical scaffolding.

This is a concept note, not a finished paper.

**The Whetstone Paradox: Why AI Demands More Education Science, Not Less**

## Thesis

AI transforms *what* and *how* education delivers, but not *why* education is necessary. Two dominant responses — that education is obsolete (the *obsolescence thesis*) or that it must retool itself for AI-era workforce needs (the *retooling thesis*) — both misidentify the problem. The retooling thesis is self-defeating: the firm-as-destination that workforce-preparation models train toward is itself dissolving under AI-driven disaggregation.

The whetstone thesis is the third position. A whetstone sharpens a blade through controlled friction. Remove all friction and the blade dulls; apply friction carelessly and the blade chips. AI removes friction indiscriminately. Education science is the discipline that knows *which friction sharpens and which friction merely damages* — and that knowledge becomes more necessary, not less, as AI advances.

## Structure

1. **The Case for Change** — Institutional consensus on inadequacy (OECD, UNESCO, WEF), dissolution of the firm (Coase → AI), the self-defeating workforce-preparation model
2. **Assessment Crisis** — GPA–innovation inverse correlation (Mayhew 2012), 2e students, credentialism's hollow promise
3. **Invariant Functions** — Socialization (Durkheim), productive friction (Bjork), delegation feedback loop, Matthew Effect
4. **The Whetstone Thesis** — Taxonomy of productive vs unproductive friction, structured autonomy as design principle

## Repository layout

```
paper/                 manuscript source of truth
  main.tex
  references.bib
  figures/
experiments/           skeleton (no empirical work in v1)
literature/            reading notes, gap analysis
planning/              review.md, decisions.md, drafts/
```

`paper/main.tex` is the single source of truth. Venue adaptations go in `submissions/<venue>/`.

## Currently implemented

- Full 285-line LaTeX manuscript (`paper/main.tex`) with 446-line references.bib integrating OECD/UNESCO/WEF reports, Coase 1937, Durkheim, Bjork's desirable difficulties, and 2026 empirical anchors (86% of student AI use undetected by instructors, 67% decline in entry-level developer job postings 2022–2026, solo-founder share of new startups rising from 23.7% to 36.3%).
- Internal review notes (`planning/review.md`) with self-assessment and venue-fit analysis.

## Planned

- Productive-friction taxonomy as a one-page formal matrix.
- One first-person case study (e.g. General Assembly / App Academy bootcamp closures) to anchor the secondary citations.
- Operational definition of *structured autonomy* with 2–3 worked examples.
- Internal review by a second reader before submission.

## Design intent

- **Position paper, deliberately.** The contribution is conceptual reframing, not new empirical data. The taxonomy and the whetstone metaphor are intended as citable infrastructure for downstream empirical work — not as a replacement for it.
- **DDD-style layout** (paper / experiments / literature / planning) is shared across the paper portfolio so that a position paper and an empirical paper share the same skeleton — room to grow if experiments are added later.
- **Program 6 placement.** Whetstone sits alongside pythia and analogic-appropriation as a metaphor-driven theory paper: the central move is naming a distinction (productive vs unproductive friction) and giving it a memorable handle, not running a study.

## Non-goals

- Curriculum prescriptions, edtech product recommendations, or AI-in-the-classroom how-to guidance.
- Empirical study of AI use in any single institution — the empirical anchors are secondary citations and the paper says so.
- Defending or attacking any specific AI tool or vendor.

## Redacted

None — this paper has no external persons, accounts, or internal cases to redact.
