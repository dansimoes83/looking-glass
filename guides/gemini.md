# Using Looking Glass with Gemini

Looking Glass can be used as the instruction layer for a Gemini Gem or as context in a normal Gemini conversation.

## Persistent use

When the environment allows persistent instructions, use:

`instructions/looking-glass-instructions.md`

as the canonical behavior definition.

Add the professional material separately.

Suggested first request:

> Use Looking Glass to diagnose how my current professional narrative is being perceived. Do not rewrite yet.

## Conversation use

Attach or paste:

1. `looking-glass-instructions.md`
2. the material to review
3. an optional target role or goal

## Keep one source of truth

Do not create a Gemini-specific rewrite of the Looking Glass method unless the platform requires a technical adaptation.

The canonical instruction file should remain the source of truth.
