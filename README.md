# ⚡ Next-Gen Claude Skills

### Build faster. Think deeper. Ship like a team.

A curated open-source collection of **17 specialized AI Skills** designed to turn Claude into a capable, role-based engineering and product team.

From **idea → architecture → code → testing → security → deployment → optimization → documentation**, the collection gives Claude a specialized role for almost every stage of modern digital product development.

[![Skills](https://img.shields.io/badge/Skills-17-6f42c1?style=for-the-badge)](./skills)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)
[![GitHub](https://img.shields.io/badge/GitHub-Open%20Source-black?style=for-the-badge&logo=github)](https://github.com/suhanr/next-gen-claude-skills)

---

## What is this?

Think of it as a **virtual AI engineering organization**.

Instead of asking one general-purpose AI to do everything, you can give it specialized roles with focused responsibilities, workflows, quality standards, decision frameworks, and production-minded behavior.

```text
                         YOUR IDEA
                            │
                            ▼
                  ┌───────────────────┐
                  │  PRODUCT ENGINEER │
                  └─────────┬─────────┘
                            ▼
                 ┌────────────────────┐
                 │ SYSTEM ARCHITECT   │
                 └──────────┬─────────┘
                            ▼
              ┌──────────────────────────┐
              │  FULL-STACK ENGINEER     │
              └────────────┬─────────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
      AI / ML          DATABASE          UI / UX
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                    QA / TESTING
                           │
                           ▼
                  CYBERSECURITY
                           │
                           ▼
                    DEVOPS / SRE
                           │
                           ▼
                    PERFORMANCE
                           │
                           ▼
                    DOCUMENTATION
                           │
                           ▼
                         SHIP
```

---

## 🚀 The 17 Roles

| # | Role | What it brings |
|---|---|---|
| **01** | **Next-Gen Full-Stack Engineer** | Build, test, deploy, run and evolve complete applications |
| **02** | **AI Systems Architect** | Design AI systems, agents, RAG, tools and evaluation workflows |
| **03** | **AI / ML Engineer** | Build ML, LLM, RAG, fine-tuning and inference systems |
| **04** | **DevOps + Cloud + SRE Engineer** | Deploy, scale, observe and operate production systems |
| **05** | **Cybersecurity Engineer** | Threat modeling, secure architecture and application security |
| **06** | **Database Architect + Data Engineer** | Data models, databases, pipelines and data platforms |
| **07** | **Software / System Architect** | Architecture, distributed systems and scalability decisions |
| **08** | **Product Engineer / 0→1 Builder** | Turn ideas into validated, usable products |
| **09** | **UI / UX + Design Engineer** | UX, interfaces, design systems and accessibility |
| **10** | **Mobile App Engineer** | Build and ship Android, iOS and cross-platform apps |
| **11** | **Game Developer** | Gameplay, systems, networking, graphics and optimization |
| **12** | **QA + Test Automation Engineer** | Automated testing, regression and quality engineering |
| **13** | **Performance Engineer** | Profiling, latency, scalability and optimization |
| **14** | **Automation / AI Automation Architect** | Agents, workflows, APIs and intelligent automation |
| **15** | **Data Analyst + Research Scientist** | Research, statistics, analysis and evidence-based reporting |
| **16** | **Technical Writer / Documentation Engineer** | Developer docs, API docs, guides and troubleshooting |
| **17** | **Git + Code Review + Engineering Manager** | Code quality, reviews, technical debt and delivery discipline |

---

## 🧩 Built to Work Together

The Skills are modular. Use one role for a focused task or combine several roles for a complete project.

### Example: Build a SaaS product

```text
Idea
 │
 ├── Product Engineer
 │       ↓
 ├── System Architect
 │       ↓
 ├── UI / UX Engineer
 │       ↓
 ├── Full-Stack Engineer
 │       ├── Database Engineer
 │       └── AI / ML Engineer
 │       ↓
 ├── QA Engineer
 │       ↓
 ├── Cybersecurity Engineer
 │       ↓
 ├── DevOps / SRE
 │       ↓
 ├── Performance Engineer
 │       ↓
 └── Documentation Engineer
```

### Example: Build an AI agent

```text
AI Systems Architect
        ↓
AI / ML Engineer
        ↓
Automation Architect
        ↓
Database / Data Engineer
        ↓
Cybersecurity Engineer
        ↓
QA Engineer
        ↓
DevOps / SRE
```

The result is not just code generation. The goal is **structured engineering thinking from beginning to production**.

---

## 🛠️ What's inside a Skill?

Every Skill is designed around a focused professional role and contains a `SKILL.md` as its primary instruction layer.

Where useful, supporting material is separated into `references/` so the core instructions stay focused while deeper frameworks remain available when needed.

```text
skill-name/
├── SKILL.md
└── references/
    ├── decision-framework.md
    ├── quality-framework.md
    └── *.md
```

---

## ⚡ Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/suhanr/next-gen-claude-skills.git
cd next-gen-claude-skills
```

### 2. Choose a role

```text
skills/
├── 01-next-gen-full-stack-engineer/
├── 02-ai-systems-architect/
├── 03-ai-ml-engineer/
├── 04-devops-cloud-sre-engineer/
├── ...
└── 17-git-code-review-engineering-manager/
```

### 3. Use the Skill

Open the selected Skill and use its `SKILL.md` according to your Claude Skill workflow.

For example:

```text
skills/01-next-gen-full-stack-engineer/SKILL.md
```

Pick the role that matches the work. Combine roles when the project needs multiple specialties.

---

## 🎯 When should you use which Skill?

| You want to... | Start with |
|---|---|
| Build a complete website or web app | Full-Stack Engineer |
| Design a complex system | Software / System Architect |
| Build an AI product | AI Systems Architect |
| Train or integrate ML/LLM systems | AI / ML Engineer |
| Deploy to cloud/VPS/Kubernetes | DevOps + Cloud + SRE |
| Secure an application | Cybersecurity Engineer |
| Design databases and pipelines | Database + Data Engineer |
| Turn an idea into a product | Product Engineer |
| Design a polished interface | UI / UX + Design Engineer |
| Build Android/iOS apps | Mobile App Engineer |
| Build a game | Game Developer |
| Automate workflows with AI | Automation Architect |
| Test a product | QA + Test Automation |
| Make an application faster | Performance Engineer |
| Analyze research/data | Data Analyst + Research Scientist |
| Write technical documentation | Documentation Engineer |
| Review code and improve engineering process | Git + Code Review + Engineering Manager |

---

## 🧠 Design Philosophy

These Skills are **forward-looking, not fictional**.

The project does not pretend to know future APIs or invent technologies for 2030. Instead, it focuses on durable engineering principles and instructs agents to verify version-sensitive technologies, APIs, SDKs, and platform behavior against authoritative documentation when needed.

The collection emphasizes:

- Production readiness
- Clear architecture
- Security by design
- Automated testing
- Reliability
- Observability
- Performance
- Maintainability
- Practical decision-making
- Clear role boundaries
- Continuous verification of changing technologies

---

## 🌍 Open Source

This project is intentionally public so developers, students, researchers, founders, and AI builders can reuse, improve, remix, and contribute to the Skills.

Found a weakness? Improve it.

Need a new role? Add it.

Have a better workflow? Share it.

The goal is to build a **community-driven library of high-quality AI professional roles**.

---

## 🤝 Contributing

Contributions are welcome.

A new Skill should generally follow:

```text
skill-name/
├── SKILL.md
└── references/
    └── *.md
```

Keep each Skill:

- Focused on one professional role
- Practical and reusable
- Production-oriented
- Clear about its responsibilities
- Free from unnecessary duplication
- Maintainable as technologies evolve

Before submitting a major change, consider whether it improves the Skill's real-world usefulness rather than simply making it longer.

---

## 🗺️ Roadmap

- [x] 17 professional Skills
- [x] Modular Skill architecture
- [x] Public GitHub repository
- [x] MIT License
- [x] Role-based Skill catalog
- [ ] Automated Skill validation
- [ ] Skill versioning and release tags
- [ ] Community contribution templates
- [ ] More specialized roles
- [ ] Cross-Skill workflow packs
- [ ] Automated quality checks

---

## ⭐ Support the Project

If you find these Skills useful:

**Star the repository, share it with other builders, and contribute improvements.**

Every contribution helps make the collection more useful for the next developer.

---

## 📄 License

MIT License. See [`LICENSE`](./LICENSE).

## 👤 Author

Created and maintained by **[Suhanur Rahman](https://github.com/suhanr)**.

---

<p align="center">
  <strong>Build faster. Think deeper. Ship better.</strong>
  <br />
  Next-Gen Claude Skills — an open-source AI engineering team in your toolkit.
</p>
