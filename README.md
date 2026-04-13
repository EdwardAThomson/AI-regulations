# AI Regulations

A comparative analysis of national AI strategies, policies, frameworks, and regulations.

Each country directory contains source documents and analysis covering the full scope of a nation's approach to AI governance — from high-level strategy through to specific regulatory frameworks, whether they address foundation models, agentic systems, sector-specific applications, or AI safety.

## Countries

| Country | Status | Focus areas |
|---------|--------|-------------|
| [EU](EU/) | Planned | EU AI Act, regulatory framework |
| [Singapore](Singapore/) | In progress | Model AI Governance Framework for Agentic AI (IMDA) |
| [Switzerland](Switzerland/) | Planned | — |
| [UK](UK/) | In progress | AI Opportunities Action Plan, AI for Science Strategy, AI Playbook |
| [USA](USA/) | Planned | — |

## Methodology

Analysis follows a structured approach adapted from a [multi-LLM review of Scotland's AI Strategy 2026-2031](https://github.com/EdwardAThomson/AI_Scotland). That project established a methodology in which three LLMs independently review a strategy document using a shared checklist, and the results are reconciled to surface consensus, disagreements, and blind spots.

This repo extends that approach to multiple countries. Not every country will receive the full multi-LLM treatment immediately — some will start with source collection and preliminary analysis, then deepen over time.

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
methodology.md              # Shared assessment framework
EU/
  source/                   # Source documents (PDFs, official publications)
  analysis/                 # Reviews, assessments, and findings
Singapore/
  source/                   # Source documents
  analysis/                 # Reviews, assessments, and findings
Switzerland/
  source/                   # Source documents
  analysis/                 # Reviews, assessments, and findings
UK/
  source/                   # Source documents
  analysis/                 # Reviews, assessments, and findings
USA/
  source/                   # Source documents
  analysis/                 # Reviews, assessments, and findings
```

## Related

- [Scotland's AI Strategy 2026-2031 — Review](https://github.com/EdwardAThomson/AI_Scotland) — The original multi-LLM review that established the methodology used here. Scotland has its own dedicated repository.
