# Using Looking Glass with Cursor

Looking Glass can live inside a local career or portfolio workspace.

## Suggested structure

```text
career/
├── looking-glass.md
├── linkedin.md
├── resume.md
├── portfolio.md
└── target-role.md
```

Copy the canonical AI instructions into:

`looking-glass.md`

Then ask Cursor to use that file as the analysis framework.

Example:

> Use `looking-glass.md` as the governing framework. Review `linkedin.md` and `resume.md`. Diagnose the current positioning and identify contradictions. Do not edit any files.

## Role comparison

> Use `looking-glass.md`. Compare `resume.md` and `portfolio.md` against `target-role.md`. Separate narrative gaps from actual evidence gaps. Do not rewrite yet.

## Editing

Only after the diagnosis is approved:

> Based on the accepted diagnosis, propose edits to `linkedin.md`. Preserve the current voice and do not add unsupported claims.

## Why this works well

File-based environments make the evidence boundary visible and allow the user to keep professional materials versioned alongside the framework.
