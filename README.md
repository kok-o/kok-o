<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,100:24292e&height=160&section=header&text=Nurkhan%20Esenbek&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer&descAlignY=60&descSize=16&animation=fadeIn" alt="banner" width="100%" />

<br/><br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;weight=600&amp;size=18&amp;duration=6500&amp;pause=1800&amp;color=388BFD&amp;center=true&amp;vCenter=true&amp;width=950&amp;height=45&amp;repeat=true&amp;lines=Building+AI+developer+tools+and+contributing+to+LLM+training+infrastructure." width="100%" alt="Building AI developer tools and contributing to LLM training infrastructure." />
</a>

<p align="center">
  <a href="https://t.me/k0ko_tg"><img src="https://img.shields.io/badge/Telegram-24292e?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://linkedin.com/in/nurkhan-esenbek"><img src="https://img.shields.io/badge/LinkedIn-24292e?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xOSAzYTIgMiAwIDAgMSAyIDJ2MTRhMiAyIDAgMCAxLTIgMkg1YTIgMiAwIDAgMS0yLTJWNWEyIDIgMCAwIDEgMi0yaDE0bS0uNSAxNS41di01LjNhMy4yNiAzLjI2IDAgMCAwLTMuMjYtMy4yNmMtLjg1IDAtMS44NC41Mi0yLjI4IDEuM3YtMS4xMWgtMi43OXY4LjM3aDIuNzl2LTQuOTNjMC0uNzcuNjItMS40IDEuMzktMS40YTEuNCAxLjQgMCAwIDEgMS40IDEuNHY0LjkzaDIuNzVNNi40NiAxMC45djguMzdIOS4yNVYxMC45SDYuNDZNNy44NiA2LjU1YTEuNjQgMS42NCAwIDEgMCAwIDMuMjggMS42NCAxLjY0IDAgMCAwIDAtMy4yOFoiLz48L3N2Zz4%3D" alt="LinkedIn" /></a>
  <a href="https://nurkhan.space"><img src="https://img.shields.io/badge/Portfolio-24292e?style=flat-square&logo=google-chrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:esenbeknurhan@gmail.com"><img src="https://img.shields.io/badge/Email-24292e?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

### Featured Project

<div align="center">

### <a href="https://github.com/kok-o/contextos-agents"><img src="https://raw.githubusercontent.com/kok-o/kok-o/main/log_k.png" width="34" align="absmiddle" alt="ContextOS logo" /> ContextOS</a>

Version-controlled project rules and agent skills for AI coding tools.

</div>

I build and maintain ContextOS, a deterministic context compiler and policy engine. It generates configuration exports for Gemini, Claude Code, Cursor, Copilot, Aider and Zed.

- **Core:** task-based skill selection, adapter exports, project overrides and configuration drift checks in CI.
- **Distribution:** a published npm CLI with an optional MCP companion (beta, read-only by default).
- **Release verification:** [v2.3.2](https://github.com/kok-o/contextos-agents/releases/tag/v2.3.2) records 542 core and 635 MCP tests, plus production-only installation, upgrade and checkpoint rollback on Windows, Linux and macOS.

**Built with:** JavaScript/TypeScript, Node.js, MCP, GitHub Actions.

[Repository](https://github.com/kok-o/contextos-agents) · [npm](https://www.npmjs.com/package/contextos-agents) · [Release evidence](https://github.com/kok-o/contextos-agents/blob/main/docs/evidence/release-2.3.2.json)

---

### Open-Source Contributions

<div align="center">

### <a href="https://github.com/MakazhanAlpamys/Soup"><img src="https://raw.githubusercontent.com/kok-o/kok-o/main/soup.png" width="34" align="absmiddle" alt="Soup logo" /> Soup</a>

Open-source LLM training, fine-tuning and distillation on PyTorch.

</div>

I contribute fixes and regression coverage to training pipelines, diagnostics and tooling. **40 merged pull requests as of October 5, 2026.** [Browse contributions](https://github.com/MakazhanAlpamys/Soup/pulls?q=is%3Apr+author%3Akok-o).

Selected merged work:

- **SFT packing correctness** ([#1304](https://github.com/MakazhanAlpamys/Soup/pull/1304)): Preserved assistant-only loss masks during sample packing, keeping masked prompt tokens out of the training loss.
- **Distillation diagnostics** ([#1026](https://github.com/MakazhanAlpamys/Soup/pull/1026)): Implemented device-side tracking of persistent non-finite distillation losses with periodic host checks, avoiding per-step host synchronization.
- **Trainer callbacks** ([#1023](https://github.com/MakazhanAlpamys/Soup/pull/1023)): Unified callback argument handling across SFT, DPO, GRPO and other trainers, with schema and regression checks.
- **Reward stress testing** ([#918](https://github.com/MakazhanAlpamys/Soup/pull/918)): Added structure-preserving adversarial families, including `wrapped_junk` and `answer_spray`, to test verifier robustness.
- **Snapshot safety** ([#1492](https://github.com/MakazhanAlpamys/Soup/pull/1492)): Refused directory symlinks and Windows junctions during MCP plan-time snapshots.

**Technologies:** Python, PyTorch, Transformers, TRL.

---

### Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake.svg" />
    <img alt="github-snake" src="https://raw.githubusercontent.com/kok-o/kok-o/output/github-snake-dark.svg" width="100%" />
  </picture>

  <br/>

  ### (⌐■_■)
</div>
