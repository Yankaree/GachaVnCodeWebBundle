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

Source commit: 7653b7e0887713c35898e88060ea7f6c679b568c
Source repository: Yankaree/Gacha-vncode
Source branch: VNcode
Build tool: Emscripten 3.1.74
Generated: 2026-11-21T02:23:35Z

pthreads are intentionally disabled (no SharedArrayBuffer).
