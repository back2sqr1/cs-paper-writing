# cs-paper-writing

A Claude skill: `cs-paper-writing-fundamentals`.
Guidance for writing and revising computer science and robotics papers, distilled in paraphrase from the principles of Justin Zobel's *Writing for Computer Science* (Springer). It is not a substitute for the book.

## Layout

```
cs-paper-writing-fundamentals/
├── SKILL.md                      # entry point: principles, routing table, output contract
└── references/
    ├── abstract.md
    ├── introduction.md
    ├── related-work.md
    ├── method.md
    ├── experiments.md
    ├── conclusion.md
    ├── claims-and-evidence.md
    ├── style.md
    ├── math-and-algorithms.md
    ├── figures-and-tables.md
    └── revision-checklist.md
```

`SKILL.md` tells Claude which reference file to read for the section being edited, so only the relevant guide is loaded.

## Install

Copy the whole `cs-paper-writing-fundamentals/` folder (including `references/`) into your skills directory, for example `~/.claude/skills/`.

If you upload it to claude.ai, zip the folder so that `SKILL.md` and `references/` are both inside the archive. A bare `SKILL.md` will load but its reference links will not resolve.
