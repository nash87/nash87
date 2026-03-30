# Florian — Platform Engineer & AI Systems Architect

<p align="center">
  <em>Jumping over the edge, not cutting it.</em>
</p>

<p align="center">
  Platform Engineer &amp; AI Systems Architect · Göttingen, Germany<br>
  14+ years building production infrastructure. Self-hosted everything. Zero vendor lock-in.
</p>

> I build the kind of platform most companies outsource to three vendors and a consulting firm.
> One person, bare metal to UI. Every layer owned, every line reproducible from Git.

---

## Forge — AI-Native Operating Platform

A self-hosted platform that unifies AI agents, infrastructure automation, and business tools into a single system running on bare-metal Kubernetes. Not a wrapper around APIs. Not a dashboard for someone else's cloud. The real thing.

<table>
<tr><td><strong>93 Rust crates</strong></td><td>80 microservices + 13 CLI modules, all from one monorepo</td></tr>
<tr><td><strong>186-page dashboard</strong></td><td>SvelteKit 2 + Svelte 5, 126K lines, 2600+ i18n keys (DE/EN)</td></tr>
<tr><td><strong>8 AI agents</strong></td><td>Autonomous fleet — each with a role, memory, tools, and MCP access</td></tr>
<tr><td><strong>85 API services</strong></td><td>Everything from finance to code search to agent orchestration</td></tr>
<tr><td><strong>36,749 tests</strong></td><td>Automated quality harness across Rust, PHP, and Node</td></tr>
<tr><td><strong>267 pods</strong></td><td>Running across 3 nodes, 57 namespaces, fully GitOps-managed</td></tr>
</table>

The platform handles its own builds, deployments, monitoring, knowledge management, security scanning, and task scheduling. The AI agents don't just answer questions — they operate infrastructure, analyze code, monitor markets, and coordinate with each other through a custom agent bus.

What makes this different: every component is a Rust crate that works both as a CLI tool on my laptop and as a K8s microservice in production. Same code, two runtimes. No vendor lock-in at any layer.

---

## Stack

**Core**
<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Svelte_5-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte 5">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Cilium-F8C517?style=flat-square&logo=cilium&logoColor=black" alt="Cilium">
  <img src="https://img.shields.io/badge/Flux_CD-5468FF?style=flat-square&logo=flux&logoColor=white" alt="Flux CD">
</p>

**AI & Data**
<p>
  <img src="https://img.shields.io/badge/Claude-6B46C1?style=flat-square" alt="Claude">
  <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" alt="Gemini">
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SurrealDB-FF00A0?style=flat-square&logo=surrealdb&logoColor=white" alt="SurrealDB">
  <img src="https://img.shields.io/badge/Qdrant-DC382D?style=flat-square" alt="Qdrant">
</p>

**Infrastructure**
<p>
  <img src="https://img.shields.io/badge/Vault-FFEC6E?style=flat-square&logo=vault&logoColor=black" alt="Vault">
  <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white" alt="WireGuard">
  <img src="https://img.shields.io/badge/Kyverno-FF9800?style=flat-square" alt="Kyverno">
  <img src="https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white" alt="Podman">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

---

## Open Source

| Project | What it does | Stack |
|---------|-------------|-------|
| [ParkHub Rust](https://github.com/nash87/parkhub-rust) | Self-hosted parking management. Single binary, zero dependencies, 10 languages. [Live](https://parkhub-rust-demo.onrender.com) | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black) |
| [ParkHub PHP](https://github.com/nash87/parkhub-php) | Same product, built for shared hosting. Laravel 12 + MySQL. [Live](https://parkhub-php-demo.onrender.com) | ![PHP](https://img.shields.io/badge/Laravel_12-FF2D20?style=flat-square&logo=laravel&logoColor=white) |
| [infracraft-demos](https://github.com/nash87/infracraft-demos) | Both ParkHub editions running side by side | ![HTML](https://img.shields.io/badge/Astro_6-BC52EE?style=flat-square&logo=astro&logoColor=white) |

---

## How It's Built

| Layer | What runs there |
|-------|----------------|
| **Compute** | 3-node kubeadm cluster (2 CP + RPi5 witness), bare metal |
| **GitOps** | Flux CD — every change lands via Git, auto-reconciled |
| **Networking** | Cilium eBPF — CNI, network policy, Hubble observability |
| **Secrets** | HashiCorp Vault (HA) + External Secrets Operator |
| **Policy** | Kyverno — admission control, image signing, best practices |
| **VPN** | Defguard (WireGuard) — full mobile access to the homelab |
| **Registry** | Zot OCI — self-hosted container images |
| **AI Protocols** | MCP + ACP + A2A — agents talk to tools, services, and each other |
| **Orchestration** | Custom Cast Engine — declarative multi-step workflows in TOML |

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

---

<p align="center">
  <a href="https://securanido.com">securanido.com</a> ·
  <a href="https://www.linkedin.com/in/florian-schulz-a312bb137">LinkedIn</a> ·
  <a href="mailto:fschulz0787@gmail.com">Email</a> ·
  <a href="https://nash87.github.io/infracraft-demos">Live Demos</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nash87&style=flat-square&color=326CE5" alt="Profile views">
</p>
