# Writing in this repo

This is the reference for the AFK build workflow. Private, and written for Jamal
and for Claude to read mid-task — not as an introduction for anyone else.

## The rule that matters

**When a workflow problem is solved, it goes in `fixes/`.** That is why this
exists. A fix made in one project has twice failed to reach the others, and the
only reason it was caught was somebody remembering. Do not rely on that again.

Two kinds belong there, and the second is the one people skip:

- Fixed in one project, not yet propagated to the toolkit or the starters.
- Too small to justify changing a template, but real and recurring.

## How entries are written

**Index by the symptom, not the cause.** You recognise what was on screen long
before you know what went wrong, so the heading is what you saw.

Each entry gives four things: what you saw (the literal output), what was
actually wrong (often nowhere near the message), the fix (exact commands), and
how to tell it worked (a check that would have failed before).

## Voice

Plain language. Short sentences. Say the specific thing rather than the general
one: "126 of 157 tests skip without a database" beats "some tests may not run".

No marketing tone. No "simply" or "just". If something is genuinely confusing,
say so and explain why rather than smoothing over it.

Claims need evidence. If a number appears, it was measured. If a behaviour is
described, it was observed. This file is read when something is already broken,
and a confident wrong answer costs more than no answer.
