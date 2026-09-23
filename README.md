# HeliosPortal

Progressive web app with an address book for many Helios Advance boards.

A user keeps one icon rather than one per board. It talks to a board only through the public JSON API and its OpenAPI description, so it never depends on engine internals.

## Status: pre-release, built in the open

No version has been released and no tag exists. `main` holds releases only; work lands on
`development` through pull requests, and the issues and the estate's project board show what
is being worked on now.

The project is designed feature-first: the developer writes a brief for each feature in
`features/`, and the specifications in `docs/spec/` are derived from those briefs, with every
section naming the features it serves. `CONSTITUTION.md` holds what is specific to this
project; the principles shared across the estate live in the
[HeliosSkills](https://github.com/HeliosBBS/HeliosSkills) plugin.

## The estate

Part of [Helios](https://github.com/HeliosBBS): the [engine](https://github.com/HeliosBBS/HeliosAdvance),
the [Door Kit](https://github.com/HeliosBBS/HeliosDoorKit), the
[door hosting service](https://github.com/HeliosBBS/HeliosDoors), the
[Portal](https://github.com/HeliosBBS/HeliosPortal) and the
[SIP gateway](https://github.com/HeliosBBS/HeliosSIP). Each project's interface to the engine
is a protocol, a wire format, or nothing at all. This one owns its own user interface and consumes the engine's public JSON API.

## Licence

**GNU Affero General Public License, version 3 only** (not "or later").

