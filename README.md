# Emanuel Victor de Melo Brebal

Full-stack developer building with LLMs and agents — PHP/Laravel and TypeScript/React/Node.js — open to remote roles.

I build and ship web products end to end: backend APIs, frontend interfaces, and the Docker setup in between. Nearly two years of experience across government systems and an AI-assisted EdTech SaaS. I also integrate LLMs into products, with guardrails and evals, and I'm doing undergraduate research on LLM resilience.

## Availability

- 📍 Marechal Deodoro (Maceió metro area), Brazil — UTC−3, 1–2 hours ahead of US Eastern: full workday overlap with US teams
- 🎓 B.Sc. in Information Systems, CESMAC — graduating by August 2027
- 🗣️ Portuguese (native) · English (B2, certified)
- ✅ Open to remote roles in Brazil and abroad

## Tech stack

**AI:** LLM APIs (Anthropic, Groq), prompt engineering (system prompts, few-shot), agents and multi-agent workflows, tool use, structured output (JSON), guardrails, evals, Claude Code, Cursor, MCP
**Backend:** PHP (Laravel), Node.js (NestJS), PostgreSQL, REST APIs, queues
**Frontend:** TypeScript, React, React Native, Inertia, Tailwind
**Tooling & DevOps:** Docker, Git, GitHub Actions, Pest, PHPStan, Linux
**ML foundations:** classification, regression and clustering (coursework)

## Selected projects

- **[OncoMente](https://github.com/emanuelbrebal/cancer-health-care-app)** — Oncology patients rarely get structured mental-health support during treatment. For my capstone project, built for a real client, I designed and built a mobile app and a web manager with an LLM-powered companion: a modular system prompt with few-shot examples, guardrails that route emergencies to crisis lines (CVV/SAMU) before the model and block cure promises and dosages, and an eval script with 5 personas, including a prompt-injection attempt. React Native + Expo, NestJS, Prisma, PostgreSQL (monorepo), 44 REST endpoints. In progress.
- **[Radar Mensal](https://github.com/emanuelbrebal/monthly-radar)** — Brazilian IT civil-service exams (*concursos*) are scattered across aggregator sites and official pages, each with its own deadlines. I built a single-user tracker: a queued pipeline scrapes 3 sources, deduplicates and puts every deadline on a calendar, and an optional LLM step (Anthropic API with web search) fills data gaps as schema-validated JSON with a source and a confidence level per field. Laravel 13, Inertia, React 19, PostgreSQL; 109 Pest tests and CI. Built with Claude Code from specs and a `CLAUDE.md`. In personal use.
- **[Vitor Finance](https://github.com/emanuelbrebal/vitor-finance)** — Most finance trackers record spending but don't prevent it. I'm building a personal finance SaaS around a CSV-import MVP and an anti-impulse wishlist that adds friction before purchases. TypeScript, React, Node.js. In development.

## Research

- **AgentShield IA** — Undergraduate research at CESMAC (Programa Semente, November 2026–present): a platform that simulates attacks and defenses to evaluate the resilience of LLMs.

Also on my GitHub:
- **[Ação entre Amigos](https://github.com/emanuelbrebal/acao-entre-amigos-laravel)** (raffle management)
- **[Nutriflow](https://github.com/emanuelbrebal/nutriflow-app)** (SaaS for nutritionists, early development)
- **[ComunidadeAlerta](https://github.com/emanuelbrebal/community-safety-tool)** (community safety forum)

## How I work

I treat AI as part of the engineering process, not a shortcut. Specs come before code (spec-driven development), a `CLAUDE.md` gives the coding agent the project's rules, AI-generated code goes through review as a quality gate, and humans own the architecture decisions. This came from real production work — it's how I contributed to an EdTech SaaS under tight timelines without sacrificing code quality.

I also build my own AI tooling in Claude: 10+ skills and agents, led by `/aprimorar`, a prompt-engineering skill that turns a raw prompt into a structured one (persona, context, verifiable task, acceptance criteria). Around it: forks for code and image generation, research skills that report confidence levels, and a four-reviewer panel in the LLM Council pattern.

## Contact

- 🌐 Portfolio: [emanuelbrebal.github.io](https://emanuelbrebal.github.io)
- 💼 LinkedIn: [linkedin.com/in/emanuel-victor-brebal](https://linkedin.com/in/emanuel-victor-brebal)
- 📧 Email: [manu.brebal@gmail.com](mailto:manu.brebal@gmail.com)
