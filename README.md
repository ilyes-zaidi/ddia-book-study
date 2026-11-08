# Designing Data-Intensive Applications — Study Workspace

Personal study of **Designing Data-Intensive Applications, second edition (2026)**, by Martin Kleppmann and Chris Riccomini.

The goal is to understand mechanisms, reason about trade-offs, and demonstrate concepts through experiments. Reading progress alone does not establish understanding.

## Our study agreement

1. Read a manageable section, then close the book.
2. Explain the idea in your own words before receiving an explanation from the assistant.
3. Work through questions one at a time: explain the mechanism, apply it to a scenario, then stress the reasoning with a failure or changed requirement.
4. Commit to an answer and explain why. Correct terminology alone is insufficient.
5. When an answer has a gap, the assistant probes it and gives progressively stronger hints before supplying an explanation.
6. Preserve the learning: **initial answer → correction → conclusion**. Keep uncertainties visible.
7. Use a small experiment when it would clarify the mechanism. Record a prediction, steps, observations, and explanation.
8. Revisit concepts in later sessions to check retention and transfer to new scenarios.

The assistant is a study partner who challenges reasoning, reviews notes, and helps build demonstrations. Notes should reflect the learner's understanding; generated summaries must not stand in for demonstrated understanding. Direct requests for an explanation are always welcome.

## Layout

```text
AGENTS.md                         Instructions for future AI assistants
STUDY_STATE.md                     Current position and session handoff
chapters/01-trade-offs/notes.md    Learner's explanations and conclusions
chapters/01-trade-offs/review.md   Questions, attempts, feedback, and revisits
cheatsheets/                      Short references distilled after study
labs/                            Focused, reproducible experiments
projects/                        Exercises combining several concepts
templates/                       Reusable chapter and lab templates
resources.md                     References and why they are useful
```

Create later chapter folders as they become useful. Keep chapter materials aligned with this edition's numbering.

## Continuing a session

Read `AGENTS.md` and `STUDY_STATE.md`, then the relevant chapter notes and review entries. Resume from the recorded next step. If reading has happened outside this repository, ask which section was completed before starting questions.

At the end of meaningful study work, update the state with what was covered, evidence of understanding, unresolved gaps, and the next action. Do not infer mastery or reading completion from an assistant explanation.

## Book and Git

The local PDF is reference material and is excluded from Git. Commit original notes, code, and small useful results. Link to sources and cite chapter/section references rather than copying substantial book text. Label printed page numbers separately from PDF page numbers when using either.

The initial materials are scaffolding, not completed study notes. Start with Chapter 1, **Trade-Offs in Data Systems Architecture**.
