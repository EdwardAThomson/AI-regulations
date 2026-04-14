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
    ├── UK-Scotland-comparison.md      # UK vs Scotland governance comparison
    └── review-claude/                 # Claude section-level reviews (14 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (14 documents):

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
- **FCA AI Update** (April 2024) — Financial Conduct Authority's mapping of the government's 5 principles onto existing FCA regulatory frameworks (Principles for Business, SYSC, SM&CR, Consumer Duty)

### Compute and infrastructure
- **Future of Compute Review** (March 2023) — independent review chaired by Professor Zoubin Ghahramani; 10 recommendations including AIRR establishment and exascale delivery by 2026. Foundational for subsequent UK compute policy
- **Delivering AI Growth Zones** (November 2025, CP 1440) — detailed operational policy paper on AIGZ implementation across grid, pricing, planning, and investment environment

### Legislation
- **Data (Use and Access) Act 2025** (Royal Assent June 2025) — the most AI-relevant primary legislation; relaxes Article 22 UK GDPR restrictions on solely automated decision-making, introduces Recognised Legitimate Interests, clarifies scientific research scope

### Safety research
- **AI Safety Institute: Approach to Evaluations** (February 2024) — AISI's first public account of its evaluation methodology
- **International Scientific Report on the Safety of Advanced AI** (May 2024) — interim report chaired by Yoshua Bengio with Expert Advisory Panel nominated by 30 countries, EU, and UN

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Fourteen document-level reviews following the structure set out in [`../methodology.md`](../methodology.md) (summary, key points, observations across analytical lenses, overall assessment).

**Note on numbering:** File numbers (`01-` through `14-`) reflect the order in which reviews were produced, not the publication date of the source document. The table below is sorted chronologically by the source document's publication date, with the file number shown in the first column.

| # | Date | Review |
|---|------|--------|
| 03 | Mar 2023 | [Pro-Innovation White Paper](analysis/review-claude/03-pro-innovation-white-paper.md) |
| 11 | Mar 2023 | [Future of Compute Review](analysis/review-claude/11-future-of-compute-review.md) |
| 09 | Sep 2023 | [CMA AI Foundation Models: Initial Report](analysis/review-claude/09-cma-ai-foundation-models-initial-report.md) |
| 02 | Feb 2024 | [Pro-Innovation Regulation: Consultation Response](analysis/review-claude/02-pro-innovation-regulation-consultation-response.md) |
| 08 | Feb 2024 | [AISI Approach to Evaluations](analysis/review-claude/08-aisi-approach-to-evaluations.md) |
| 12 | Apr 2024 | [FCA AI Update](analysis/review-claude/12-fca-ai-update.md) |
| 10 | May 2024 | [International Scientific Report on Safety of Advanced AI](analysis/review-claude/10-international-scientific-report-safety-advanced-ai.md) |
| 01 | Jan 2025 | [AI Opportunities Action Plan](analysis/review-claude/01-ai-opportunities-action-plan.md) |
| 05 | Jan 2025 | [AI Opportunities Action Plan: Government Response](analysis/review-claude/05-ai-opportunities-action-plan-govt-response.md) |
| 07 | Feb 2025 | [AI Playbook for UK Government](analysis/review-claude/07-ai-playbook-uk-government.md) |
| 14 | Jun 2025 | [Data (Use and Access) Act 2025](analysis/review-claude/14-data-use-and-access-act.md) |
| 06 | Nov 2025 | [AI for Science Strategy](analysis/review-claude/06-ai-for-science-strategy.md) |
| 13 | Nov 2025 | [Delivering AI Growth Zones](analysis/review-claude/13-delivering-ai-growth-zones.md) |
| 04 | Jan 2026 | [AI Opportunities Action Plan: One Year On](analysis/review-claude/04-ai-opportunities-action-plan-one-year-on.md) |

### Cross-country comparison

- [**UK vs Scotland comparison**](analysis/UK-Scotland-comparison.md) — cross-references the 14 UK reviews with the three-LLM review of Scotland's AI Strategy 2026-2031 in the sibling [AI_Scotland repository](https://github.com/EdwardAThomson/AI_Scotland). Identifies substantive divergences (regulatory philosophy, measurability, operational depth), shared weaknesses (economy-first framing, institutional machinery without results), and structural constraints (reserved vs devolved competences).

## Key findings across the UK landscape

The fourteen reviews together surface several persistent tensions in the UK's AI governance position:

1. **Voluntary vs binding.** The regulatory framework is explicitly non-statutory. The January 2025 Government Response committed to establishing AISI as a statutory body; as of the January 2026 progress report, this remained undelivered.

2. **Pro-innovation framing vs identified risks.** The framework is branded pro-innovation, but AISI's own research and the International Scientific Report find that LLMs can lower barriers for malicious actors, safeguards are easily bypassed, AI agents behave deceptively, and oversight fails roughly half the time. The UK approach identifies risks but provides limited mechanism for responding to them.

3. **Central government vs wider public sector.** The Playbook, ATRS, and related frameworks apply well to central government. Local government, NHS trusts, schools, and arms-length bodies have less comprehensive coverage — despite being major users of AI systems.

4. **Domestic vs international.** The UK leads on international scientific coordination (AISI, international summits) but the flagship strategy documents are almost entirely domestic. International governance alignment is under-developed.

5. **Process vs outcome measurement.** The Government Response added delivery timelines to the original Action Plan, but outcome metrics remain absent. The One Year On claim of "38 of 50 actions met" is unverifiable from the text.
