<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=220&section=header&text=Elyse%20Messer&fontSize=64&fontColor=ffffff&animation=fadeIn&desc=Senior%20AI%20Engineer%20%C2%B7%20Elcano&descSize=24&descAlignY=78" width="100%" alt="Elyse Messer — Senior AI Engineer at Elcano" />
</div>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=F472B6&center=true&vCenter=true&width=640&lines=Building+AI+agents+for+programmatic+AdTech;MCP+servers+%C2%B7+agentic+workflows+%C2%B7+design+systems;From+pixels+(2017)+to+autonomous+agents+(2026);Complex+%E2%89%A0+complicated" alt="Typing animation" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/elysemesser" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-elysemesser-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/elysemesser" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-elysemesser-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=elysemesser&color=ff69b4&style=for-the-badge" />
</p>

---

## ✨ About Me

> **Complex ≠ complicated.**

I started as a **frontend developer in 2017**, obsessing over pixels, accessibility, and the feel of a well-crafted interface. That obsession evolved: from building UIs that make dense data usable, to building **AI agents that do the dense work themselves** — and designing the interfaces, protocols, and guardrails that make them trustworthy.

Today I'm a **Senior AI Engineer at Elcano**, where I architect the full pipeline that turns a plain-English deal brief into live programmatic deals across the AdTech ecosystem — autonomous agents, MCP servers, audit engines, and the human-facing tools that keep people confidently in the loop.

```text
2017 ──────── 2019 ─────────────── 2024 ─────────────── 2026
Frontend      Senior Frontend      AI Engineer          Senior AI Engineer
Developer     Developer            Elcano               Elcano
              Rightpoint
└── pixels ──→ design systems ──→ AI agents ──→ agentic platforms ──┘
```

---

## 🚀 What I've Been Building Lately

### 🗡️ Cutlass — AI Agent for Programmatic AdTech
The autonomous agent at the heart of Elcano's platform: a **Go-based AI agent** driving a fleet of **Python MCP (Model Context Protocol) servers** that I architected and maintain. It creates, targets, and reports on PMP deals across **Index Exchange, OpenX, Magnite, Xandr, TripleLift, Media.net, PubMatic, and Adverity** — absorbing each SSP's quirks (enum casing, exclusive date ranges, inventory-targeting models, regulatory policy flags) so traders never have to.

### 📋 Manifest — Deal Intake, Audited & Agent-Ready
A full-stack platform (**Go + Chi · React 18 + Vite + TypeScript**) that replaces manual deal intake with a structured, SSP-aware form, a **client-aware audit engine**, and a prompt generator that emits **MCP-tool-call-ready YAML** — so the agent gets it right on the first try, every try. Includes a conversational **deal-chat** interface for editing deals in plain English.

### 🔬 Elcano Lens — Resilient LLM Classification
An LLM-powered classification pipeline built on **OpenRouter** with **cross-provider model fallback chains** — hardened response parsing, provider-error detection, and automatic failover so one flaky model never takes down the pipeline.

### 🔐 Unified Auth — One Login for the Whole Suite
A central **magic-link auth service** minting **Ed25519-signed**, domain-wide session cookies, with two integration tiers (edge `forward_auth` and native in-app verification with scoped membership). I wired it across the product suite — stateless CSRF checks, fail-closed verification, clean logout semantics.

### 🚩 Flag — Design System at Scale
Elcano's design system: shared tokens, components, and **bulletproof HTML email templates** (dark-mode QA harness, fixtures, template guardrails). I led the rollout that brought every app in the suite — login flows, dashboards, iconography — into one coherent, accessible visual language.

<details>
  <summary><b>🗺️ How it all fits together</b></summary>

```mermaid
flowchart LR
    T(["🧑‍💼 Trader brief"]) --> M["📋 Manifest<br/>intake · audit · prompt gen"]
    M -- "MCP-ready YAML" --> A["🗡️ Cutlass Agent<br/>(Go)"]
    A --> S{{"🐍 Python MCP servers"}}
    S --> IX["Index Exchange"]
    S --> OX["OpenX"]
    S --> XA["Xandr"]
    S --> TL["TripleLift"]
    S --> PM["PubMatic"]
    S --> MN["Media.net"]
    AU["🔐 Unified Auth"] -.protects.-> M
    FL["🚩 Flag Design System"] -.styles.-> M
```

</details>

<details>
  <summary><b>💼 Earlier Experience</b></summary>
  <ul>
    <li><b>Rightpoint</b> — Senior Frontend Developer (2019 → 2024): secure React Native app for a government client; e-commerce design system (Next.js, TypeScript, MUI); modern SharePoint UIs (React, Storybook)</li>
    <li><b>Bread Factory Studios</b> — Frontend Developer (2017 → 2019)</li>
    <li><b>LevelEleven</b> — Frontend UI/UX (2017 → 2019)</li>
  </ul>
</details>

---

## 🧰 Tech Stack

### Languages & Frameworks
<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=000&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Chi%20Router-00ADD8?logo=go&logoColor=fff&style=for-the-badge"/>
</p>

### AI & Automation
<p>
  <img src="https://img.shields.io/badge/Model%20Context%20Protocol%20(MCP)-7C3AED?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Agentic%20Workflows-4A90E2?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LLM%20Tool%20Calling-F5A623?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Prompt%20Engineering-EC4899?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenRouter-FF4A00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Multi--Model%20Fallbacks-10B981?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/YAML%20Protocol%20Design-CB171E?logo=yaml&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/httpx-000000?logo=python&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/pytest-0A9B70?logo=pytest&logoColor=fff&style=for-the-badge"/>
</p>

### Platforms & APIs (MCPs)
<p>
  <img src="https://img.shields.io/badge/Index%20Exchange-00A99D?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenX-00AEEF?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Magnite-F15A29?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Xandr-FF6900?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/TripleLift-1B9AF7?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Media.net-2C2C32?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PubMatic-6F42C1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Adverity-228B22?style=for-the-badge"/>
</p>

### Design & Tools
<p>
  <img src="https://img.shields.io/badge/Design%20Systems-FF4785?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Design%20Tokens-0EA5E9?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Storybook-FF4785?logo=storybook&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MUI-007FFF?logo=mui&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/HTML%20Email-EA580C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Accessibility-000000?logo=accessible-icon&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff&style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?logo=anthropic&logoColor=fff&style=for-the-badge"/>
</p>

---

## 🧭 Values & Interests

- 🎯 Bridging powerful backend systems and the humans who use them — whether through a React UI or an AI agent, the goal is the same: **make the complex feel simple**.
- ✨ Creating tech that feels **beautiful, effortless, trustworthy, and human**.
- 🌿 Off the clock: hiking 🥾, skiing ⛷️, travel ✈️, photography 📸, organic cooking 👩🏻‍🍳, board games 🎲, interior design 🕯️, painting 🎨 & crafts 🧶.

---

<h2 align="center">🤝 Let's Connect</h2>

<p align="center">
  <a href="https://www.linkedin.com/in/elysemesser">LinkedIn</a> ·
  <a href="https://github.com/elysemesser">GitHub</a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12&height=120&section=footer" width="100%" alt="" />
</div>
