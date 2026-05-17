# Florian Schulz

**fop is the control plane I built to run everything I do.** One Rust binary: a CLI in my terminal and, from the same crates, signed microservices in Kubernetes. Every build, test, deploy and agent task goes through it — including a multi-CLI harness where Claude, Codex, Kimi and Gemini work as parallel coding agents on one shared task board. The fully open-source slice of this is ParkHub.

Full write-up: **[securanido.com](https://securanido.com)**.

## Currently in the lab

- fop — a Rust control plane where ~50 services are each both a local subcommand and a signed Kubernetes microservice. Same code, two runtimes. Private home lab in Germany, research and demonstration, end to end.
- A multi-CLI agent harness — Claude, Codex, Kimi and Gemini run as parallel coding agents inside the same control plane, coordinating through one shared task board with worktree isolation and a build queue.
- An AI-first phone OS on a Linux mainline handset — postmarketOS, a Slint-native UI, and an on-device LLM running the same agent runtime as the cluster. The phone is a first-class target of the platform, not a companion app.
- A multi-agent fleet coordinating over NATS JetStream and A2A v1.0 across Anthropic, Google, and local Ollama.

## Public open source

| Project | What | Stack |
|---|---|---|
| **[parkhub-rust](https://github.com/nash87/parkhub-rust)** | Self-hosted parking management | Axum · Astro 6 · React 19 · MIT |
| **[parkhub-php](https://github.com/nash87/parkhub-php)** | Same product for shared hosting | Laravel 13 · PHP 8.4 · MIT |
| **[parkhub-site](https://nash87.github.io/parkhub-site/)** | ParkHub site | Astro 6 · GitHub Pages |
| **[legal](https://nash87.github.io/legal/)** | GDPR Impressum & Datenschutz | HTML · GitHub Pages |

Both ParkHub editions share one product direction: the Rust build targets single-binary self-hosting; the PHP build fits conventional shared hosting.

## How I work

**Build, don't consume** — Rust-native over npm-glue and SaaS lock-in.
**Self-hosted by default** — bare-metal Kubernetes in Germany, GDPR-compliant, no foreign cloud.
**Production-grade from day one** — mTLS, signed builds, SBOM attestations, not afterthoughts.
**Multi-vendor AI** — Anthropic primary; OpenAI, Google, local Ollama fallback.

## Stack

Rust · TypeScript · PHP · Kubernetes · Cilium · Flux CD · PostgreSQL (CNPG) · Wolfi · Vault · SPIRE · cosign · Kyverno · OpenTelemetry · eBPF

---

**[securanido.com](https://securanido.com)** · **[LinkedIn](https://www.linkedin.com/in/florian-schulz-a312bb137)** · fschulz0787@gmail.com
