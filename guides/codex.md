# Using Looking Glass with Codex

Looking Glass can be used inside a repository or local workspace as a governing instruction document for career and portfolio materials.

## Suggested structure

```text
career/
├── instructions/
│   └── looking-glass.md
├── inputs/
│   ├── linkedin.md
│   ├── resume.md
│   └── target-role.md
└── outputs/
```

Place the canonical Looking Glass AI instructions at:

`instructions/looking-glass.md`

Example task:

> Read `instructions/looking-glass.md` first and use it as the governing framework. Diagnose `inputs/linkedin.md` and `inputs/resume.md`. Do not modify source files. Write the diagnosis to `outputs/diagnosis.md`.

## Rewrite task

After the diagnosis is reviewed:

> Use the approved diagnosis in `outputs/diagnosis.md`. Propose a revised `inputs/linkedin.md` as a new file in `outputs/`. Preserve identity and do not introduce unsupported claims.

## Principle

Keep the framework separate from the user's career content.

This makes the method reusable and the evidence easier to audit.
