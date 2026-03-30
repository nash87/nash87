# Florian — Platform Engineer & AI Systems Architect

<p align="center">
  <em>Jumping over the edge, not cutting it.</em>
</p>

<p align="center">
  Platform Engineer &amp; AI Systems Architect -- Goettingen, Germany<br>
  14+ years building infrastructure. Self-hosted everything. Zero vendor lock-in.
</p>

> I build platforms I own and understand end-to-end.
> Every layer is reproducible from Git. No managed black boxes.

---

## What I Build

**Forge Platform** -- A self-hosted AI-native operating platform running on bare-metal Kubernetes. 100+ microservices in Rust, 8 AI agents, real-time dashboards, GitOps-managed. Everything from code search to financial tracking to agent orchestration, built as modular Rust crates that work both as CLI tools and K8s services.

Highlights:
- 36+ Rust microservices, 600+ API endpoints
- Multi-model AI agent fleet (Claude, Gemini, Ollama local inference)
- SvelteKit 2 + Svelte 5 dashboard with 105+ pages
- MCP, ACP, A2A protocol support
- Flux CD GitOps, Cilium eBPF networking, Vault secrets
- WireGuard VPN via Defguard for mobile access

---

## Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte 5">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

**Infrastructure**
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Cilium-F8C517?style=flat-square&logo=cilium&logoColor=black" alt="Cilium">
  <img src="https://img.shields.io/badge/Flux_CD-5468FF?style=flat-square&logo=flux&logoColor=white" alt="Flux CD">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm">
  <img src="https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white" alt="Podman">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

**AI & Data**
<p>
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/Claude-6B46C1?style=flat-square" alt="Claude">
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SurrealDB-FF00A0?style=flat-square&logo=surrealdb&logoColor=white" alt="SurrealDB">
  <img src="https://img.shields.io/badge/Qdrant-DC382D?style=flat-square" alt="Qdrant">
</p>

**Security & Networking**
<p>
  <img src="https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black" alt="HashiCorp Vault">
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white" alt="WireGuard">
  <img src="https://img.shields.io/badge/Kyverno-FF9800?style=flat-square&logo=kubernetes&logoColor=white" alt="Kyverno">
  <img src="https://img.shields.io/badge/cert--manager-326CE5?style=flat-square" alt="cert-manager">
</p>

---

## Open Source

| Project | Description | Stack |
|---------|-------------|-------|
| [ParkHub Rust](https://github.com/nash87/parkhub-rust) | Self-hosted parking management. Single binary, embedded redb, Astro 6 + React 19, credits, i18n (10 langs), GDPR. [Demo](https://parkhub-rust-demo.onrender.com) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) |
| [ParkHub PHP](https://github.com/nash87/parkhub-php) | Same features, shared hosting friendly. Laravel 12, MySQL/SQLite, Astro 6 + React 19. [Demo](https://parkhub-php-demo.onrender.com) | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) |
| [infracraft-demos](https://github.com/nash87/infracraft-demos) | Live interactive demos -- both ParkHub editions running side by side | ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) |

---

## Infrastructure

| Layer | Stack |
|-------|-------|
| **Compute** | kubeadm cluster, 3 nodes (2x CP + 1 RPi5 witness) |
| **Orchestration** | Kubernetes 1.32, kubeadm-managed |
| **GitOps** | Flux CD -- declarative cluster state from Git |
| **Networking** | Cilium (eBPF CNI + network policy + Hubble) |
| **Secrets** | HashiCorp Vault (HA) + External Secrets Operator |
| **Policy** | Kyverno admission controller |
| **VPN** | Defguard (WireGuard) -- mobile access to homelab |
| **Registry** | Zot OCI registry (self-hosted) |
| **DNS** | CoreDNS + internal `.test` zone |
| **TLS** | cert-manager with internal CA |

---

## Stats

<p align="center">
  <a href="https://github.com/nash87">
    <img src="https://github-readme-stats.vercel.app/api?username=nash87&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="160">
  </a>
  <a href="https://github.com/nash87">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nash87&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="160">
  </a>
</p>

<p align="center">
  <a href="https://github.com/nash87">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=nash87&theme=github-dark-blue&hide_border=true" alt="GitHub Streak">
  </a>
</p>

---

<p align="center">
  <a href="https://nash87.github.io/infracraft-demos">Live Demos</a> ·
  <a href="mailto:fschulz0787@gmail.com">fschulz0787@gmail.com</a> ·
  Available for platform engineering & infrastructure consulting
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nash87&style=flat-square&color=326CE5" alt="Profile views">
</p>
