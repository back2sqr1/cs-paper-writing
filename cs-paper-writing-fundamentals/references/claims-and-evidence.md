# Claims and Evidence

Every claim in a paper is one of: proved, supported by experiment, cited, or explicitly labeled as conjecture or opinion. Anything else is unsupported.

## Building a claim-evidence map
For each major claim in the abstract and introduction, write one line:

`Claim: <statement> | Evidence: <theorem / table / figure / citation> | Status: supported / needs evidence`

Then:
- **supported**: evidence exists and matches the claim's scope and strength.
- **needs evidence**: run the experiment or proof, or weaken the claim, or remove it.

## Calibrating strength
- Match verbs to evidence: "prove" (proof), "show empirically" (experiments), "suggest" (indirect evidence), "conjecture" (none yet).
- Bound the scope: "on the 12 benchmark scenes", "for graphs up to 10^5 nodes", "under bounded noise".
- Prefer numbers to adjectives. "Significantly" and "dramatically" need numbers or a statistical test.
- Avoid unsupported frequency words about the world ("rarely", "usually", "most") unless cited.
- Avoid superlatives and "first" unless verified.

## Negative results and limitations
- Report where the method fails or is not better. Honest limits make the positive results believable.
- Do not hide results that contradict the story; explain them or acknowledge them.

## Consistency checks
- Abstract, introduction, experiments and conclusion must agree on the same claims at the same strength.
- Numbers quoted in the text must match tables and figures exactly.
- Claims about a component must be backed by an ablation that isolates it.
