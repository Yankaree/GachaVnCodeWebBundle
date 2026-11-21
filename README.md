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

Source commit: 03944a0212581e3f2028b13d24d8e86b7d488e36
Source repository: Yankaree/Gacha-vncode
Source branch: VNcode
Build tool: Emscripten 3.1.74
Generated: 2026-11-21T01:38:38Z

pthreads are intentionally disabled (no SharedArrayBuffer).
