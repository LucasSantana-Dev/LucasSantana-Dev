<h1 align="center">Hi, I'm Lucas (Luk)</h1>
<h3 align="center">Senior Software Engineer · Backend-focused Full-Stack · AI agent tooling and evals · Node.js · TypeScript · Python</h3>
<p align="center">
  Currently at <a href="https://www.thoughtworks.com/">Thoughtworks</a> (remote from Brazil, UTC-3) · 5+ years shipping cloud-native systems for international clients.
</p>

<p align="center">
  <a href="https://lucassantana.tech"><img src="https://img.shields.io/badge/Portfolio-lucassantana.tech-000000?style=flat-square&logo=cloudflare&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/devlucassantana/"><img src="https://img.shields.io/badge/LinkedIn-devlucassantana-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:lucas.diassantana@gmail.com"><img src="https://img.shields.io/badge/Email-lucas.diassantana%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://pypi.org/project/hitgate"><img src="https://img.shields.io/pypi/v/hitgate?style=flat-square&logo=pypi&logoColor=white&label=PyPI" alt="hitgate on PyPI"/></a>
  <img src="https://img.shields.io/badge/English-C1-2b9348?style=flat-square" alt="English C1"/>
</p>

---

## What I do

I build backend-focused full-stack systems for a living and tools for AI coding agents on the side. I care about measuring those tools: retrieval quality in hitgate, and which tools an agent actually gets in decision-critic.

Day job is senior consulting at Thoughtworks (previously CI&T), on international teams with strict review cultures. Off-hours I run a homelab and a self-hosted Discord bot, and I publish developer tooling on npm and PyPI.

- [decision-critic](https://github.com/LucasSantana-Dev/decision-critic): a runtime probe showed a Claude Code denylist left 91 MCP tools in place, including one that runs shell commands. The empty allow-list resolved to 0.
- [hitgate](https://github.com/LucasSantana-Dev/hitgate): hybrid retrieval reaches Hit@5 0.99 on a 99-case benchmark (BM25 alone: 0.91), with a label-free evaluation gate in CI.
- Backend for a global consumer brand's mobile app and personalization platform (Node.js, AWS Lambda).
- [Lucky](https://github.com/LucasSantana-Dev/Lucky): staging and production deploys, a migration gate and mutation testing.

---

## Featured projects

| Project | What it does | Stack | |
|---------|--------------|-------|---|
| [**decision-critic**](https://github.com/LucasSantana-Dev/decision-critic) | A reviewer agent with no tools, on purpose. Portable spec, Claude Code adapter, and a probe that checks what the host actually resolves | Node.js · Claude Code | [![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](https://github.com/LucasSantana-Dev/decision-critic/blob/main/LICENSE) |
| [**hitgate**](https://github.com/LucasSantana-Dev/hitgate) | Hybrid RAG evaluation harness: BM25 + dense + RRF retrieval, label-free eval, CI-ready | Python · Sentence Transformers · BM25 | [![PyPI](https://img.shields.io/pypi/v/hitgate?style=flat-square&logo=pypi)](https://pypi.org/project/hitgate) |
| [**Lucky**](https://github.com/LucasSantana-Dev/Lucky) | Self-hosted Discord music bot: Spotify stats, autoplay recommendations, React dashboard, moderation suite | TypeScript · Prisma · Discord.js | [![CI](https://github.com/LucasSantana-Dev/Lucky/actions/workflows/ci.yml/badge.svg)](https://github.com/LucasSantana-Dev/Lucky/actions) |
| [**homelab**](https://github.com/LucasSantana-Dev/homelab) | Self-hosted infra: Docker Compose, Caddy, Tailscale, Prometheus/Grafana, SOPS | Python · Bash · Docker | [![CI](https://github.com/LucasSantana-Dev/homelab/actions/workflows/ci.yml/badge.svg)](https://github.com/LucasSantana-Dev/homelab/actions) |
| [**sharekit**](https://github.com/LucasSantana-Dev/sharekit) | Share your AI coding setup (CLAUDE.md, skills, cursorrules) with one command: `npx @lucassantana/sharekit install lucassantana` | Node.js · CLI | [![npm](https://img.shields.io/npm/v/@lucassantana/sharekit?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@lucassantana/sharekit) |

_Additional private repos (finance tools, infra dashboards) available on request._

---

## Tech stack

**Backend and cloud:** Node.js · TypeScript · Python · Express · AWS (Lambda, S3, API Gateway, SSM, CloudWatch, EventBridge) · PostgreSQL · Redis · Prisma · Docker · Cloudflare Workers and Pages · Serverless Framework

**AI agents:** Claude Code (subagents, hooks, skills) · MCP servers · RAG retrieval and evaluation

**Frontend:** React · Next.js · Tailwind CSS · Material UI

**DevOps and observability:** GitHub Actions · Jenkins · Jest · Mocha · Grafana · Splunk · Kubernetes (k3s) · SOPS/age · Tailscale · Caddy · Linux

---

## Certifications and education

- **AWS Certified Cloud Practitioner**
- Bachelor's in Computer Systems, [FIAP](https://www.fiap.com.br/) (2025)

---

## Open to

- Open-source collaboration on AI agent tooling, evals, or observability
- Architecture and system-design discussions. Happy to review or pair

**Get in touch:** [lucas.diassantana@gmail.com](mailto:lucas.diassantana@gmail.com) · [LinkedIn](https://www.linkedin.com/in/devlucassantana/)

---

## GitHub stats

<p align="center">
  <a href="https://github.com/stats-organization/github-stats-extended"><img height="160" src="https://raw.githubusercontent.com/LucasSantana-Dev/LucasSantana-Dev/cards/stats.svg" alt="GitHub stats"/></a>
  <a href="https://github.com/stats-organization/github-stats-extended"><img height="160" src="https://raw.githubusercontent.com/LucasSantana-Dev/LucasSantana-Dev/cards/top-langs.svg" alt="Top languages"/></a>
</p>
