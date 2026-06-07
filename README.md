# 👋 Hi, I'm Lê Văn Tâm

<p align="center">
  <strong>AI Agent Developer | Autonomous Systems | Developer Tools</strong>
  <br>
  Building intelligent solutions that enhance developer productivity
</p>

---

## 🎯 About Me

I'm passionate about creating **AI-powered autonomous agents** and intelligent developer tools that transform how teams write, review, and manage code. My work focuses on bridging the gap between cutting-edge AI technology and practical developer needs.

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Claude%20API-000000?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
  <img src="https://img.shields.io/badge/AI%20Agents-FF6B6B?style=for-the-badge" alt="AI Agents" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
</p>

---

## 🚀 Featured Projects

<details>
<summary><strong>1. 🤖 <a href="https://github.com/LVT382009/mizumi">Mizumi</a> - Self-Learning PR Review Agent</strong></summary>

<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

GitHub Action that reviews pull requests using AI, learns from past reviews, and posts actionable findings — with deterministic rules that never hallucinate.

**Key Features:**
- ✅ BYOK from day 1 (Anthropic, OpenAI, Google, NVIDIA NIM, OpenRouter, or any OpenAI-compatible endpoint)
- ✅ Self-learning via repository memory
- ✅ Deterministic rules (catches hardcoded secrets, missing auth, SQL injection WITHOUT LLM calls)
- ✅ Two-pass review (LLM review + self-critique on cheaper model)
- ✅ Prompt injection defense framework (first AI code review tool with explicit defense architecture)
- ✅ Confidence calibration & auto-fix on 👍 reaction
- ✅ CI-validated fix loop (apply → poll → revert on failure)
- ✅ AST cross-file contract analysis

</details>

<details>
<summary><strong>2. 🧠 <a href="https://github.com/LVT382009/hermes-rate-limiter-plugin">Hermes Rate Limiter Plugin</a> - Smart Rate Limiting</strong></summary>

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Cross-session rate limit guard for Hermes Agent side clients that **prevents retry amplification when rate limits are hit.**

**Problem Solved:**
Each 429 error triggers up to 9 API calls (3 SDK retries × 3 Hermes retries). This plugin records rate limit state on first 429 and checks it before subsequent attempts across all sessions.

**Key Features:**
- ✅ Cross-session tracking with shared state file
- ✅ Retry amplification prevention
- ✅ Runtime controls via slash commands (`/ratelimit status`, `/ratelimit clear`, etc.)
- ✅ Thread-safe atomic writes
- ✅ Reset time parsing (x-ratelimit headers, retry-after, default cooldown)

</details>

<details>
<summary><strong>3. 💾 <a href="https://github.com/LVT382009/noxem">Noxem</a> - AI Memory System for Hermes</strong></summary>

<br>

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![14 Stars](https://img.shields.io/github/stars/LVT382009/noxem?style=flat-square&color=yellow&label=⭐)

Two-brain AI memory system with **hybrid semantic search (vector KNN + FTS5)** and optional advisor brain via QwenProxy or local LLM.

**Brain 1 — Semantic Engine:**
- Hybrid search with Reciprocal Rank Fusion
- Auto-categorization (12+ tags)
- Smart deduplication (cosine >0.92)
- Conflict resolution & contextual enrichment
- Spaced repetition & importance scoring
- Provenance graph tracking

**Brain 2 — Reasoning Engine (optional):**
- Cloud (QwenProxy) or local (Ollama, LM Studio, llama.cpp)
- Drift detection & context recovery
- Background web research via DuckDuckGo
- Session extraction & consolidation
- OpenAI-compatible API on port 8000

</details>

---

## 🎯 Current Focus

- 🔭 **Exploring:** Advanced AI agent architectures and intelligent memory systems
- 🌱 **Learning:** Defense mechanisms, prompt injection mitigation, and security best practices
- 💡 **Building:** Next-generation autonomous development tools and AI agents
- 🤝 **Contributing:** To open-source AI ecosystems

---

## 🤝 Connect With Me

<p align="center">
  <a href="mailto:levantam.98.2324@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/LVT382009">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

## 💬 Let's Collaborate!

I'm always excited to collaborate on:
- 🤖 AI agent development and memory systems
- 🛠️ Developer tools and productivity solutions
- 🔐 AI safety, security, and defense mechanisms
- 🌟 Open-source projects

**Feel free to:**
- ⭐ Star projects you find interesting
- 🐛 Report issues and suggest improvements
- 🤝 Submit pull requests
- 💌 Reach out with ideas and feedback

---

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=LVT382009" alt="Visitor Badge" />
  <br><br>
  <strong>Let's build the future of AI-powered development together! 🚀</strong>
</p>
