# Florian Schulz

> Self-hosted AI platforms. Bare-metal Kubernetes, multi-vendor LLM orchestration, agent protocols. Göttingen, DE — 14+ years in production systems.

The full write-up lives on **[securanido.com](https://securanido.com)**.

---

## Currently in the lab

- A Rust-native platform layer running dual-mode — local CLI and Kubernetes microservices, unified by a SvelteKit operator UI.
- An AI-first phone OS prototype on SHIFTphone 8 (postmarketOS + Slint) — voice-driven, on-device LLM, agent runtime.
- A multi-agent fleet coordinating over NATS JetStream and A2A v1.0 across Anthropic, Google, and local Ollama.

## Public open source

| Project | What | Stack |
|---|---|---|
| **[parkhub-rust](https://github.com/nash87/parkhub-rust)** | Self-hosted parking management. [Live demo](https://parkhub-rust-demo.onrender.com) | Axum · Astro 6 · React 19 · MIT |
| **[parkhub-php](https://github.com/nash87/parkhub-php)** | Same product on shared hosting. [Live demo](https://parkhub-php-demo.onrender.com) | Laravel 13 · PHP 8.4 · MIT |
| **[parkhub-site](https://github.com/nash87/parkhub-site)** | ParkHub marketing site. [Live](https://nash87.github.io/parkhub-site/) | Astro 6 · GitHub Pages |
| **[legal](https://nash87.github.io/legal/)** | GDPR-compliant Impressum & Datenschutz pages. | HTML · GitHub Pages |

Both ParkHub editions share the same product direction. Rust targets single-binary self-hosting; PHP fits conventional shared hosting.

## How I work

**Build, don't consume.** Rust-native implementations over npm-glue and SaaS lock-in.
**Self-hosted by default.** Bare-metal Kubernetes in Germany, GDPR-compliant, no foreign cloud.
**Production-grade from day one.** mTLS, signed builds, SBOM attestations — not afterthoughts.
**Multi-vendor AI.** Anthropic primary, with OpenAI, Google, and local Ollama fallback.

## Stack

Rust · TypeScript · PHP · Kubernetes · Cilium · Flux CD · PostgreSQL (CNPG) · Wolfi · HashiCorp Vault · SPIRE · cosign · Anthropic · OpenAI · Ollama · OpenTelemetry · eBPF

---

**[securanido.com](https://securanido.com)** · **[LinkedIn](https://www.linkedin.com/in/florian-schulz-a312bb137)** · fschulz0787@gmail.com
