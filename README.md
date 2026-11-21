# Gacha VNcode Web Bundle

This repository contains **generated Web build output** from
[`Yankaree/Gacha-vncode`](https://github.com/Yankaree/Gacha-vncode)
(branch `VNcode`), built with Emscripten and WebGL2.

**Do not edit files in this repository manually.** They are
overwritten on every successful Web build of the source repository.

Files at the repository root are served directly for static hosting:
`index.html` is the entry point; `GachaVNcode.js` loads the module,
`GachaVNcode.wasm` is the compiled game, and `GachaVNcode.data`
contains the preloaded assets.

## Build provenance

Source commit: 30259a5a9e01c466efff543a8be1a0956dd5ee19
Source repository: Yankaree/Gacha-vncode
Source branch: VNcode
Build tool: Emscripten 3.1.74
Generated: 2026-11-21T01:59:17Z

pthreads are intentionally disabled (no SharedArrayBuffer).
