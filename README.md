# Stanislav Gonorovskii

19 years across full-stack and AI/ML, based in Dubai.
I build the plumbing under LLM-powered products — agent runtimes, trading systems, media pipelines.

**Python, Rust, TypeScript, C/C++.**
*LLM agent infrastructure · RAG systems · gRPC services · trading automation · GenAI media pipelines.*

[LinkedIn](https://linkedin.com/in/gonorovsky) · [sgon.ai](https://sgon.ai)


## Projects

### [orno](https://github.com/DoctorMozg/orno) — terraform plan, but for agents
LLM agents fail silently and expensively. You learn what they did after they did it. *orno* pins a typed contract at runtime, so you read the plan, diff it, and reject it if it lies. Event-sourced, so replay and audit aren't a separate project. Built for CI from day one.
`Rust` `GitHub Actions` `LLM Agents` `Event Sourcing`

### [kavzi-trader](https://github.com/DoctorMozg/kavzi-trader) — three agents walk into a futures market
Binance Futures automation on a Brain-Spine multi-agent setup. **Scout** scans, **Analyst** validates, **Trader** executes. Tiered LLM routing puts cheap models on the hot path and saves the expensive ones for decisions that actually move money. Every fill is event-sourced — no fill exists without a record of why it happened.
`Python` `Pydantic-AI` `Binance API` `LLM Routing`

### [claude-pipelines](https://github.com/DoctorMozg/claude-pipelines) — agents all the way down
A plugin system for *Claude Code*: reusable multi-agent pipelines, skills, and hooks for day-to-day engineering work. The pipeline is built with agents and runs agents. Either elegant or a war crime, depending on the day.
`Shell` `Python` `Claude Code` `MCP`

### [cartoon-genai](https://github.com/DoctorMozg/cartoon-genai) — a studio that fits on one GPU
End-to-end generative media on one workstation. *FLUX.1* draws stills, *Wan2.2* handles motion, *ElevenLabs* does voice, *MusicGen* writes the score, *Claude* writes the script. 9:16 video out, no render farm in.
`Python` `FLUX.1` `ElevenLabs` `MusicGen` `Claude`


## Work

Earlier roles spanned full-stack systems, AI infrastructure, and voice/speech platforms. Same job, different stack each time: build the boring layer correctly so the product team above it can move fast.

**Currently** — shipping my own products at [sgon.ai](https://sgon.ai).

## Tech

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Rust" src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="C++" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white">
  <img alt="Qdrant" src="https://img.shields.io/badge/Qdrant-24386C?style=flat-square&logo=qdrant&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
  <img alt="Anthropic" src="https://img.shields.io/badge/Anthropic-D4A017?style=flat-square&logo=anthropic&logoColor=white">
</p>

---

📬 Building something in AI and want to compare notes? → [sgon.ai](https://sgon.ai) or drmozg@gmail.com
