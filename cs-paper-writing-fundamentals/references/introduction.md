# Introduction

The introduction answers, in order: what is the problem, why does it matter, why is it unsolved, what did you do, and what did you find.

## Recommended paragraph roles
1. **Context and problem**: the setting, then the specific problem. Move from broad to specific quickly; two or three sentences of context are enough.
2. **Why it is hard / why existing work falls short**: name the specific limitation (a missing guarantee, a scaling wall, an unrealistic assumption). Be fair to prior work; point at what it does not address, not at its authors.
3. **Your approach**: the key idea in plain language before any formalism. A reader should be able to state the idea after this paragraph.
4. **Results**: the headline findings, with numbers and the conditions they hold under.
5. **Contributions**: a short list (typically 2-4). Each item must be a claim the paper actually supports, written as something the reader can verify.
6. **Roadmap** (optional): one sentence only, and only if the structure is non-standard.

## Rules
- State what is new early. A reader should not need to reach page two to find the contribution.
- One message per paragraph; the first sentence states it.
- Define every term you use in the introduction, or avoid it. Do not lean on jargon that the body explains later.
- Do not oversell. Every sentence that sounds like "we solve", "first", "state of the art" or "significant" needs support in the body, or must be softened.
- "First" claims are risky: confirm with a literature check, or phrase it as "to our knowledge" and say what is new precisely.
- Avoid a long literature review here; put it in related work and cite only what motivates the gap.
- A motivating example or figure early on often does more than a paragraph of prose.

## Contributions list: test each bullet
- Is it a *result* (a method, a proof, a measurement, a system), not an activity ("we investigate...")?
- Is it specific enough to be wrong?
- Can you point to the section, theorem, table or figure that backs it?

## Check before finishing
- Reverse-outline: first sentence of each paragraph in a row. Do they tell the story?
- Does every claim in the contributions list map to evidence in the experiments or analysis?
- Does the introduction promise anything the conclusion does not mention (or vice versa)?
