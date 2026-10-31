---
name: cs-paper-writing-fundamentals
description: Write or revise computer science and robotics papers using the core principles of Zobel's Writing for Computer Science: clarity, claim support, structure, style, math, figures and experiments.
---

# CS Paper Writing Fundamentals

A working guide distilled (in paraphrase) from the principles in Justin Zobel, *Writing for Computer Science* (Springer). Use it when drafting, revising or reviewing a paper section, an abstract, a figure or an experiment write-up.

## 1. Start from the research question
- Before writing, state in one or two sentences: the question, the hypothesis, and the evidence that would confirm or refute it.
- Every section should serve that question. Cut material that does not.
- A paper reports a result, not a diary of what was done. Order content by logic, not by chronology.

## 2. Write for the reader
- Assume an intelligent reader from the general area who has not read your earlier work.
- Define every term and symbol before its first use, and use it the same way afterwards. Never vary terminology for elegance: one concept, one name.
- Give intuition before formalism, and an example before or right after a definition.
- Say what is new and why it matters early; do not make the reader search for the contribution.

## 3. Claims and evidence
- Every claim is either proved, supported by experiments, cited, or explicitly marked as conjecture or opinion.
- Do not overclaim. Prefer precise, bounded statements ("in all 300 instances", "up to 30%") over vague ones ("significantly", "dramatically") unless a statistical test backs them.
- Avoid frequency words ("rarely", "usually", "most") about the world unless you can cite them.
- Report negative or limiting results honestly; they make the positive ones credible.
- Check that the abstract and introduction promise nothing the body does not deliver.

## 4. Structure
- Title: specific and informative, not cute.
- Abstract: problem, approach, key result (with numbers where possible), significance. No citations or undefined symbols.
- Introduction: context, the problem, why existing work falls short, what this paper does, the main results, contributions.
- Background/related work: organized by idea, not by paper; say how each line of work differs from yours.
- Method/formulation: precise enough to reimplement.
- Experiments: questions, setup, results, interpretation, limitations.
- Conclusion: what was shown, what it means, what remains open. Do not merely repeat the abstract.

## 5. Style
- Prefer short, direct sentences and the active voice. Put the important information at the end of the sentence, where it gets emphasis.
- One idea per paragraph; the first sentence states it.
- Use "we" for what the authors do or claim ("We prove..."). Do not use "we" for what a system or robot does, and avoid "we" as a stand-in for general truths.
- Cut filler: "in order to" -> "to"; "it is the case that" -> delete; "very", "quite", "basically" usually go.
- Avoid "obviously", "clearly", "trivially": if it is obvious, the word is unnecessary; if not, it is condescending.
- Avoid ambiguous references: "this", "it" and "they" need a clear antecedent. "This approach" beats "this".
- Be consistent in tense: present for what the paper shows and for general facts; past for what was done in experiments.
- Do not start a sentence with a symbol or a numeral.

## 6. Mathematics and algorithms
- Introduce notation only when it will be reused; keep it minimal and consistent across sections.
- Every displayed equation belongs to a sentence and is punctuated as such.
- State theorems and propositions precisely, with all assumptions; sketch the intuition before the proof.
- Pseudocode: clear inputs and outputs, consistent naming with the text, comments for non-obvious steps, and an explanation in prose of what each part does and why.

## 7. Figures and tables
- Each figure or table must be understandable from its caption alone: say what is shown, the units, and the takeaway.
- Refer to every figure and table in the text, and tell the reader what to notice.
- Prefer simple, minimal-ink tables (no vertical rules; aligned decimals; consistent precision).
- Label axes with quantities and units; make lines distinguishable without color.
- Use a figure when the shape of the data matters, a table when exact values matter.

## 8. Experiments
- State the question each experiment answers before giving results.
- Describe the setup so it can be reproduced: data or instance generation (including seeds), parameters, hardware, implementations.
- Compare against meaningful baselines and bounds, not straw men.
- Report variability (counts, ranges, distributions or confidence intervals), not only means.
- Separate what was observed from how you interpret it; label interpretation as such.
- Distinguish improvement from noise; say when differences are small.

## 9. Citations and ethics
- Cite the original source of an idea, and cite fairly, including work that competes with yours.
- Describe others' work accurately; do not paraphrase it into a weaker version than it is.
- Do not reuse text from your own or others' papers without attribution.
- Disclose limitations, and do not hide results that contradict the story.

## 10. Revision workflow
1. Reverse-outline the draft: list each paragraph's first sentence; check the sequence makes the argument on its own.
2. Check every claim against its evidence (proof, experiment, citation).
3. Check terminology and notation for consistency across the whole paper.
4. Read once purely for cuts: remove anything that does not serve the research question.
5. Read aloud, or read as a skeptical reviewer, and fix every place you hesitate.
6. Check figures, tables and captions last, as a reader skimming the paper would.

## Output when revising
Return: (1) the revised text; (2) a short list of changes and why; (3) any claims that need evidence, flagged as `Claim: ... | Evidence: ... | Status: supported / needs evidence`.
