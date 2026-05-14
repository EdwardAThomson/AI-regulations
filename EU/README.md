# European Union — AI Governance

The EU's AI governance position is the world's most comprehensive horizontal regulatory framework for AI. The EU AI Act (Regulation 2024/1689) classifies AI systems by risk level (prohibited, high-risk, limited risk, minimal risk) and imposes binding obligations accordingly, with separate provisions for general-purpose AI models. Phased application runs from February 2025 (prohibited practices) through August 2027 (full high-risk provisions). The Act is complemented by the EU AI Office, the AI Pact (voluntary pre-compliance), the GPAI Code of Practice, Commission Guidelines, and adjacent legislation (GDPR, Digital Services Act, Data Act, Data Governance Act).

This directory contains the source documents and reviews that together map that position.

## Note

- This material is for research and comparison only, not legal advice.
- Reviews in this directory were produced or assisted by AI and may contain mistakes or outdated interpretations; important points should be checked against the primary sources.

## Contents

```
EU/
├── README.md                          # This file
├── source/                            # Source documents (PDFs)
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews
    └── review-claude/                 # Claude section-level reviews (10 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (15 documents):

### Primary legislation
- **EU AI Act (Regulation 2024/1689)** (July 2024) — horizontal AI regulation with risk-based classification, GPAI provisions, and phased application through August 2027

### Commission Guidelines (non-binding, authoritative)
- **Guidelines on the Definition of an AI System** (July 2025, C(2025) 5053) — Article 3(1) interpretation
- **Guidelines on Prohibited AI Practices** (July 2025, C(2025) 5052) — 134 pages on Article 5
- **Commission Guidelines on GPAI** (July 2025) — scope of GPAI obligations, FLOP thresholds, downstream modifier rules

### Codes of Practice (voluntary)
- **GPAI Code of Practice** — Transparency chapter (July 2025)
- **GPAI Code of Practice** — Copyright chapter (July 2025)
- **GPAI Code of Practice** — Safety and Security chapter (July 2025)
- **GPAI Code of Practice (Summary)** (2025)
- **First Draft Code of Practice on Transparency of AI-Generated Content** (December 2025) — Article 50 operationalisation; final expected June 2026

### Operational guidance
- **Draft Guidance on Serious Incident Reporting** (September 2025) — Article 73 operationalisation with tiered timelines (2/10/15 days)
- **Incident Report Template for Serious Incidents** (September 2025)

### Voluntary pact
- **EU AI Pact Press Release** (September 2024) — voluntary pledges bridging AI Act entry into force and full application

### Strategic plans
- **Coordinated Plan on AI — 2021 Review** (April 2021, COM(2021) 205) — investment/coordination blueprint with 14 joint action areas

### Ethical frameworks (historical)
- **Ethics Guidelines for Trustworthy AI** (April 2019) — AI HLEG 7-requirement framework that became the intellectual foundation of the AI Act

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Ten document-level reviews following the structure set out in [`../methodology.md`](../methodology.md) (summary, key points, observations across analytical lenses, overall assessment).

**Note on numbering:** File numbers (`01-` through `10-`) reflect the order in which reviews were produced, not the publication date of the source document. The table below is sorted chronologically by the source document's publication date, with the file number shown in the first column.

| # | Date | Review |
|---|------|--------|
| 08 | Apr 2019 | [Ethics Guidelines for Trustworthy AI (HLEG)](analysis/review-claude/08-ethics-guidelines-trustworthy-ai-2019.md) |
| 09 | Apr 2021 | [Coordinated Plan on AI — 2021 Review](analysis/review-claude/09-coordinated-plan-on-ai-2021-review.md) |
| 01 | Jul 2024 | [EU AI Act (Regulation 2024/1689)](analysis/review-claude/01-eu-ai-act.md) |
| 10 | Sep 2024 | [EU AI Pact](analysis/review-claude/10-eu-ai-pact.md) |
| 02 | Jul 2025 | [Guidelines on the Definition of an AI System](analysis/review-claude/02-guidelines-definition-ai-system.md) |
| 03 | Jul 2025 | [Guidelines on Prohibited AI Practices](analysis/review-claude/03-guidelines-prohibited-ai-practices.md) |
| 04 | Jul 2025 | [Commission GPAI Guidelines](analysis/review-claude/04-commission-gpai-guidelines.md) |
| 05 | Jul 2025 | [GPAI Code of Practice (three chapters)](analysis/review-claude/05-gpai-code-of-practice.md) |
| 06 | Sep 2025 | [Serious Incident Reporting Guidance and Template](analysis/review-claude/06-serious-incident-reporting-guidance-and-template.md) |
| 07 | Dec 2025 | [Transparency Code for AI-Generated Content (first draft)](analysis/review-claude/07-transparency-code-ai-generated-content.md) |

## Key findings across the EU landscape

The ten reviews together surface several persistent themes and tensions in the EU's AI governance position:

1. **Regulatory stack, not a single instrument.** The AI Act is the binding centrepiece, but operational compliance flows through Commission Guidelines (interpretation), voluntary Codes of Practice (structured compliance routes), and Article 73 incident reporting (operational detail). UK firms serving EU clients cannot rely on the AI Act alone — the secondary instruments define how compliance is actually demonstrated.

2. **Intellectual continuity from 2019 to 2025.** The HLEG's four ethical principles and seven requirements (April 2019) directly shape the AI Act's high-risk obligations (2024) and the July 2025 Commission Guidelines. "Trustworthy AI" vocabulary remains the EU's positional framing.

3. **Phased application creates compliance windows.** Prohibited practices + AI literacy (Feb 2025), GPAI (Aug 2025), high-risk + transparency (Aug 2026), embedded-product high-risk (Aug 2027). The AI Pact provides a voluntary bridge mechanism for the 2024-2026 transition.

4. **GPAI emerged post-Plan, now central.** The 2021 Coordinated Plan pre-dated ChatGPT and did not address foundation models. By July 2025, GPAI had become a major compliance category with its own Guidelines, Code of Practice, and 10^23/10^25 FLOP thresholds for classification and systemic risk designation.

5. **Four specified systemic risks in the GPAI Code.** CBRN, Loss of Control, Cyber Offence, Harmful Manipulation. These categories, plus the tiered incident reporting timelines (2/10/15 days), define the operational risk architecture for the most capable models.

6. **Two-track transparency obligations.** Provider machine-readable marking (Article 50(2)) and deployer human-readable labelling (Article 50(4)) operate at different layers but must interoperate. The Transparency Code (Dec 2025 first draft) specifies the two-level taxonomy (fully AI-generated vs AI-assisted) and modality-specific rules.

7. **Extraterritorial reach.** UK-established providers placing AI systems on the EU market or whose outputs are used in the EU fall within scope regardless of UK establishment — the primary basis on which UK firms serving EU clients need to understand the EU framework.

8. **Enforcement interoperability.** AI Act obligations intersect with GDPR, DSA, CER, NIS2, DORA, MDR/IVDR, AVMSD, European Media Freedom Act, and sectoral product safety legislation. Compliance often requires coordinated interpretation across multiple regulatory regimes.

## Position in comparative landscape

The EU AI Act is the benchmark against which other jurisdictions' approaches are compared or contrasted:

- **UK** explicitly rejects the EU's risk-classification model in favour of a context-specific, sector-regulator-led approach (see [`../UK/analysis/review-claude/03-pro-innovation-white-paper.md`](../UK/analysis/review-claude/03-pro-innovation-white-paper.md))
- **Scotland** advocates EU AI Act alignment on market access grounds (see [`../UK/analysis/UK-Scotland-comparison.md`](../UK/analysis/UK-Scotland-comparison.md))
- **Singapore** operates a voluntary governance framework but participates in international coordination alongside EU efforts
- **USA** has taken a patchwork approach with no comprehensive federal legislation; state-level regulation (Colorado AI Act) more closely resembles the EU approach than federal action does
- **Switzerland** explicitly decided against standalone AI legislation (November 2023) but is assessing equivalence pressure from the EU AI Act

The three EEA EFTA states (Norway, Iceland, Liechtenstein) must incorporate the AI Act into the EEA Agreement — extending its effective reach beyond the EU 27. Switzerland, as the only EFTA member outside the EEA, explicitly rejected the AI Act. See [`../comparisons/efta-ai-governance.md`](../comparisons/efta-ai-governance.md) for the EFTA comparison.

The CMA's review of the EU approach (in [`../UK/analysis/review-claude/09-cma-ai-foundation-models-initial-report.md`](../UK/analysis/review-claude/09-cma-ai-foundation-models-initial-report.md)) summarises the Act's provisions on foundation models and general-purpose AI.
