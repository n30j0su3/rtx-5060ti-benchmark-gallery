# RTX 5060 Ti Benchmark Gallery

> **FreakingJSON Agencia • AI Operations Center**

Public SPA: <https://n30j0su3.github.io/rtx-5060ti-benchmark-gallery/>

## What changed on 2026-05-29

This gallery now fuses the original RTX 5060 Ti throughput evidence with the final all-local MiniV/Vector trust-gate run.

- Source run: `all-local-model-eval-20260528-231052`
- Environment highlighted here: **Vector RTX 5060 Ti CUDA**
- Vector models evaluated: **8**
- Strict end-to-end Vector champions: **vector-qwen36-35b-a3b-q4xl**
- Gold-stage strict Vector passers: **vector-qwen36-35b-a3b-q4xl, vector-qwen35-9b-glm-q4**
- N30 credit: `All benchmark orchestration, methodology design, and AI model evaluations directed by N30.`

## Methodology

N30's trust policy is multi-pass:

1. **Smoke** — agentic/structured trust probes.
2. **Framework** — framework-spec tasks.
3. **Gold** — high-signal creative UI/canvas-style tasks.

Attempt 1 is the strict trust measurement. Attempts 2-3 are recovery signals only. Recoverable lanes are never labeled as production-strict unless their classification says so.

## Jackrong comparison frame

The page links to Jackrong/Kyle Hessling's public `qwopus36-eval` Space:

<https://huggingface.co/spaces/Jackrong/qwopus36-eval>

That Space uses a 16-prompt suite (agentic, web-design, canvas/WebGL) for Qwopus3.6-27B v1-preview. This gallery uses the same comparison vocabulary to contextualize N30's local gates; it is **not** an apples-to-apples hardware claim.

## Files

- `index.html` — public single-page gallery.
- `data/all-local-evaluation-summary.json` — normalized public summary with source artifact hashes.
- `data/vector-rtx-results.json` — Vector RTX subset.
- `benchmark-metrics.json` / `data/benchmark-metrics.json` — combined legacy throughput + trust-gate data.

## Official links

- GitHub: <https://github.com/n30j0su3>
- FreakingJSON Linktree: <https://linktr.ee/freakingjson>
- X/Twitter: <https://x.com/freakingjson>
- YouTube: <https://www.youtube.com/@freakingjson>

© 2026 FreakingJSON Agencia.

## Features
- Live ES/EN language toggle, dark/light mode, and mobile-first responsive charts/tables.
