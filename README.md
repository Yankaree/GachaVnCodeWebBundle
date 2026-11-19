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

Source commit: 757fc23f1607ee7b464d8c24eaa5b29aca1c6c6b
Source repository: Yankaree/Gacha-vncode
Source branch: VNcode
Build tool: Emscripten 3.1.74
Generated: 2026-11-19T07:24:10Z

pthreads are intentionally disabled (no SharedArrayBuffer).
