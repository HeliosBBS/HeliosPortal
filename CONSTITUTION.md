# Constitution

The estate's shared constitution, in the `helios` plugin, is loaded first in every session and
holds the principles: authority from features down, security designed in, multi-node from the
start, the estate and its contracts, the spec rules. This file adds only what is specific to
HeliosPortal, and is loaded right after it, unchanged.

## Role

A user keeps one icon rather than one per board. It talks to a board only through the public JSON API and its OpenAPI description, so it never depends on engine internals.

It owns its own user interface and consumes the engine's public JSON API. An interface it owns changes here first, with a version,
before any consumer moves; an interface it consumes is cited by name and version from the
contracts register, never restated.

## How this file is used

Loaded after the shared constitution by every skill, every prompt and every loop iteration. A
change to it is a pull request the developer approves, and nothing else edits it.
