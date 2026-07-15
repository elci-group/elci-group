# The ELCI Group — Rust Developer Tools & Terminal Utilities

<p>
  <img alt="built with Rust" src="https://img.shields.io/badge/built%20with-Rust-c96f2e?style=flat-square">
  <img alt="open source" src="https://img.shields.io/badge/open%20source-FOSS-39d6d6?style=flat-square">
  <img alt="platform: linux" src="https://img.shields.io/badge/platform-Linux-8a8f98?style=flat-square">
</p>

**The ELCI Group** (UK) builds fast, open-source, **Rust-native developer tools for the terminal**: an autonomous semantic-versioning daemon, intelligent process lifecycle management, LLM context-bundling and code-analysis utilities, and small composable CLI tools that each do one job well.

## kaptaind — autonomous semantic versioning

Autonomous semantic versioning, change analysis, and deterministic conventional commits. Runs as a daemon, watches your working tree, scores diffs, and cuts releases with changelogs — no human in the loop required.

![kaptaind analyzing a change](https://raw.githubusercontent.com/elci-group/kaptaind/main/analyze_and_log.gif)

→ [elci-group/kaptaind](https://github.com/elci-group/kaptaind)

## pv — intelligent process lifecycle management

[**Pressure Valve**](https://github.com/elci-group/pv) treats a process not as a PID that is either running or dead, but as an *intent* with lifecycle semantics: it understands what each process is trying to accomplish, predicts resource exhaustion before it happens, and can suspend, resume, detach, and migrate work accordingly. *The process is no longer sacred. The objective is.*

## The Rust toolbox

| Tool | What it does |
|---|---|
| [Walt](https://github.com/elci-group/Walt) | Converts Rust source into a linearized form for LLM training — and back, losslessly |
| [marty](https://github.com/elci-group/marty) | Smart, history-driven directory traversal |
| [bound](https://github.com/elci-group/bound) | Bundles large file sets into a single file for LLM context |
| [bart](https://github.com/elci-group/bart) | Visualises storage use within a directory |
| [deckhand](https://github.com/elci-group/deckhand) | Deterministic build-surface maintenance and hygiene agent |
| [amber](https://github.com/elci-group/amber) | Autonomous dependency-reduction engine for Rust |
| [furnace](https://github.com/elci-group/furnace) | AI-powered semantic Rust code analyzer with 10 output styles |
| [snakepit](https://github.com/elci-group/snakepit) | Python dependency installer with multiple backends and venv management |
| [umami](https://github.com/elci-group/umami) | Multi-tier memory-pressure buffering daemon for Linux: RAM → ZRAM → flash → disk, driven by PSI |
| [bank](https://github.com/elci-group/bank) | Context-aware `mkdir`/`touch` with timestamp and permission control |
| [modrn](https://github.com/elci-group/modrn) | One command to update all your `mod.rs` files |
| [winch](https://github.com/elci-group/winch) | Automatic Cargo dependency resolver ([winch-daemon](https://github.com/elci-group/winch-daemon) runs it continuously) |
| [egor](https://github.com/elci-group/egor) | Simple Go version manager, written in Rust |
| [rena](https://github.com/elci-group/rena) | Renaming tool with Gemini integration for automated batch renames |
| [oip](https://github.com/elci-group/oip) | Rapid prototyping: overwrite project files straight from LLM clipboard output |

## Experiments & platforms

- [scotia](https://github.com/elci-group/scotia) — Semantic Decision Ledger: git-native audit logs for agentic systems
- [padagonia](https://github.com/elci-group/padagonia) — Ontology-native graph store with HNSW vector search
- [venturi](https://github.com/elci-group/venturi) — DAG language runtime
- [guac](https://github.com/elci-group/guac) — Git + Groq Augmented Cognition: conversational agent with git-native memory
- [vicount](https://github.com/elci-group/vicount) — Chat-first terminal UI for ViCo Desktop

## Heritage

Our one-command Linux software installers and GUI onboarding tools live at [**@ELCI-Linux**](https://github.com/ELCI-Linux).

## Philosophy

Rust. Terminal-first. One tool, one job, no runtime you didn't ask for.
