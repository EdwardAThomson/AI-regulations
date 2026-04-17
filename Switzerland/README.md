# Switzerland — AI Governance

Switzerland has adopted a deliberately light-touch, technology-neutral approach to AI regulation. The Federal Council explicitly decided against standalone AI legislation in February 2025, preferring to address AI through ratification of the Council of Europe AI Convention, sector-specific legislative adjustments, and non-binding complementary measures. Switzerland is not bound by the EU AI Act but faces market access pressure: Swiss firms exporting to the EU must comply with the AI Act regardless of domestic Swiss regulation.

Switzerland's distinctive contribution is its international convening role: Geneva hosts the ITU AI for Good platform, and Switzerland positions itself as a neutral hub for AI governance diplomacy.

## Contents

```
Switzerland/
├── README.md                          # This file
├── source/                            # Source documents
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews
    └── review-claude/                 # Claude section-level reviews (2 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (2 documents):

### Federal policy
- **Federal Council AI Regulation Approach** (February 2025) — the definitive policy announcement: no Swiss AI Act; sector-specific + Council of Europe Convention implementation

### Sector-specific
- **FINMA Guidance 08/2024 on AI Governance** (December 2024) — 7-page supervisory guidance on governance and risk management for AI use in financial services

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Two document-level reviews following the structure set out in [`../methodology.md`](../methodology.md).

| # | Date | Review |
|---|------|--------|
| 02 | Dec 2024 | [FINMA Guidance 08/2024 on AI Governance](analysis/review-claude/02-finma-guidance-ai-governance.md) |
| 01 | Feb 2025 | [Federal Council AI Regulation Approach](analysis/review-claude/01-federal-council-ai-regulation-approach.md) |

## Key findings across the Swiss landscape

1. **No Swiss AI Act — and no binding AI-specific obligations until at least 2028.** The Federal Council chose sector-specific adjustments plus Council of Europe Convention ratification. The FDJP bill is due end 2026; parliamentary process adds 1-2 years. Swiss-specific AI obligations are unlikely before 2028.

2. **FINMA is the most operationally relevant Swiss AI regulator today.** Its Guidance 08/2024 is the most substantive domestic AI compliance document. It applies a proportionate, materiality-based framework: not all AI requires the same governance. This is philosophically aligned with the UK FCA's approach and contrasted with the EU's categorical classification.

3. **EU AI Act applies to Swiss firms serving the EU market regardless of domestic law.** The Swiss framework is additive, not substitutive. Swiss life sciences, MedTech, and financial services firms exporting to the EU must comply with the AI Act directly. This creates dual-compliance obligations.

4. **The Council of Europe Convention anchor is diplomatically important but operationally light.** The Convention requires human-rights-compatible AI governance but does not prescribe risk tiers, prohibited practices, or GPAI thresholds. It leaves implementation to national discretion.

5. **Switzerland's approach is the closest to the UK's among jurisdictions studied.** Both reject comprehensive AI Acts; both prefer sector-regulator-led approaches; both face EU market-access pressure. Key difference: the UK has AISI (100+ researchers, £240M); Switzerland has no equivalent safety institute.

6. **No prohibited practices, no GPAI provisions, no incident reporting.** Switzerland has none of the EU's Article 5 prohibitions, Chapter V GPAI obligations, or Article 73 incident reporting. Whether the Council of Europe Convention will require Switzerland to address any of these remains to be determined.

## Position in comparative landscape

Switzerland's approach is philosophically closest to the UK's pro-innovation, non-statutory stance:

- **No standalone AI law** — contrasts with EU AI Act; parallels UK framework
- **Data protection as primary binding instrument** — revised Federal Act on Data Protection (revFADP / nDSG, September 2023) covers automated decision-making and profiling
- **EU equivalence pressure** — Switzerland must assess whether Swiss law provides sufficient protections to maintain EU market access; parallels UK's post-Brexit dynamic
- **Geneva as international hub** — ITU AI for Good, UN agencies, neutral diplomatic tradition; complements UK's AISI secretariat role
- **FINMA addresses AI through existing supervisory frameworks** — analogous to UK FCA's approach (see [`../UK/analysis/review-claude/12-fca-ai-update.md`](../UK/analysis/review-claude/12-fca-ai-update.md))
- **No safety institute** — unlike UK (AISI) or EU (AI Office); no dedicated scientific evaluation function

Key differences from UK:
- UK has AISI as a world-leading frontier safety research body; Switzerland has no equivalent
- UK has the DUAA 2025 actively relaxing ADM rules; Switzerland's revFADP maintains stricter baseline
- UK has produced 14 substantive AI governance documents; Switzerland has produced 2

Key differences from EU:
- EU has binding horizontal regulation with risk tiers, prohibited practices, GPAI provisions, and €35M/7% penalties
- Switzerland has voluntary + sector-specific + Convention implementation
- EU framework has extraterritorial reach; Swiss framework does not
