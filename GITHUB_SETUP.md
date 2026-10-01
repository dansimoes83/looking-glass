# GitHub setup

## Recommended repository name

`looking-glass`

## Repository description

> Model-agnostic framework for diagnosing professional narrative before rewriting it.

## Suggested topics

- career
- positioning
- professional-narrative
- linkedin
- resume
- portfolio
- llm
- ai
- prompt-engineering
- framework
- career-tools

## Create with GitHub CLI

```bash
gh repo create looking-glass \
  --public \
  --description "Model-agnostic framework for diagnosing professional narrative before rewriting it."
```

Then, from the local repository:

```bash
git init
git branch -M main
git add .
git commit -m "Release Looking Glass v1.0.0"
git remote add origin git@github.com:YOUR-GITHUB-USERNAME/looking-glass.git
git push -u origin main
```

## Create the first release

After pushing:

```bash
gh release create v1.0.0 \
  --title "Looking Glass v1.0.0" \
  --notes-file release/v1.0.0.md
```

## Suggested About text

**Description**

Model-agnostic framework for diagnosing professional narrative before rewriting it.

**Website**

Add the project page or portfolio URL when available.

## Pin these files

The README should point readers first to:

1. `framework/looking-glass.md`
2. `instructions/looking-glass-instructions.md`

Do not make a provider-specific guide the conceptual entry point.
