# Hey, I'm Santiago

I solve problems — the tool I reach for just happens to be code, most of the time.
I care more about the "why" behind a system than the stack it's built on: right now
that's meant Rust + Nix for reproducible tooling, and whatever fits when the problem
is someone else's domain, not mine.

## What I've built

### Pax

- Academic paper management is a mess: search, metadata, PDFs, references,
  reproducibility, all disconnected
- Split the problem cleanly instead of writing one more script — PAX handles
  papers, Nix handles artifacts (fetching, hashing, caching, reproducibility)
- Split into two components:
  - **[pax-core](https://github.com/Santiago-Garrote/pax)** — the library; the
    `pax` CLI is just one thin client on top of it
  - **[lazy-pax](https://github.com/Santiago-Garrote/lazy-pax)** — interactive
    TUI front-end to pax-core, in progress

### CETUCA

- Civil engineers doing road-safety pre-analysis were losing hours manually
  extracting data from footage, then feeding it into microsimulation models
  that were nearly impossible to calibrate for local driver behavior — bad
  calibration meant bad decisions downstream
- Proposed and built a pipeline that analyzes real-world vehicle trajectories
  directly instead of simulated ones, removing the calibration error and
  automating most of the manual pre-processing
- Split into three components:
  - **[TraTrac](https://github.com/CentroEstudiosTransporteUCA/TraTrac)** — trajectory tracking
  - **[FloCo](https://github.com/CentroEstudiosTransporteUCA/FloCo)** — flow counting
  - **[URBAn](https://github.com/CentroEstudiosTransporteUCA/URBAn)** — the GUI tying them together
- Done with UCA (Argentina), presented at a Civil Engineering congress

### uroboros

- Full-stack storefront for a stationery business
- Backend, frontend, and shared types built to actually ship and be used, not
  just a portfolio piece
- **[uroboros-frontend](https://github.com/UroborosDesigns/uroboros-frontend)**

### [.dotfiles](https://github.com/Santiago-Garrote/.dotfiles)

- How I work, not just what I've built — my whole system (NixOS + home-manager)
  declared and reproducible from one flake instead of manual, drifting config
- Custom theming/palette system so the desktop's look is generated config, not
  one-off tweaks — same instinct as pax: understand the system, make it
  reproducible

## Tools I reach for

[![Rust](https://img.shields.io/badge/-Rust-000000?logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Nix](https://img.shields.io/badge/-Nix-5277C3?logo=nixos&logoColor=white)](https://nixos.org/)
[![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/santiago-garrote-benes/) · [Email](mailto:santiagogarrote2005@gmail.com)
