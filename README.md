<!-- PROFILE README — renders at github.com/joeblackwaslike -->
<!-- Palette matched to joeblack.nyc: base #0a0c0d · teal #15808a · cyan #45e1ed · ink #e6ecf0 -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0c0d,45:15808a,100:45e1ed&height=200&section=header&text=Joe%20Black&fontColor=e6ecf0&fontSize=64&fontAlignY=38&desc=Backend%20engineer%20%C2%B7%20building%20at%20the%20frontier%20of%20AI%20agents&descAlignY=60&descSize=18" alt="Joe Black" width="100%" />

<a href="https://joeblack.nyc">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=22&pause=1000&color=15808A&center=true&vCenter=true&width=820&lines=Senior+Backend+Engineer+%E2%80%94+10%2B+years+in+production;Building+the+dev+tools+that+make+AI+agents+useful;Python+%C2%B7+TypeScript+%C2%B7+Rust+%C2%B7+MCP+%C2%B7+LangGraph;Scaled+an+SDK+to+millions+%C2%B7+shipped+WaaS+to+~%243M+ARR" alt="What I do" />
</a>

<br/>

[![Website](https://img.shields.io/badge/joeblack.nyc-15808A?style=flat-square&logo=firefoxbrowser&logoColor=white&labelColor=0a0c0d)](https://joeblack.nyc) [![Email](https://img.shields.io/badge/me@joeblack.nyc-0f626a?style=flat-square&logo=maildotru&logoColor=white&labelColor=0a0c0d)](mailto:me@joeblack.nyc) [![X](https://img.shields.io/badge/@joeblackwaslike-0a0c0d?style=flat-square&logo=x&logoColor=45e1ed)](https://x.com/joeblackwaslike) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0a0c0d)](https://www.linkedin.com/in/joeblack949)

</div>

---

I build **backend systems** and the **developer tools that make AI agents genuinely useful**. Ten-plus years shipping production Python and TypeScript — I scaled the **Magic Labs SDK to millions of users**, built an **OIDC/JWT Wallet-as-a-Service to ~$3M ARR**, and helped build the **CNN Magic Wall** for the 2020 US election. These days I'm heads-down on **agent infrastructure**: MCP servers, context engineering, autonomous code-review, and the connective tissue that makes coding agents faster, cheaper, more reliable, safer, and more autonomous.

> Most of what's below is a body of work I've been building **deliberately rather than marketing** — substance first, launch later. Based in New York City.

<div align="center">

`Backend` · `AI / Agent Infrastructure` · `MCP & Tooling` · `Async Python` · `TypeScript` · `Rust`

</div>

## 🤖 Featured — AI &amp; Agent Infrastructure

> The frontier work: making coding agents faster, cheaper, and less forgetful.

| Project | What it does |
| --- | --- |
| **[lessons-learned](https://github.com/joeblackwaslike/lessons-learned)** | Captures coding mistakes and injects the relevant lesson *before* the next tool call — with a built-in **eval framework** that proves which lessons actually work and **auto-prunes** the ones that don't. |
| **[mcp-exec](https://github.com/joeblackwaslike/mcp-exec)** | **Reference implementation** of Anthropic's [*Code execution with MCP*](https://www.anthropic.com/engineering/code-execution-with-mcp) (Nov 2025). Reuses Claude Code's **own sandbox and config** — so isolation comes **free** — and keeps intermediate tool output **out of the context window entirely**, on *every* workflow, not just multi-tool ones. Up to **99% fewer tokens**. |
| **[ai-review-bot](https://github.com/joeblackwaslike/ai-review-bot)** | Autonomous multi-agent PR reviewer. **Waits for every other review bot to finish and indexes their findings to avoid duplication**, then dispatches **5+ specialized sub-agents** (scaled to the PR) to review and suggest. The full **review → re-review → approval** loop runs end-to-end, with QA gates and a feedback loop that folds in reviewer remarks and **self-improves** over time. |
| **[ctx-tree](https://github.com/joeblackwaslike/ctx-tree)** | Tree/graph-based persistent context store for long-running agent sessions. Pairs with **mcp-exec** to keep raw output *out* of the window — returns **identifiers, snippets, and hints** instead of full payloads, so the agent pulls exactly what it needs and works far longer before context fills. |
| **[idiomatic](https://github.com/joeblackwaslike/idiomatic)** | Language-agnostic idiom-enforcement gate for AI agents *and* humans — Rust core, **sub-100ms autofix**, Python + Node bindings. |
| **[ai-listings](https://github.com/joeblackwaslike/ai-listings)** | AI-powered product-listing generation tool. |
| **[agent-skills](https://github.com/joeblackwaslike/agent-skills)** | A large, growing library of agent skills for Claude Code &amp; Codex — spanning Git/GitHub/Actions, Vercel, Serena, Dolt, DDD &amp; SOLID, cross-platform plugin development, docs tooling, and agentic best-practices. Every skill **auto-updates weekly** from upstream docs to stay current. |
| **[cc-recall](https://github.com/joeblackwaslike/cc-recall)** | Discoverability + enrichment for Claude Code session transcripts — **fixes a Claude Code bug that leaves ~90% of sessions undiscoverable**, so past work can actually be found and reused. |
| **[agent-marketplace](https://github.com/joeblackwaslike/agent-marketplace)** | My curated marketplace &amp; storefront — where I publish, version, and showcase every plugin, skill, and tool I ship for Claude Code &amp; Codex CLI. Also home to the **idea-nursery**, where nascent macOS tools &amp; automations incubate before earning their own repo. |
| **[anti-compact](https://github.com/joeblackwaslike/anti-compact)** | **Intercepts automatic compaction and halts it**, generating a structured session handoff instead of lossy compression. |
| **[edgelite](https://github.com/joeblackwaslike/edgelite)** | EdgeDB-style developer experience on PGlite — SDL schema, typed TS query builder, migration CLI. |
| **[cc-vscode-ext](https://github.com/joeblackwaslike/cc-vscode-ext)** | A clean, documented **reimplementation of the Claude Code VS Code extension** — reverse-engineered, with a number of **improvements** over the original. |
| **[pieces-dev](https://github.com/joeblackwaslike/pieces-dev)** | pnpm monorepo of PiecesOS developer tools — a monitoring platform (daemon + SDK + CLI + editor extensions), an LTM context injector for VS Code, and gap-reconstruct. |
| **[agent-improvement](https://github.com/joeblackwaslike/agent-improvement)** | Centralized hub for Claude/agent workflow improvements — improvement plans (AIPs), hooks, and tooling. |

## ⚙️ Backend &amp; API Engineering

Async-first Python and framework-level tooling. FastAPI + SQLModel for CRUD; DDD/CQRS for the complex stuff.

- **[quart-sqlalchemy](https://github.com/joeblackwaslike/quart-sqlalchemy)** ⭐ — Production async SQLAlchemy integration for Quart.
- **[python-banshee](https://github.com/joeblackwaslike/python-banshee)** — My port of **Banshee**: a command dispatcher &amp; message bus (Commands / Queries / Events / Handlers) for CQRS-style Python services.
- **[pricing](https://github.com/joeblackwaslike/pricing)** — Locale-aware, CLDR-backed pricing, currency formatting &amp; exchange.
- **[quart-depends](https://github.com/joeblackwaslike/quart-depends)** · **[python-quart-injector](https://github.com/joeblackwaslike/python-quart-injector)** — FastAPI-style dependency injection for Quart.
- **[redis-bloom-ttl](https://github.com/joeblackwaslike/redis-bloom-ttl)** — Rust Redis module: a bloom filter with per-entry TTL.
- **[hashidtools](https://github.com/joeblackwaslike/hashidtools)** — Async hash-ID generation components.

## ⛓️ Web3 &amp; Crypto

Former Web3 technical co-founder; built wallet infrastructure and the primitives underneath it.

- **[coinaddr](https://github.com/joeblackwaslike/coinaddr)** ⭐ — Cryptocurrency address inspection &amp; validation for Python.
- **[btcpay-python](https://github.com/btcpayserver/btcpay-python)** ⭐ — The **first &amp; canonical Python SDK** for BTCPay Server, adopted into the official BTCPayServer org.
- **[base58check](https://github.com/joeblackwaslike/base58check)** ⭐ — Base58Check encoding/decoding.
- **[docker-geth](https://github.com/joeblackwaslike/docker-geth)** — Dockerized Geth + Swarm (Ethereum) node wrappers.

## 🧰 Developer Experience &amp; Tooling

- **[spinup-ts](https://github.com/joeblackwaslike/spinup-ts)** · **[spinup-py](https://github.com/joeblackwaslike/spinup-py)** — Opinionated, **very strict** project scaffolds that bake my agentic-development best practices into each language (extensive linters + code-quality gates). Using one **forces the AI to write better, more maintainable code that needs less review** (Biome/Vitest/Husky · uv/ruff/wps).
- **[safaribooks](https://github.com/joeblackwaslike/safaribooks)** — Revived a defunct fork: rebuilt on O'Reilly's current APIs + cookie auth, made it async, and published it to PyPI (`safaribookshelf`). Beyond EPUB, it now exports **agent-ready Markdown** built to be consumed by AI agents or dropped straight into skills.
- **[resume-builder](https://github.com/joeblackwaslike/resume-builder)** ⭐ — Dynamic LaTeX résumé pipeline from a JSON Resume schema.
- **[jobsearch-tracker](https://github.com/joeblackwaslike/jobsearch-tracker)** — Personal job-search pipeline tracker.
- **[ext-tool](https://github.com/joeblackwaslike/ext-tool)** — Manage VS Code / Cursor extensions from one source-of-truth TOML registry.
- **[gstack](https://github.com/joeblackwaslike/gstack)** — Forked the original and wrapped it as a **Claude Code plugin**, making the 23-tool setup far easier to install and use.
- **[tmpld](https://github.com/joeblackwaslike/tmpld)** — Jinja2 templating on steroids for Docker containers.
- **[dcgoss](https://github.com/joeblackwaslike/dcgoss)** — `dgoss` variant driven by docker-compose files.
- **[testdocker](https://github.com/joeblackwaslike/testdocker)** — Unit testing for Docker containers.
- **[devcontainer](https://github.com/joeblackwaslike/devcontainer)** — Reusable dev-container configurations.
- **[gpgkeyring](https://github.com/joeblackwaslike/gpgkeyring)** — Programmatic GPG keyring management.
- **[cookiecutter-ds](https://github.com/joeblackwaslike/cookiecutter-ds)** — Cookiecutter template for Python data-science projects.

<details>
<summary><b>☸️ Cloud-native &amp; Kubernetes — deeper systems catalog (2016–2020)</b></summary>

<br/>

- **[kubed](https://github.com/joeblackwaslike/kubed)** — An opinionated, human-friendly Kubernetes client.
- **[pycaps](https://github.com/joeblackwaslike/pycaps)** ⭐ — Linux capabilities for Python.
- **[overridehostname](https://github.com/joeblackwaslike/overridehostname)** ⭐ — `gethostname(2)` interposer.
- **[docker-couchdb](https://github.com/joeblackwaslike/docker-couchdb)** ⭐ — Dockerized CouchDB 2.0.
- **[couchdiscover](https://github.com/joeblackwaslike/couchdiscover)** — CouchDB 2.0 autodiscovery on Kubernetes.
- **[rpi-cluster-bootstrap](https://github.com/joeblackwaslike/rpi-cluster-bootstrap)** — Bootstrap for a Raspberry Pi k3s cluster.
- **[kubewait](https://github.com/joeblackwaslike/kubewait)** — Init container that pauses startup until dependencies are ready.
- **[pyrkube](https://github.com/joeblackwaslike/pyrkube)** — Read-only `pykube` wrapper tuned for a different focus.
- **[kube-ssl](https://github.com/joeblackwaslike/kube-ssl)** — Kubernetes TLS helpers.
- **[k8s-kernel](https://github.com/joeblackwaslike/k8s-kernel)** — Kubernetes-optimized Linux kernel.
- **[container-utils](https://github.com/joeblackwaslike/container-utils)** — Shell utilities for containers.
- **[debian](https://github.com/joeblackwaslike/debian)** — Minimal Debian for containers with Kubernetes extras.

</details>

<details>
<summary><b>🔩 Hardware, home automation &amp; earlier work</b></summary>

<br/>

- **[homepod-update](https://github.com/joeblackwaslike/homepod-update)** — Turns a **jailbroken 1st-gen HomePod** into a bidirectional voice satellite — swap Siri for **Claude / GPT / any LLM** via Home Assistant or an OpenClaw cluster. A `mediaserverd` tweak streams beam-formed mic audio (Wyoming protocol), with a Go management dashboard — enabled by a checkm8 jailbreak + a custom pogo-pin USB dock adapter.
- **[luxafor](https://github.com/joeblackwaslike/luxafor)** — Python driver + internet-health monitor for the Luxafor Flag USB HID device.
- **[brca-crawler](https://github.com/joeblackwaslike/brca-crawler)** — Scrapy-based crawler that harvests county property-parcel records into structured data.
- **[video-pro](https://github.com/joeblackwaslike/video-pro)** — Application for managing video content at scale.
- **[lifx-demo](https://github.com/joeblackwaslike/lifx-demo)** — LIFX Wi-Fi LED control demo (Ruby).

</details>

## 🛠️ Tech I reach for

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-0a0c0d?style=flat-square&logo=rust&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-15808A?style=flat-square&logo=langchain&logoColor=white) ![Anthropic](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-0a0c0d?style=flat-square&logo=modelcontextprotocol&logoColor=45e1ed) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

## 📊 GitHub

<div align="center">

<img height="165" src="https://github-readme-stats-taupe-psi-61.vercel.app/api?username=joeblackwaslike&show_icons=true&count_private=true&hide_border=true&bg_color=0a0c0d&title_color=45e1ed&icon_color=15808a&text_color=e6ecf0" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats-taupe-psi-61.vercel.app/api/top-langs/?username=joeblackwaslike&layout=compact&langs_count=8&hide_border=true&bg_color=0a0c0d&title_color=45e1ed&text_color=e6ecf0" alt="Top languages" />

</div>

---

<div align="center">

**Open to senior backend &amp; AI-infrastructure roles, custom AI development &amp; consulting engagements — and collaborators at the frontier.**

📫 [me@joeblack.nyc](mailto:me@joeblack.nyc) · 🌐 [joeblack.nyc](https://joeblack.nyc) · 𝕏 [@joeblackwaslike](https://x.com/joeblackwaslike)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:45e1ed,55:15808a,100:0a0c0d&height=120&section=footer" alt="" width="100%" />

</div>

