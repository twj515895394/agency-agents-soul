# 🔌 Agency Agents - Soul.md Core Directory

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Bilingual Twin](https://img.shields.io/badge/Bilingual-Bilingual%20Twin-blue)](https://github.com/twj515895394/agency-agents-soul-cn)

> **Enterprise-grade AI Agent Personality Cores built on a rigid 8-layer cognitive architecture and defensive alignment boundaries.**

---

## 🌟 Project Vision

Traditional system prompts often suffer from **behavioral drift**, **hallucinatory instructions**, and **jailbreak vulnerabilities**. When prompts are written as loose, narrative-style instructions, Large Language Models struggle to maintain consistent constraints across long conversational contexts.

**Agency Agents - Soul.md** solves this by formalizing agent design. We have refactored **177 distinct professional AI Agent roles** into structured, high-density, and highly rigid `.md` config files (personality cores) based on the **8-Layer Cognitive Architecture**. Every agent profile acts as a deterministic, predictable, and audit-ready behavioral contract.

---

## 📐 The 8-Layer Cognitive Architecture

Every agent core (`-soul.md`) in this repository strictly adheres to a robust, standardized 8-dimensional hierarchy:

```
+-------------------------------------------------------------+
|  1. Profile           -- Role, domain, and core vibe        |
+-------------------------------------------------------------+
|  2. Personality       -- Professional traits & attitudes    |
+-------------------------------------------------------------+
|  3. Core Abilities    -- Categorized skill checklists       |
+-------------------------------------------------------------+
|  4. Boundaries        -- Defensive constraints (Do Not...)  |
+-------------------------------------------------------------+
|  5. Calibration       -- High-fidelity response examples    |
+-------------------------------------------------------------+
|  6. Language & Style  -- Formality, vocabulary & tone keys   |
+-------------------------------------------------------------+
|  7. Interaction       -- Standard input/process/output loops|
+-------------------------------------------------------------+
|  8. Safety & Trust    -- IP protection, compliance & safety |
+-------------------------------------------------------------+
```

### 🛡️ Defensive Alignment Boundaries
A hallmark of this repository is the **rigid negative constraint paradigm** in the **Boundaries** layer. 
* Every rule in the Boundaries section **strictly and exclusively** starts with `"Do not..."`.
* This syntax prevents prompt contamination, flags potential execution drift, and stops models from attempting positive actions within a safety fence—drastically reducing hallucinations in production MLOps environments.

---

## 📦 Category Navigation

We have categorized our 177 specialized agents into **17 structural directories** mapping a complete enterprise operations matrix:

| Directory | Core Operational Focus | Roles Count |
| :--- | :--- | :---: |
| 🎓 [**Academic Research**](./academic/) | Deep theoretical, sociological, and transdisciplinary research. | **5** |
| 🎨 [**Creative Design**](./design/) | Brand guardians, visual storytellers, and UI/UX design directors. | **8** |
| 💻 [**Software Engineering**](./engineering/) | Backend architects, Solidity devs, DevOps, and mini-program engineers. | **29** |
| 🔌 [**Workflow Examples**](./examples/) | Streamlined multi-agent and spatial discovery workflow demonstrations. | **5** |
| 📊 [**Financial Analysis**](./finance/) | Bookkeepers, tax strategists, and investment researchers. | **5** |
| 🎮 [**Game Development**](./game-development/) | Level designers, game audio engineers, and technical artists. | **5** |
| 🪢 [**System Integrations**](./integrations/) | Bridges and API connectors for third-party system integrations. | **0** *(Spec Core)* |
| 📢 [**Growth & Marketing**](./marketing/) | SEO specialists, Xiaohongshu experts, and outbound copywriters. | **30** |
| 🎯 [**Paid Media Operations**](./paid-media/) | PPC strategists, social ad buyers, and conversion attribution analysts. | **7** |
| 📦 [**Product Management**](./product/) | Trend researchers, product managers, and roadmap controllers. | **5** |
| 🗃️ [**Project Management**](./project-management/) | Jira stewards, studio producers, and sprint prioritizers. | **6** |
| 🤝 [**Sales Enablement**](./sales/) | Outbound prospectors, discovery coaches, and proposal strategists. | **8** |
| 🥽 [**Spatial Computing**](./spatial-computing/) | visionOS engineers, Metal rendering developers, and XR interaction builders. | **6** |
| 💼 [**Specialized Services**](./specialized/) | Legal document auditors, blockchain security specialists, and medical compliance experts. | **41** |
| 🧠 [**Strategy Consulting**](./strategy/) | Corporate positioning specialists, executive brief writers, and strategy advisers. | **3** |
| 🩺 [**Operations & Support**](./support/) | Data reporters, compliance officers, and infrastructure maintainers. | **6** |
| 🧪 [**Testing & Quality Assurance**](./testing/) | API automation testers, accessibility auditors, and reality checkers. | **8** |

---

## ⚡ Integration Quickstart

You can easily load any `soul.md` from this repository into your favorite developer IDEs or agent orchestrators to instantly spin up highly reliable agent personas.

### 1. In Cursor / VSCode Cline
1. Navigate to the category of your choice, open the target `-soul.md` file (e.g., `software-architect-soul.md`).
2. Copy the content and paste it into your `.cursorrules` file, or save it under `.cline/prompts/` to condition the AI context.
3. Your editor assistant will immediately adopt the strict cognitive style and defensive boundaries.

### 2. In Claude Code
Set up a transparent developer agent by supplying the soul profile in the run configuration:
```bash
claude --prompt "$(cat specialized-mcp-builder-soul.md)"
```

### 3. In Custom Multi-Agent Frameworks (LangChain, CrewAI, AutoGen)
Inject the `soul.md` contents into the system message parameter when initializing the model executor:
```python
from crewai import Agent

system_soul = open("software-architect-soul.md", "r").read()

architect_agent = Agent(
    role="Software Architect",
    goal="Design production-grade system blueprints",
    backstory=system_soul, # Injects the 8-layer architecture
    verbose=True
)
```

---

## 🇨🇳 Bilingual Twin Repository

This project is maintained alongside its sister repository: **[agency-agents-soul-cn](https://github.com/twj515895394/agency-agents-soul-cn)**.
* **100% Identical File Names**: Files share identical names across both repositories (e.g. `/marketing/seo-specialist-soul.md` maps exactly to `/08_增长与数字营销/seo-specialist-soul.md`).
* **Physical Sorted Chinese Directories**: The Chinese repository prepends numerical categories (like `03_软件与系统工程`) to force physical ascending order in file trees and sidebars, avoiding Chinese character sorting drift.
* **Localization Sweep**: Every Chinese card undergoes deep engineering and linguistic translation, scrubbing generic adjectives in favor of operational, high-context Chinese business terminology.

---

## 🤝 Acknowledgments & Credits

We would like to express our deepest gratitude to the original repository **[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)**. Most of the AI Agent roles and profiles in this project are adapted, refactored, and converted from their excellent open-source agent descriptions. This project would not have been possible without their foundational contribution to the global AI engineering community.

---

## 📄 License

This repository is licensed under the **MIT License**. Feel free to use, adapt, and build upon these agent cores for personal and commercial applications.
