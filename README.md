# Florian Schulz

<p align="center">
  <em>Self-hosted AI platforms — bare-metal Kubernetes, multi-vendor LLM orchestration, agent protocols.</em>
</p>

<p align="center">
  Göttingen, Germany &nbsp;·&nbsp; 14+ years operating production systems<br>
  <sub>Private home lab and proof-of-concept environment. Not a commercial offering.</sub>
</p>

---

## Currently in the lab

- A Rust-native platform layer running dual-mode (local CLI + Kubernetes microservices) — **200+ modular service crates**, unified through a SvelteKit operator UI.
- An AI-first phone OS prototype on SHIFTphone 8 (postmarketOS + Slint UI) — voice-driven, with on-device local LLM and an experimental agent runtime.
- A multi-agent fleet of **6+ specialized AI bots** (Claude + Gemini + Haiku + local Ollama on RTX 4070), coordinating over NATS JetStream and A2A v1.0 on bare-metal Kubernetes.
- End-to-end supply chain — cosign signatures, SBOM attestations, Kyverno PSS, Cilium + SPIRE mTLS, GitOps via Flux 2.4. **~50 platform services** on local hardware in Germany.

---

## Open Source (the public slice)

Most of the lab work above runs on internal repos. The public open-source slice:

| Project | Description | Lang |
|---------|-------------|------|
| [ParkHub Rust](https://github.com/nash87/parkhub-rust) | Self-hosted parking management — Axum + Astro 6 + React 19 + Tailwind 4. v4.13.0, GDPR-compliant, MIT. [Live demo](https://parkhub-rust-demo.onrender.com) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |
| [ParkHub PHP](https://github.com/nash87/parkhub-php) | Same product on Laravel 13 + PHP 8.4 for shared hosting. Identical Astro 6 + React 19 + Tailwind 4 frontend, MySQL/SQLite. [Live demo](https://parkhub-php-demo.onrender.com) | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) |
| [parkhub-site](https://github.com/nash87/parkhub-site) | ParkHub marketing site — Astro 6 + React 19 + Tailwind 4 on GitHub Pages. [Live](https://nash87.github.io/parkhub-site/) | ![Astro](https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white) |
| [legal](https://nash87.github.io/legal/) | GDPR-compliant legal pages (Impressum & Datenschutz) — deployed to GitHub Pages | ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) |

Both ParkHub editions share the same product direction and frontend. The Rust edition targets self-hosted single-binary deployment; the PHP edition fits conventional shared-hosting environments.

---

## How I work

- **Build, don't consume** — Rust-native implementations over npm-glue and SaaS lock-in.
- **Self-hosted by default, sovereign by design** — bare-metal Kubernetes in Germany, GDPR-compliant, no foreign cloud.
- **Production-grade from day one** — observability, mutual TLS, signed builds, and SBOM attestations are not afterthoughts.
- **Multi-vendor AI orchestration** — Anthropic primary, with OpenAI, Google, and local fallback. No single-vendor lockout.

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte">
  <img src="https://img.shields.io/badge/Cilium-F8C517?style=flat-square&logo=cilium&logoColor=black" alt="Cilium">
  <img src="https://img.shields.io/badge/Flux_CD-5468FF?style=flat-square&logo=flux&logoColor=white" alt="Flux CD">
  <img src="https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black" alt="HashiCorp Vault">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Anthropic-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Anthropic">
</p>

---

**Personal site:** [securanido.com](https://securanido.com) &nbsp;·&nbsp; **ParkHub:** [nash87.github.io/parkhub-site](https://nash87.github.io/parkhub-site/) &nbsp;·&nbsp; **LinkedIn:** [florian-schulz-a312bb137](https://www.linkedin.com/in/florian-schulz-a312bb137) &nbsp;·&nbsp; **Contact:** fschulz0787@gmail.com
