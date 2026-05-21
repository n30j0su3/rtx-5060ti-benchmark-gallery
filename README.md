# RTX 5060 Ti Benchmark Gallery

> **FreakingJSON Agency • AI Operations Center**

[![English](https://img.shields.io/badge/lang-English-blue)](README.md)
[![Spanish](https://img.shields.io/badge/lang-Spanish-green)](README_ES.md)

---

## Overview (English)

This repository presents benchmark results for **Qwopus/Jackrong/Hessling Lab models** tested on consumer-grade hardware: NVIDIA RTX 5060 Ti 16GB (Blackwell architecture).

### Key Findings

| Metric | Result |
|--------|--------|
| **Best 9B Model** | Qwopus3.5-9B Claude Opus Distill — 56.37 tok/s |
| **Best 27B MTP Lane** | Qwen3.6-27B Q3_K_S + MTP nmax=2 — 41–43 tok/s |
| **Max Throughput** | 194.7 tok/s (Qwen3.5-2B CUDA baseline) |
| **Benchmark Window** | updated window (Apr 24 → May 20, 2026) |
| **Models Tested** | 10 (Qwopus/Qwen3.6 MTP variants + baseline controls) |

### Blockers Encountered

- **DeepSeek Reasoning** — Thinking blocks in GGUF chat template (no fix on 16GB VRAM)
- **Unsupported architectures in older runtimes** — resolved by upgrading the llama.cpp runtime
- **16GB VRAM pressure** — resolved through Q3/Q2 MTP lanes and MoE quant selection

### Interactive Dashboard

Open `index.html` in browser for full SPA with:
- 📊 Chart.js throughput visualization
- 🖥️ Hardware hero card with neon glow
- 📋 Model comparison table
- 🏆 Pokedex/StarWars scores
- 🌐 Bilingual toggle (EN/ES)

---

## Resumen (Español)

Este repositorio presenta resultados de benchmark para modelos **Qwopus/Jackrong/Hessling Lab** probados en hardware consumer: NVIDIA RTX 5060 Ti 16GB (Blackwell).

### Hallazgos Clave

| Métrica | Resultado |
|---------|-----------|
| **Mejor modelo 9B** | Qwopus3.5-9B Claude Opus Distill — 56.37 tok/s |
| **Mejor lane 27B MTP** | Qwen3.6-27B Q3_K_S + MTP nmax=2 — 41–43 tok/s |
| **Throughput máximo** | 194.7 tok/s (baseline Qwen3.5-2B CUDA) |
| **Ventana de benchmark** | ventana actualizada (Abr 24 → May 20, 2026) |
| **Modelos probados** | 10 (variantes Qwopus/Qwen3.6 MTP + controles baseline) |

### Dashboard Interactivo

Abrir `index.html` en browser para SPA completa con:
- 📊 Gráficas Chart.js de throughput
- 🖥️ Hero card de hardware con glow neon
- 📋 Tabla comparativa de modelos
- 🏆 Puntuaciones Pokedex/StarWars
- 🌐 Toggle bilingüe (EN/ES)

---

## Repository Structure

```
rtx-5060ti-benchmark-gallery/
├── index.html                 # SPA dashboard (bilingual)
├── data/
│   ├── benchmark-metrics.json # Raw data
│   └── hardware-specs.json    # RTX specs
├── assets/locales/
│   ├── en.json                # English translations
│   └── es.json                # Spanish translations
├── docs/
│   ├── tweet-response.md      # Ready-to-use tweet reply
│   └── methodology-v5.md      # Phased generation explained
└ └── README.md                # This file
```

---

## Contact

**FreakingJSON Agency** — AI Operations for e-commerce, automation, and agency workflows.

Twitter/X: [@freakingjson](https://twitter.com/freakingjson)

---

*"Free your mind." — Morpheus*

*Built with Chart.js • Dark theme #0a0a0a • Accent #f2fc9e*