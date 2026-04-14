# United Kingdom — AI Governance

The UK's AI governance position is distinctive: deliberately pro-innovation, non-statutory, sector-regulator-led, with a dedicated safety institute (AISI) operating at the frontier and extensive operational guidance for public sector use. It explicitly rejects the EU's horizontal regulatory approach while positioning itself as a convener of international AI safety dialogue (Bletchley, Seoul, Paris summits).

This directory contains the source documents and reviews that together map that position.

## Contents

```
UK/
├── README.md                          # This file
├── source/                            # Source documents (PDFs / markdown)
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews and cross-country comparison
    ├── ai-strategy-summary-from-claude.md
    ├── UK-Scotland-comparison.md      # UK vs Scotland governance comparison
    └── review-claude/                 # Claude section-level reviews (10 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (10 documents):

### Core strategy
- **AI Opportunities Action Plan** (January 2025) — the flagship strategy authored by Matt Clifford with 50 recommendations
- **AI Opportunities Action Plan: Government Response** (January 2025) — formal recommendation-by-recommendation response with delivery timelines
- **AI Opportunities Action Plan: One Year On** (January 2026) — progress update claiming 38 of 50 actions met

### Regulatory framework
- **Pro-Innovation White Paper** (March 2023, HTML-only, converted to markdown) — the foundational regulatory framework with 5 cross-sectoral principles
- **Pro-Innovation Regulation: Government Response to Consultation** (February 2024) — detailed 100-page policy evolution including the case for binding measures on frontier AI developers

### Operational guidance
- **AI Playbook for UK Government** (February 2025) — 118-page operational guidance with 10 principles and extensive ethics, legal, security, and governance prescriptions

### Sector-specific
- **AI for Science Strategy** (November 2025) — dedicated strategy for AI in research with 137M GBP budget, 5 priority areas, and a drug discovery mission
- **CMA AI Foundation Models: Initial Report** (September 2023) — 129-page competition analysis with 7 principles for market development

### Safety research
- **AI Safety Institute: Approach to Evaluations** (February 2024) — AISI's first public account of its evaluation methodology
- **International Scientific Report on the Safety of Advanced AI** (May 2024) — interim report chaired by Yoshua Bengio with Expert Advisory Panel nominated by 30 countries, EU, and UN

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Ten document-level reviews following the structure set out in [`../methodology.md`](../methodology.md) (summary, key points, observations across analytical lenses, overall assessment):

| # | Review | Source document |
|---|--------|-----------------|
| 01 | [AI Opportunities Action Plan](analysis/review-claude/01-ai-opportunities-action-plan.md) | January 2025 |
| 02 | [Pro-Innovation Regulation: Consultation Response](analysis/review-claude/02-pro-innovation-regulation-consultation-response.md) | February 2024 |
| 03 | [Pro-Innovation White Paper](analysis/review-claude/03-pro-innovation-white-paper.md) | March 2023 |
| 04 | [AI Opportunities Action Plan: One Year On](analysis/review-claude/04-ai-opportunities-action-plan-one-year-on.md) | January 2026 |
| 05 | [AI Opportunities Action Plan: Government Response](analysis/review-claude/05-ai-opportunities-action-plan-govt-response.md) | January 2025 |
| 06 | [AI for Science Strategy](analysis/review-claude/06-ai-for-science-strategy.md) | November 2025 |
| 07 | [AI Playbook for UK Government](analysis/review-claude/07-ai-playbook-uk-government.md) | February 2025 |
| 08 | [AISI Approach to Evaluations](analysis/review-claude/08-aisi-approach-to-evaluations.md) | February 2024 |
| 09 | [CMA AI Foundation Models: Initial Report](analysis/review-claude/09-cma-ai-foundation-models-initial-report.md) | September 2023 |
| 10 | [International Scientific Report on Safety of Advanced AI](analysis/review-claude/10-international-scientific-report-safety-advanced-ai.md) | May 2024 |

### Cross-country comparison

- [**UK vs Scotland comparison**](analysis/UK-Scotland-comparison.md) — cross-references the 10 UK reviews with the three-LLM review of Scotland's AI Strategy 2026-2031 in the sibling [AI_Scotland repository](https://github.com/EdwardAThomson/AI_Scotland). Identifies substantive divergences (regulatory philosophy, measurability, operational depth), shared weaknesses (economy-first framing, institutional machinery without results), and structural constraints (reserved vs devolved competences).

### Earlier summary

- [`ai-strategy-summary-from-claude.md`](analysis/ai-strategy-summary-from-claude.md) — initial summary produced before the section-level review programme began.

## Key findings across the UK landscape

The ten reviews together surface several persistent tensions in the UK's AI governance position:

1. **Voluntary vs binding.** The regulatory framework is explicitly non-statutory. The January 2025 Government Response committed to establishing AISI as a statutory body; as of the January 2026 progress report, this remained undelivered.

2. **Pro-innovation framing vs identified risks.** The framework is branded pro-innovation, but AISI's own research and the International Scientific Report find that LLMs can lower barriers for malicious actors, safeguards are easily bypassed, AI agents behave deceptively, and oversight fails roughly half the time. The UK approach identifies risks but provides limited mechanism for responding to them.

3. **Central government vs wider public sector.** The Playbook, ATRS, and related frameworks apply well to central government. Local government, NHS trusts, schools, and arms-length bodies have less comprehensive coverage — despite being major users of AI systems.

4. **Domestic vs international.** The UK leads on international scientific coordination (AISI, international summits) but the flagship strategy documents are almost entirely domestic. International governance alignment is under-developed.

5. **Process vs outcome measurement.** The Government Response added delivery timelines to the original Action Plan, but outcome metrics remain absent. The One Year On claim of "38 of 50 actions met" is unverifiable from the text.
