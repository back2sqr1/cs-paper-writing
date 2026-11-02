# Method / Problem Formulation

The method section must be precise enough that a competent reader could reimplement the work.

## Structure
1. **Problem statement**: inputs, outputs, assumptions, and what counts as success. Use a formal definition when one helps; give the intuition first.
2. **Overview**: a short roadmap, ideally with a pipeline figure. Name each component and how data flows between them.
3. **Components**: for each subsection, cover **motivation** (why this component), **design** (what it is, precisely), and **advantage** (what it buys over the obvious alternative).
4. **Properties** (if applicable): complexity, guarantees, failure modes, assumptions that matter.

## Rules
- Introduce each term and symbol before use; keep notation minimal and identical across the paper, figures and pseudocode.
- Describe design choices as choices: say what the alternatives were and why you picked this one. Avoid presenting the method as a patch on a naive baseline unless that is the contribution.
- Separate the idea from implementation detail. Put hyperparameters, engineering tricks and hardware specifics in the experimental setup or an appendix, unless they are essential to the idea.
- State assumptions explicitly (e.g., known dynamics, static scene, bounded noise) and say where they matter.
- Give an example or a worked case alongside any non-trivial definition.
- Keep tense and voice consistent: present tense for what the method does.

## Algorithms and pseudocode
- Inputs and outputs are stated at the top. Variable names match the text.
- Each non-obvious step has a comment or a sentence in the prose.
- Explain in prose what the algorithm does and why it is correct or effective; do not leave the pseudocode as the only explanation.

## Check before finishing
- Could a reader reproduce the method without contacting you? What is missing?
- Is there any term that appears in the method without a definition?
- Does each component's advantage connect to a result in the experiments (an ablation or a comparison)?
