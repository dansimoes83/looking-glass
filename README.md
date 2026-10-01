# Looking Glass

**Diagnose before writing.**

Looking Glass is a model-agnostic professional narrative diagnostic framework.

It helps people understand how their experience is currently being perceived before rewriting a LinkedIn profile, résumé, portfolio, bio, or other professional narrative.

Looking Glass is not a LinkedIn optimizer, a résumé generator, or a promise of market success. Its job is to separate evidence from interpretation, make positioning signals visible, and help a person decide what should change before changing the writing.

## Core principle

> Diagnose before writing.

The order matters:

**Material → Evidence → Diagnosis → Direction → Rewrite, only if requested**

Looking Glass prioritizes:

- evidence over assumption;
- identity over optimization;
- diagnosis over immediate rewriting;
- clarity over persuasion;
- explicit uncertainty over false confidence.

## What Looking Glass can review

Looking Glass can be used with:

- LinkedIn profiles;
- résumés and CVs;
- portfolios and case-study narratives;
- professional bios;
- About pages;
- role descriptions;
- job opportunities;
- career positioning material;
- combinations of the above.

It can also compare an existing professional narrative against a specific role or direction when enough evidence is provided.

## One framework, multiple environments

Looking Glass does not depend on a specific AI provider or model.

You can use it:

1. **As persistent instructions**
   - AI projects or workspaces
   - custom assistants
   - GPT-style assistants
   - Gemini Gems
   - other environments that support persistent instructions

2. **As context in a conversation**
   - attach `instructions/looking-glass-instructions.md`
   - provide the professional material to review
   - ask for a diagnosis

3. **Inside AI-assisted work environments**
   - Cursor
   - Codex
   - other coding or knowledge work environments that can read project files

4. **Without AI**
   - use `framework/looking-glass.md` as a manual review method

The method is stable. The installation changes.

## Quick start

### With an AI assistant

Give the assistant:

- `instructions/looking-glass-instructions.md`
- the professional material you want reviewed
- your goal, if you have one

Then ask:

> Use Looking Glass to diagnose how this material is currently positioning me. Do not rewrite anything yet.

### Without AI

Open:

`framework/looking-glass.md`

Follow the diagnostic flow manually.

## Repository structure

```text
looking-glass/
├── README.md
├── LICENSE.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── GITHUB_SETUP.md
├── framework/
│   └── looking-glass.md
├── instructions/
│   └── looking-glass-instructions.md
├── guides/
│   ├── chatgpt.md
│   ├── gemini.md
│   ├── conversation.md
│   ├── cursor.md
│   └── codex.md
├── examples/
│   ├── linkedin-review.md
│   ├── portfolio-review.md
│   └── role-comparison.md
└── release/
    └── v1.0.0.md
```

## Source of truth

The canonical definition of the method is:

`framework/looking-glass.md`

The canonical AI instruction file is:

`instructions/looking-glass-instructions.md`

Tool-specific guides should not redefine the method. They only explain how to load and use it in different environments.

## What Looking Glass does not do

Looking Glass should not:

- invent experience, authority, metrics, or outcomes;
- exaggerate seniority;
- assume access to private or external data;
- present inference as fact;
- rewrite by default;
- optimize a person into a generic market persona;
- treat keywords as more important than evidence;
- predict hiring outcomes;
- claim that a narrative change guarantees job-market results.

## Evidence model

Looking Glass separates claims into three types:

### Direct Evidence
Information directly present in the material supplied by the user.

### Verified External Evidence
Information confirmed through an external source when the user explicitly requests external research and the environment supports it.

### Inference
A reasoned interpretation based on patterns in the available evidence.

Inference must never be presented as direct evidence.

## License

Looking Glass is released under **CC BY 4.0**.

You may use, share, and adapt the framework, including commercially, as long as appropriate attribution is provided and changes are indicated.

See `LICENSE.md`.

## Attribution

Created by **Daniel Simões**.

Suggested attribution:

> Looking Glass, created by Daniel Simões. Licensed under CC BY 4.0.

## Version

**1.0.0**

This is the first public, model-agnostic release of Looking Glass.
