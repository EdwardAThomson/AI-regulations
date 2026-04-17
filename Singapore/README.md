# Singapore — AI Governance

Singapore's AI governance is distinctive for being entirely voluntary/soft-law based with no standalone binding AI legislation. The governance stack is layered: Model AI Governance Framework (2020, foundational) → Model AI Governance Framework for Generative AI (June 2024) → Model AI Governance Framework for Agentic AI (January 2026). Binding obligations come through adjacent law (PDPA for personal data, HSA for medical devices, MAS supervisory expectations for financial services). Singapore is distinctive for practical testing infrastructure (AI Verify, Project Moonshot) that most jurisdictions lack.

This directory contains the source documents and reviews that together map that position.

## Contents

```
Singapore/
├── README.md                          # This file
├── source/                            # Source documents (PDFs)
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews and analyses
    ├── 01-agentic-ai-governance-framework.md    # Earlier analysis
    ├── 02-agent-adoption-guide.md               # Practical deployment guide
    └── review-claude/                           # Claude section-level reviews (7 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (8 documents):

### National strategy
- **National AI Strategy 2.0** (December 2023) — 3 systems, 10 enablers, 15 actions; "AI for the Public Good"

### Governance frameworks
- **Model AI Governance Framework, Second Edition** (January 2020) — foundational; 4 pillars; voluntary
- **Model AI Governance Framework for Generative AI** (June 2024) — 9 dimensions; shared responsibility model
- **Model AI Governance Framework for Agentic AI** (January 2026) — 4 pillars for agentic systems; world's first

### Sector-specific
- **MAS FEAT Principles** (November 2018) — Fairness, Ethics, Accountability, Transparency in financial services AI
- **PDPC Advisory Guidelines on Use of Personal Data in AI** (March 2024)

### Regional
- **ASEAN Guide on AI Governance and Ethics** (2024)
- **Expanded ASEAN Guide on AI Governance for GenAI** (January 2025)

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Seven document-level reviews following the structure set out in [`../methodology.md`](../methodology.md).

| # | Date | Review |
|---|------|--------|
| 04 | Nov 2018 | [MAS FEAT Principles](analysis/review-claude/04-mas-feat-principles.md) |
| 01 | Jan 2020 | [Model AI Governance Framework (2nd Ed)](analysis/review-claude/01-model-ai-governance-framework-2020.md) |
| 03 | Dec 2023 | [National AI Strategy 2.0](analysis/review-claude/03-national-ai-strategy-2.0.md) |
| 05 | Mar 2024 | [PDPC Advisory Guidelines on Personal Data in AI](analysis/review-claude/05-pdpc-advisory-guidelines-ai.md) |
| 02 | Jun 2024 | [Model AI Governance Framework for GenAI](analysis/review-claude/02-model-ai-governance-framework-genai-2024.md) |
| 06 | 2024 | [ASEAN Guide on AI Governance and Ethics](analysis/review-claude/06-asean-guide-ai-governance.md) |
| 07 | Jan 2025 | [Expanded ASEAN Guide — Generative AI](analysis/review-claude/07-expanded-asean-guide-genai.md) |

### Earlier analyses — [`analysis/`](analysis/)

Two analyses produced before the review-claude methodology was applied:

- [Agentic AI Governance Framework (January 2026)](analysis/01-agentic-ai-governance-framework.md) — first national-level governance document for agentic AI globally
- [Practical Guide to Adopting AI Agents Responsibly](analysis/02-agent-adoption-guide.md) — operational deployment guide based on the agentic framework

## Key findings across the Singapore landscape

1. **Entirely voluntary governance stack.** No standalone AI legislation. No prohibited practices, no binding transparency obligations, no AI-specific penalties. Governance operates through voluntary frameworks, sector regulators (MAS, PDPC, HSA), and adjacent law (PDPA).

2. **Three-generation governance framework.** Model Framework 2020 (traditional AI) → GenAI Framework 2024 (generative AI, 9 dimensions) → Agentic AI Framework 2026 (agentic systems, 4 pillars). Each generation builds on the previous while addressing new risks — a layered, evolutionary approach without breaking changes.

3. **Practical testing infrastructure is distinctive.** AI Verify (governance testing toolkit, open-source, 90+ corporate members) and Project Moonshot (LLM red-teaming) are tangible tools that most jurisdictions lack. This positions Singapore as the jurisdiction that builds governance tools, not just governance documents.

4. **Shared responsibility model for GenAI.** The GenAI Framework's adaptation of cloud computing shared-responsibility models to AI development chains (model developer → application deployer → cloud provider → end-user) is a practical allocation framework.

5. **"Food labels" disclosure concept.** Standardised model transparency covering data, training infrastructure, evaluation, mitigations, risks, intended use, and user data protection — memorable framing with practical utility.

6. **International positioning as governance thought-leader.** Singapore's frameworks are reference documents for ASEAN Guide on AI Governance, have influenced OECD work, and are cited by multiple jurisdictions. AI Verify Foundation provides the community anchor.

7. **No GPAI-specific provisions or compute thresholds.** Unlike the EU AI Act, Singapore does not classify models by compute, does not define systemic risk categories, and does not require incident reporting on specified timelines.

## Position in comparative landscape

Singapore's approach is philosophically distinct from both the EU and UK:

- **vs EU**: Singapore is voluntary where the EU is binding; Singapore has no risk tiers, no prohibited practices, no GPAI chapter, no penalties; Singapore has better practical testing infrastructure
- **vs UK**: Both non-statutory, but the UK has AISI (100+ researchers, £240M) for frontier safety evaluation; Singapore has AI Verify Foundation and Digital Trust Centre (S$50M) focused on governance testing rather than frontier evaluation; UK has more documents but Singapore's are more systematically layered
- **vs Switzerland**: Both voluntary, both sector-regulator-led; Singapore is more operationally specified; Switzerland faces EU equivalence pressure that Singapore does not
- **Unique strengths**: world's first agentic AI governance framework; AI Verify testing toolkit; ASEAN regional influence; three-generation governance stack; practical "food labels" concept
