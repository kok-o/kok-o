# Nurkhan Esenbek

Software Engineer • Python, TypeScript, Node.js • AI Tooling & Systems

[LinkedIn](https://linkedin.com/in/nurkhan-esenbek) • [Telegram](https://t.me/k0ko_tg) • [Portfolio](https://nurkhan.space) • [Email](mailto:esenbeknurhan@gmail.com)

---

### Open-Source Contributions

#### [MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup)
Open-source library for training, fine-tuning, and distillation of LLMs on PyTorch (26 author Pull Requests):

- **GPU/Host Async Optimization** ([PR #1026](https://github.com/MakazhanAlpamys/Soup/pull/1026)): Implemented `DistillNonfiniteTracker` to catch non-finite teacher logits directly on GPU tensors without device-to-host synchronization (`.item()`), preventing training throughput stalls.
- **Unified Callback Architecture** ([PR #1023](https://github.com/MakazhanAlpamys/Soup/pull/1023)): Unified callback parameter extraction (`soup_callback_kwargs`) across all 16 trainers (`sft`, `grpo`, `dpo`, `ppo`, `distill`, etc.), adding schema gating and AST validation tests.
- **RLHF Reward Hacking Stress Tests** ([PR #918](https://github.com/MakazhanAlpamys/Soup/pull/918)): Added structure-preserving adversarial attack families (`wrapped_junk`, `answer_spray`) to evaluate verifier robustness against reward gaming in reasoning models.
- **Cross-Platform Security & CI Gates** ([PR #1024](https://github.com/MakazhanAlpamys/Soup/pull/1024), [PR #921](https://github.com/MakazhanAlpamys/Soup/pull/921)): Hardened Windows symlink and TOCTOU defense in draft registries and unified CLI exit code taxonomy (0/2/3) across evaluation gate commands.

---

### Featured Project

#### [ContextOS](https://github.com/kok-o/contextos-agents)
Deterministic context compiler and policy engine for AI coding assistants (Gemini, Claude Code, Cursor, Copilot, Aider, Zed).

- **Core Problem**: Monolithic prompt rules cause token overflow, context drift, and instruction conflicts across different IDEs and developer workflows.
- **Architecture**: Dynamic skill resolution engine based on graph dependencies, multi-agent configuration compiler, and automated CI quality gates.
- **Engineering Quality**: Published npm package ([`contextos-agents` v2.0.0](https://www.npmjs.com/package/contextos-agents)), comprehensive test suite running on Node.js native test runner (`node --test`), pre-flight diagnostic system (`contextos doctor`).
- **Quick Start**:
  ```bash
  npx contextos-agents init
  contextos resolve "auth session validation" --files src/auth/session.ts --explain
  ```

---

### Experience

#### AlanaTechGroup - Junior Frontend Developer
*Jan 2026 - May 2026 (5 mos) • Astana, Kazakhstan (Hybrid)*
- Developed responsive web interfaces and dashboards for the company's real-time GPS tracking platform using React and TypeScript.
- Integrated frontend modules with backend REST APIs and implemented live telemetry and tracking updates.
- Collaborated with engineering team on feature development, debugging, and production releases.

#### iQadam Systems - Web Developer Intern
*Sep 2025 - Nov 2025 (3 mos) • Astana, Kazakhstan (On-site)*
- Built responsive web applications and modular UI components using React, Next.js, TypeScript, and Tailwind CSS.
- Integrated backend REST APIs and optimized client-side rendering performance.
- [Internship Certificate](https://github.com/kok-o/kok-o/blob/main/iqadam_certificate.jpg)

#### SpaceLab LTD - Assistant Programmer / Web Designer
*May 2025 - Jun 2025 (2 mos) • Astana, Kazakhstan (Remote)*
- Designed interactive UI prototypes, wireframes, and design systems in Figma.
- Prepared UI specifications and layout assets for frontend implementation.

---

### Education

- **Astana IT College**, Astana - Software Engineering

---

### Tech Stack

- **Languages**: Python, TypeScript, JavaScript, SQL, HTML/CSS
- **AI & Systems**: PyTorch, LLM Training & Fine-Tuning (SFT, DPO, PPO, Distillation), Context Governance
- **Frontend & Web**: React, Next.js, Tailwind CSS, WebSockets, REST APIs
- **Tooling & Infrastructure**: Node.js, Git, GitHub Actions, Docker, Linux, Windows APIs

---

### Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" width="100%" />
  </picture>
</div>
