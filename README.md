# OpenRock-Terrain

Bounded flood-fill, choke-point detection, and room-safety coverage tracking - Bedrock has no native concept of a room, a connected area, or a choke point, so this fills that real gap.

Part of the [OpenRock](https://github.com/codex-alchemist-dev/OpenRock) Minecraft Bedrock mod-packaging ecosystem - a Codex Alchemist project, under Fireball Everything. Consumed as a real git submodule at `libs/terrain` in the main OpenRock repo, and directly `npm require`/`import`-able (real top-level CommonJS exports, esbuild-CJS/ESM-interop-compatible) by any mod's own build-time kernel registration or real in-game script.

## License

MPL-2.0. See [LICENSE](LICENSE).
