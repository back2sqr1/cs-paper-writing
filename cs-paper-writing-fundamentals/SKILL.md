---
name: cs-paper-writing-fundamentals
description: "Write, revise or review computer science and robotics papers: abstract, introduction, related work, method, experiments, conclusion, claims vs evidence, style, math, figures and tables. Use when drafting a section, polishing writing, or self-reviewing before submission."
---

# CS Paper Writing Fundamentals

A working guide, distilled in paraphrase from the principles in Justin Zobel, *Writing for Computer Science* (Springer), plus common reviewer-facing practice. It is not a substitute for the book.

## How to use this skill
1. Identify what the user is editing (a section, a figure, an experiment write-up, or the whole paper).
2. Read **only** the reference file(s) for that target. Do not load them all at once.
3. Rewrite or review following the guide, then return the output in the contract below.

| Target | Read |
|---|---|
| Abstract | `references/abstract.md` |
| Introduction | `references/introduction.md` |
| Related work / background | `references/related-work.md` |
| Method / problem formulation | `references/method.md` |
| Experiments | `references/experiments.md` |
| Conclusion | `references/conclusion.md` |
| Checking claims against evidence | `references/claims-and-evidence.md` |
| Sentence, paragraph, terminology | `references/style.md` |
| Equations, theorems, pseudocode | `references/math-and-algorithms.md` |
| Figures, tables, captions | `references/figures-and-tables.md` |
| Final pass / self-review | `references/revision-checklist.md` |

If a reference file cannot be read, say so and continue using the core principles below rather than inventing its contents.

## Core principles
1. **Start from the research question.** State the question, the hypothesis and the evidence that would confirm or refute it. Order content by logic, not chronology.
2. **Write for the reader.** Define terms before use, one concept per name, intuition before formalism, say what is new early.
3. **Every claim has support.** Proved, experimentally supported, cited, or labeled conjecture. Prefer bounded, numeric statements to adjectives.
4. **One message per paragraph**, stated in the first sentence, with a visible relation between consecutive sentences.
5. **Be honest about limits.** Report negative results and failure cases; do not overclaim.
6. **Treat figures and tables as core content**, understandable from their captions.
7. **Cite fairly**, including competing work, and describe it accurately.

## Workflow
1. Build a mini-outline (3-7 bullets) before drafting prose.
2. Draft or revise paragraph by paragraph.
3. Reverse-outline the section: first sentences should carry the argument.
4. Check claims against evidence.
5. Run the self-review list in `references/revision-checklist.md` before finalizing.

## Output contract
When asked to draft or revise, return:
1. The revised text (with the outline first if drafting).
2. A short list of changes and why.
3. Claims that need evidence, as `Claim: ... | Evidence: ... | Status: supported / needs evidence`.
4. Any unresolved self-review items.
