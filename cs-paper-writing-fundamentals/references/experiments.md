# Experiments

Experiments exist to test the claims of the paper. Design the section around those claims.

## Structure
1. **Questions**: list what each experiment is meant to answer (e.g., "Does the method scale to 10x more agents?", "Which component accounts for the gain?"). Tie each question to a claim in the introduction.
2. **Setup**: data or instance generation (including seeds and sizes), implementations, parameters, hardware, metrics, and how baselines were obtained and tuned.
3. **Results**: for each question, state it, present the result, then say what to notice.
4. **Analysis**: separate what was observed from what you interpret it to mean. Mark interpretation as such.
5. **Limitations**: conditions where the method fails, is not better, or was not tested.

## Rules
- Reproducibility: someone should be able to rerun the experiment from the description. Report versions, seeds, and any filtering of data or runs.
- Baselines must be meaningful: strong, recent where relevant, and given comparable tuning effort. Include simple baselines and upper/lower bounds where they help interpret scale.
- Report variability: number of runs, ranges, standard deviation or confidence intervals. A mean alone hides noise.
- Distinguish improvement from noise. If differences are small or within variance, say so; use a statistical test only when you can state its assumptions.
- Use metrics that match the claim. If you claim robustness, measure robustness, not only average success.
- Include ablations for each component that the method section says matters.
- Report negative and mixed results. Cherry-picked cases weaken credibility; if you show qualitative examples, say how they were selected.
- Do not tune on the test set. State the split.
- Avoid vague language ("much better", "dramatically"); give the number and the comparison.

## Presentation
- A table when exact values matter; a figure when the shape or trend matters.
- Every table and figure: understandable from its caption, referenced in the text, with the takeaway stated.
- Bold or highlight sparingly; do not bold differences that are within noise.

## Check before finishing
- Does every claim in the abstract and contributions have a corresponding experiment?
- Is there any experiment that answers no stated question? Cut it or add the question.
- If a reviewer asked "what if the baseline were tuned as much as yours?", could you answer?
