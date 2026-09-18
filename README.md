<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:24292e&height=160&section=header&text=Nurkhan%20Esenbek&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer&descAlignY=60&descSize=16&animation=fadeIn" alt="banner" width="100%" />

<br/><br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=388BFD&center=true&vCenter=true&width=500&lines=Building+AI+Tooling+%26+Systems;Open-Source+Contributor+%40+Soup;Context+Governance+%26+Security;Full-Stack+Developer" alt="Typing SVG" />
</a>

<p align="center">
  <a href="https://t.me/k0ko_tg"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://linkedin.com/in/nurkhan-esenbek"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://nurkhan.space"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:esenbeknurhan@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

### Featured Projects

#### <a href="https://github.com/kok-o/contextos-agents"><img src="https://raw.githubusercontent.com/kok-o/kok-o/main/log_k.png" width="22" align="absmiddle" alt="ContextOS logo" /> ContextOS</a>
Deterministic context compiler and policy engine for AI coding assistants (Gemini, Claude Code, Cursor, Copilot, Aider, Zed).

- Eliminates prompt bloat and context drift by dynamically compiling only task-relevant engineering rules and skills.
- Packaged as [`contextos-agents` v2.0.0](https://www.npmjs.com/package/contextos-agents) on npm with automated CI quality gates and native `node --test` suite.

```bash
npx contextos-agents init
contextos resolve "auth session validation" --files src/auth/session.ts --explain
```

#### <a href="https://github.com/kok-o/Stroq"><img src="https://raw.githubusercontent.com/kok-o/kok-o/main/stroq_logo.svg" width="22" align="absmiddle" alt="Stroq logo" /> Stroq</a>
Local action firewall and runtime policy engine for AI coding agents.

- Scans files and tool inputs an agent reads, tracks taint propagation across the session, and blocks dangerous follow-up actions.
- Enforces fail-closed security guarantees against prompt injection, unverified tool execution, and supply-chain drift.

---

### Open-Source Contributions

#### [MakazhanAlpamys/Soup](https://github.com/MakazhanAlpamys/Soup)
Open-source library for training, fine-tuning, and distillation of LLMs on PyTorch (26 author Pull Requests):

- **GPU/Host Async Optimization** ([PR #1026](https://github.com/MakazhanAlpamys/Soup/pull/1026)): Implemented `DistillNonfiniteTracker` to catch non-finite teacher logits on GPU tensors without device-to-host synchronization (`.item()`), preventing throughput stalls during distillation.
- **Unified Callback Architecture** ([PR #1023](https://github.com/MakazhanAlpamys/Soup/pull/1023)): Unified callback parameter extraction (`soup_callback_kwargs`) across all 16 trainers (`sft`, `grpo`, `dpo`, `ppo`, `distill`, etc.), adding schema gating and AST validation tests.
- **RLHF Reward Hacking Stress Tests** ([PR #918](https://github.com/MakazhanAlpamys/Soup/pull/918)): Added structure-preserving adversarial attack families (`wrapped_junk`, `answer_spray`) to evaluate verifier robustness against reward gaming in reasoning models.
- **Cross-Platform Security & CI Gates** ([PR #1024](https://github.com/MakazhanAlpamys/Soup/pull/1024), [PR #921](https://github.com/MakazhanAlpamys/Soup/pull/921)): Hardened Windows symlink and TOCTOU defense in draft registries and unified CLI exit code taxonomy (0/2/3) across evaluation gate commands.

---

### Tech Stack

<div align="center">

**AI & Systems**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<br/>

**Frontend & Web**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

<br/>

**Backend, Data & Tooling**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

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

### Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" width="100%" />
  </picture>
</div>
