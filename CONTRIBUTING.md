# Contributing

Looking Glass is intentionally small.

Contributions should improve the method without turning it into a provider-specific prompt collection or a generic career-coaching system.

## Good contributions

- clearer evidence rules;
- better examples;
- corrections to ambiguous language;
- accessibility improvements;
- provider usage guides that do not redefine the framework;
- new examples that expose edge cases;
- translations that preserve the method.

## Avoid

- adding unsupported career advice as framework rules;
- optimizing for one AI provider at the expense of portability;
- adding mandatory interview steps that increase friction without improving diagnosis;
- turning inference into scoring;
- promising hiring outcomes;
- making rewriting the default behavior.

## Source of truth

Changes to the method belong in:

`framework/looking-glass.md`

Changes to AI behavior belong in:

`instructions/looking-glass-instructions.md`

Tool guides should point to those files rather than restating the full method.

## Pull requests

A useful pull request should explain:

1. what problem it solves;
2. whether it changes the framework or only its implementation;
3. what behavior should remain unchanged;
4. an example showing the improvement.
