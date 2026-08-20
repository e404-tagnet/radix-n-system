<!-- TAGNET README HEADER — Catppuccin Mocha — do not edit by hand -->
<div align="center">

[![License](https://img.shields.io/github/license/e404-tagnet/radix-n-system?color=313244&labelColor=11111b&label=License&style=flat-square)](https://github.com/e404-tagnet/radix-n-system/blob/main/LICENSE)
[![Status](https://img.shields.io/badge/Status-experimental-fab387?labelColor=11111b&style=flat-square)](https://github.com/e404-tagnet/radix-n-system/pulse)
[![Version](https://img.shields.io/github/v/release/e404-tagnet/radix-n-system?color=313244&labelColor=11111b&label=Version&style=flat-square)](https://github.com/e404-tagnet/radix-n-system/releases)
[![Docs](https://img.shields.io/badge/Docs-HTML-89b4fa?labelColor=11111b&style=flat-square&logo=read-the-docs&logoColor=89b4fa)](./compute_first_language_pm_.html)
[![Repo](https://img.shields.io/badge/Repo-radix-n-system-94e2d5?labelColor=11111b&style=flat-square&logo=github&logoColor=94e2d5)](https://github.com/e404-tagnet/radix-n-system)
[![Tagnet](https://img.shields.io/badge/By-Tagnet-89dceb?labelColor=11111b&style=flat-square&logo=tag&logoColor=89dceb)](https://tagnet.dev)

</div>
<!-- TAGNET README HEADER — end -->

# radix-n-system / AXON

> *A language whose semantics derive from machine architecture, not human metaphor.*

This repository holds research materials for **AXON**, a compute-first programming language experiment. The current work is a pre-discovery framing document and project plan, not a working compiler.

## Problem statement

Mainstream languages encode human cognitive habits: named variables, linear text, sequential metaphor, base-10 assumptions. Compilers then spend enormous effort translating those abstractions back into registers, pipelines, memory hierarchies, and instruction parallelism.

**Hypothesis:** a language whose primary abstraction mirrors the machine's execution model could eliminate whole classes of translation overhead and expose optimisation space humans would not naturally write toward.

## Documents

| File | Purpose |
|---|---|
| [`compute_first_language_pm_.html`](./compute_first_language_pm_.html) | Project Initiation Document — v0.1 draft |
| [`compute_first_language_pm_plan.html`](./compute_first_language_pm_plan.html) | Planning variant of the PID |
| [`LICENSE`](./LICENSE) | GPL-3.0 |

## Phases (from PID)

1. **Phase 0 — Needs + constraint analysis** *(blocker)*: define "compute-first", map target hardware, set measurable success criteria.
2. **Phase 1 — Core compute model**: dataflow, SSA-native, actor, or hardware-description logic.
3. **Phase 2 — Semantics + syntax**: formal semantics first; syntax is a reversible view over the IR.
4. **Phase 3 — Human interface layer**: kept separate, generatable on top.
5. **Phase 4 — Prototype runtime**: single target, benchmarked against C.

## Status

Pre-discovery. No compiler, no formal semantics, no runtime yet. This is a research framing exercise.

## License

Licensed under [GPL-3.0](./LICENSE).


<!-- TAGNET README FOOTER — start -->

<div align="center">

**Like this work? Fuel the next widget / experiment / scaffold.**

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%23FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/e404.tagnet)
[![Patreon](https://img.shields.io/badge/Support-Patreon-ff424d?logo=patreon&logoColor=white&style=for-the-badge)](https://www.patreon.com/VeritasExMachina?utm_campaign=creatorshare_creator)

<small>Crafted with caffeine, curiosity, and a Catppuccin palette · © e404-tagnet</small>

</div>
<!-- TAGNET README FOOTER — end -->
