# GameClient-CasualMode

This fork is dedicated to a single unified build of GameClient with the client-side anticheat layer removed and all validation kept on the server.

## Scope

- No anticheat DLL dependency on the client
- No plugin initialization or shutdown wiring
- No AC settings persisted in the client configuration
- Full game logic and gameplay remain unchanged
- Multiplayer remains server-authoritative

## Patch set

The repo contains a fork-only patch package under `patches/` that is intended to be applied to the upstream client source tree when mirroring the project into this fork.

## Files in this fork

- `README.md` — fork overview
- `patches/remove-anticheat.patch` — upstream patch for the no-AC unified build
- `docs/implementation-notes.md` — notes explaining why the AC layer is redundant

