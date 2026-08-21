# Next-Gen Claude Skills

A modular open-source collection of 17 professional AI Skills covering software engineering, AI, product development, research, automation, and engineering leadership.

The goal is simple: give an AI agent specialized professional roles that can work independently or together as an engineering team.

## Skills

| # | Skill | Focus |
|---|---|---|
| 01 | Next-Gen Full-Stack Engineer | End-to-end development, testing, deployment and maintenance |
| 02 | AI Systems Architect | AI architecture, agents, RAG, tools and evaluation |
| 03 | AI / ML Engineer | ML, LLM, RAG, fine-tuning and inference |
| 04 | DevOps + Cloud + SRE Engineer | Infrastructure, CI/CD, deployment and reliability |
| 05 | Cybersecurity Engineer | Security engineering and threat modeling |
| 06 | Database Architect + Data Engineer | Databases, data architecture and pipelines |
| 07 | Software / System Architect | System design, scalability and architecture |
| 08 | Product Engineer / 0â†’1 Builder | Idea, MVP, product engineering and launch |
| 09 | UI / UX + Design Engineer | UX, design systems and production UI |
| 10 | Mobile App Engineer | Android, iOS and cross-platform applications |
| 11 | Game Developer | Gameplay, systems, networking and optimization |
| 12 | QA + Test Automation Engineer | Testing, automation and quality engineering |
| 13 | Performance Engineer | Profiling, latency, scalability and optimization |
| 14 | Automation / AI Automation Architect | AI agents and workflow automation |
| 15 | Data Analyst + Research Scientist | Research, statistics and data analysis |
| 16 | Technical Writer / Documentation Engineer | Developer and technical documentation |
| 17 | Git + Code Review + Engineering Manager | Git, code quality and engineering delivery |

## Structure

```text
skills/
â”œâ”€â”€ 01-next-gen-full-stack-engineer/
â”œâ”€â”€ 02-ai-systems-architect/
â”œâ”€â”€ 03-ai-ml-engineer/
â”œâ”€â”€ 04-devops-cloud-sre-engineer/
â”œâ”€â”€ 05-cybersecurity-engineer/
â”œâ”€â”€ 06-database-data-engineer/
â”œâ”€â”€ 07-software-system-architect/
â”œâ”€â”€ 08-product-engineer-zero-to-one-builder/
â”œâ”€â”€ 09-ui-ux-design-engineer/
â”œâ”€â”€ 10-mobile-app-engineer/
â”œâ”€â”€ 11-game-developer/
â”œâ”€â”€ 12-qa-test-automation-engineer/
â”œâ”€â”€ 13-performance-engineer/
â”œâ”€â”€ 14-automation-ai-automation-architect/
â”œâ”€â”€ 15-data-analyst-research-scientist/
â”œâ”€â”€ 16-technical-writer-documentation-engineer/
â””â”€â”€ 17-git-code-review-engineering-manager/
```

Every Skill is self-contained and includes a `SKILL.md`.

## Using the Skills

Choose the role that matches the work you want the AI agent to perform.

For larger projects, combine multiple roles:

```text
Product Engineer
       â†“
System Architect
       â†“
Full-Stack Engineer
       â†“
AI / ML Engineer
       â†“
Database Engineer
       â†“
QA Engineer
       â†“
Cybersecurity Engineer
       â†“
DevOps / SRE
       â†“
Performance Engineer
       â†“
Documentation Engineer
```

## Design Philosophy

These Skills are designed to be forward-looking and maintainable.

They do not depend on invented future APIs or fictional 2030 technologies. Version-sensitive implementation details should be verified against current authoritative documentation.

The collection emphasizes:

- production readiness
- security
- testing
- maintainability
- observability
- reliability
- performance
- practical architecture
- clear role boundaries

## Contributing

Contributions are welcome.

A new Skill should generally follow:

```text
skill-name/
â”œâ”€â”€ SKILL.md
â””â”€â”€ references/
    â””â”€â”€ *.md
```

Keep Skills focused on a specific professional role and avoid unnecessary duplication.

## License

MIT License. See [LICENSE](LICENSE).

## Author

Created and maintained by [Suhanur Rahman](https://github.com/suhanr).
