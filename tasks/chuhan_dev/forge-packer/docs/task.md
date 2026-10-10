# Task brief: forge-packer

Owner: chuhan_dev

## Goal
Build a small internal utility called *forge-packer* for the DevTaskArena collection.
The utility should expose a minimal CLI, keep its state under a single
working directory, and fail loudly on bad input.

## Acceptance sketch
- CLI parses the documented flags.
- Exit codes: 0 on success, 2 on usage errors.
- A short demo run is described in the user prompt.

(This folder is part of the DevTaskArena dev board; acceptance is judged
by the current acceptance policy at the repo root, not by this brief.)
