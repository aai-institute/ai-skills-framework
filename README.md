# AI Skills Framework

A framework for defining, developing, and assessing AI skills for professionals — translating artificial intelligence competencies into concrete, assessable skills that organizations can realistically evaluate and develop.

Developed by the [appliedAI Institute for Europe](https://www.appliedai-institute.de/). Full background: [AI Skills Framework](https://www.appliedai-institute.de/ressourcen/ai-skills-framework/) and the whitepaper *"Bringing AI Skills into Practice 2026."*

This repository is the public derivative of the Institute's internal [skills-framework](https://github.com/aai-institute/skills-framework) backend and shares its single core asset: the list of skill components below.

## Why this framework

Most existing AI competency frameworks raise awareness but stop short of professional, role-specific capability. This framework closes that gap by breaking AI competence down into discrete, demonstrable **skill components** that can be assessed and developed like any other professional skill.

## Four primary interaction types

| Type | Who | Focus |
|---|---|---|
| **Use AI** | Analysts, educators, managers, public servants | Integrating AI tools into daily work |
| **Integrate AI** | Leaders | Embedding AI into processes, managing change, aligning adoption with strategy and regulations |
| **Build AI** | Engineers, developers, researchers | Designing, training, and deploying AI systems |
| **Frame AI** | Policymakers, ethicists, communicators | Establishing governance and responsible AI practices |

## Five proficiency levels

1. **Unknown** — no familiarity
2. **Knowledge** — conceptual awareness
3. **Application** — use in familiar contexts
4. **Adaptation** — flexible, confident application
5. **Mastery** — expertise and ability to mentor others

## Multiple projection views

The same skill components can be viewed by:

- **Purpose** — Use / Integrate / Build / Frame AI
- **Domain** — Strategy, Ethics, Data, Programming, Machine Learning, GenAI, MLOps, etc.
- **Role** — professional profiles
- **System** — specific AI applications

Collaboration, communication, problem-solving, and critical thinking form cross-cutting competencies that underpin all four interaction types.

## Skill components

[`skill_components.csv`](skill_components.csv) is the core dataset of this repository — 161 skill components, each with:

- `skill_component_id` — stable identifier
- `skill_component` — the competency itself
- `description` — explanation of the skill (where available)
- `purpose` — one or more of Use / Integrate / Build / Frame AI
- `domain` — e.g. GenAI Proficiency, AI Strategy, MLOps/Infrastructure, Data Competence, AI Regulation, AI Ethics, Machine Learning, Programming, Software Design, Agentic AI Engineering/Governance/Integration/Proficiency
- `keywords_en` / `keywords_ge` — English and German search keywords for each skill

## License

This work is licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). See [LICENSE](LICENSE).
