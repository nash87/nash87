# Florian Schulz

> Self-hosted AI platforms. Bare-metal Kubernetes, multi-vendor LLM orchestration, agent protocols. Göttingen, DE — 14+ years in production systems.

Full write-up: **[securanido.com](https://securanido.com)**.

## Currently in the lab

- A Rust-native platform layer running dual-mode — one CLI locally, the same crates as Kubernetes microservices, unified by a SvelteKit operator UI.
- An AI-first phone OS prototype on a SHIFTphone 8 (postmarketOS + Slint) — voice-driven, on-device LLM, agent runtime.
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
