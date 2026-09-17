# BOOSTSCIENCE WP2 Expert

Reusable ChatGPT Skill for the **BOOSTSCIENCE** Erasmus+ Capacity Building in Higher Education project (Grant Agreement **101237769**), focused on the Leanspots/LNS responsibilities around:

- **T2.2** labour-market and skills intelligence for Biology and Chemistry graduates.
- **T2.4** methodological framework for Ukrainian HEI reform.
- **D2.3** Reform Roadmap for Ukrainian HEIs.
- Evidence traceability, contractual mapping, KPI design, pilot frameworks, stakeholder consultation, and Basecamp evidence reconciliation.

## What this repository contains

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
├── assets/
│   └── icon.svg
└── references/
    ├── basecamp-evidence-workflow.md
    ├── boostscience-contractual-map.md
    ├── compliance-and-qa.md
    ├── eu-frameworks-and-policies.md
    ├── evidence-source-hierarchy.md
    ├── sources-to-refresh.md
    ├── t2-2-market-skills-methodology.md
    ├── t2-4-d2-3-roadmap-methodology.md
    ├── templates.md
    └── ukraine-he-and-labour-context.md
```

## Core design principles

The skill uses a strict evidence hierarchy and distinguishes contractual facts, project evidence, external evidence, methodological recommendations, and evidence gaps. It is designed to prevent unsupported institutional claims and to preserve documentary inconsistencies rather than silently rewriting the approved proposal.

The operational chain is:

```text
T2.2 market/skills evidence
        ↓
T2.4 reform methodology
        ↓
D2.3 implementable HEI reform roadmap
```

## Typical prompts

- `Analyse current Biology and Chemistry labour-market demand relevant to BOOSTSCIENCE T2.2.`
- `Map employer demand to curriculum gaps for a participating Ukrainian HEI.`
- `Audit this D2.3 section against the approved BOOSTSCIENCE contractual baseline.`
- `Create a pilot framework for a proposed HEI reform action.`
- `Reconcile the latest Basecamp instructions with T2.4 and D2.3 contractual responsibilities.`
- `Build a KPI and evidence-of-completion matrix for the reform roadmap.`

## Installation / distribution

The repository root is the skill directory. To distribute it as a ChatGPT Skill, package the directory as `skill.zip` using the standard Skill packaging workflow, or use the validated `skill.zip` included in the release artifacts generated from this repository.

## Source maintenance

The skill deliberately separates stable contractual content from sources that must be refreshed. See `references/sources-to-refresh.md` before using the skill for current labour-market, policy, framework, or regulatory claims.

## Data and confidentiality

This repository contains reusable instructions and public-source references. It does **not** bundle project invoices, credentials, local filesystem paths, private email archives, or uploaded proposal PDFs. When used operationally, project records should be retrieved from authorised sources and treated according to the evidence hierarchy defined in `SKILL.md`.

## Project context

BOOSTSCIENCE is an Erasmus+ CBHE Strand 2 project: **Boosting Education Quality and Entrepreneurial Mindsets for Natural Sciences in Ukraine**. This skill is project-specific and should not be treated as a generic Erasmus+ legal or reporting authority.

## License

This repository is released under the MIT License. See [LICENSE](LICENSE) for the full text.
