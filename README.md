# AI Regulations

A comparative analysis of national AI strategies, policies, frameworks, and regulations.

Each country directory contains source documents and analysis covering the full scope of a nation's approach to AI governance — from high-level strategy through to specific regulatory frameworks, whether they address foundation models, agentic systems, sector-specific applications, or AI safety.

## Countries

Each country directory contains its own README with an overview, source inventory, and links to analysis files.

| Country | Status | Reviews | Focus areas |
|---------|--------|---------|-------------|
| [EU](EU/README.md) | Analysis complete | 10 | EU AI Act, GPAI Code of Practice, Commission Guidelines, Transparency Code, HLEG Ethics Guidelines |
| [Singapore](Singapore/README.md) | Analysis in progress | 3 + 2 earlier | Model AI Governance Frameworks (base / GenAI / Agentic AI), National AI Strategy 2.0 |
| [Switzerland](Switzerland/README.md) | Analysis complete | 2 | Federal Council approach (no standalone AI law), FINMA AI governance guidance |
| [UK](UK/README.md) | Analysis complete | 14 | Pro-Innovation framework, AI Opportunities Action Plan, AISI, Playbook, DUAA 2025 |
| [USA](USA/README.md) | Sources collected | 0 | Biden EO 14110 (revoked), Trump AI Action Plan, NIST AI RMF, state-level patchwork |

## Cross-Jurisdictional Comparisons

| Comparison | Location |
|------------|----------|
| [UK vs EU](comparisons/UK-EU-comparison.md) | Dimension-by-dimension table, convergences, strategic implications |
| [Small Open Economies: UK, Singapore, Switzerland](comparisons/small-open-economies-comparison.md) | Three-way comparison of jurisdictions that rejected comprehensive AI legislation |
| [EFTA and AI Governance](comparisons/efta-ai-governance.md) | Norway, Iceland, Liechtenstein (EEA — AI Act binding) vs Switzerland (non-EEA) |
| [UK vs Scotland](UK/analysis/UK-Scotland-comparison.md) | Intra-UK divergence on regulatory philosophy |

## Methodology

Analysis follows a structured approach adapted from a [multi-LLM review of Scotland's AI Strategy 2026-2031](https://github.com/EdwardAThomson/AI_Scotland). That project established a methodology in which three LLMs independently review a strategy document using a shared checklist, and the results are reconciled to surface consensus, disagreements, and blind spots.

This repo extends that approach to multiple countries. Each review covers: summary, key points, and observations across analytical lenses (clarity, measurability, gaps, feasibility, internal consistency, coverage, international alignment), concluding with an overall assessment.

See [methodology.md](methodology.md) for the full assessment framework.

## Scope

The analysis covers **all aspects of a country's AI governance position**, including but not limited to:

- **National AI strategies** — overarching vision, goals, and delivery plans
- **Regulatory frameworks** — binding legislation and regulatory mechanisms (e.g. EU AI Act)
- **Governance frameworks** — non-binding guidance, model frameworks, codes of practice (e.g. IMDA's Model AI Governance Framework)
- **Sector-specific policies** — AI in healthcare, finance, defence, public services, etc.
- **Technical standards** — alignment with ISO/IEC 42001, NIST AI RMF, and other international standards
- **Infrastructure and compute** — national compute strategies, data centre policy, energy considerations
- **Skills and workforce** — AI literacy, upskilling, Fair Work, and labour market impacts
- **Safety and ethics** — AI safety institutes, responsible AI principles, ethical frameworks
- **International positioning** — participation in multilateral AI governance (OECD, G7, GPAI, ASEAN)

The goal is to understand not just what a country has published, but how its various policy instruments fit together, where the gaps are, and how its approach compares to other nations.

## Repository Structure

```
methodology.md                 # Shared assessment framework
README.md                      # This file
comparisons/                   # Cross-jurisdictional comparisons
  UK-EU-comparison.md
  small-open-economies-comparison.md
  efta-ai-governance.md
EU/
  README.md                    # Country overview + 10-review index
  source/
    inventory.md
  analysis/
    review-claude/             # 10 section-level reviews
Singapore/
  README.md                    # Country overview + review index
  source/
    inventory.md
  analysis/
    01-agentic-ai-governance-framework.md
    02-agent-adoption-guide.md
    review-claude/             # 3 section-level reviews
Switzerland/
  README.md                    # Country overview + 2-review index
  source/
    inventory.md
  analysis/
    review-claude/             # 2 section-level reviews
UK/
  README.md                    # Country overview + 14-review index
  source/
    inventory.md
  analysis/
    UK-Scotland-comparison.md
    review-claude/             # 14 section-level reviews
USA/
  README.md                    # Country overview (analysis not yet started)
  source/
    inventory.md
  analysis/
```

## Related

- [Scotland's AI Strategy 2026-2031 — Review](https://github.com/EdwardAThomson/AI_Scotland) — The original multi-LLM review that established the methodology used here. Scotland has its own dedicated repository.
