# workflow-docs

The Mintlify site for the AFK build workflow: how it works, how to run it, and
what to do when it breaks.

Private. Written for Jamal and for Claude to read mid-task.

## Editing

Pages are MDX. `docs.json` holds the navigation. Mintlify builds from `main`.

## The one rule

**When you solve a workflow problem, add it to `fixes/`.** The site exists so the
next session does not rediscover what this one worked out — and because a fix
made in one project has twice failed to reach the others.
