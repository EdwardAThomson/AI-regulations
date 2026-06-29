# UAE — AI Governance

The United Arab Emirates has no single comprehensive, binding AI statute. Its position is a
layered patchwork: an ambitious federal strategy (National Strategy for AI 2031) and a
voluntary 12-principle ethics Charter (June 2024) sitting over generally applicable federal
laws (data protection, copyright, cybercrime); emirate-level strategies and bodies in Dubai
and Abu Dhabi; and independent common-law financial free zones (DIFC, ADGM) that contain the
most concrete binding AI-adjacent rules. Sector regulators (the Central Bank, SCA, health
authorities) add expectations on top. The defining theme is the state as an aggressive
adopter of AI: the world's first AI minister (2017), Chief AI Officers across government, AI
sitting as an advisory member of Cabinet from January 2026, and AI used to assist legislative
drafting. The posture is pro-innovation and adoption-led rather than restriction-led.

This directory collects the source documents and reviews that map that position.

## Note

- This material is for research and comparison only, not legal advice.
- The UAE's free zones (DIFC, ADGM) operate independent legal systems; their rules are not
  "federal UAE law" and should be treated as distinct sub-jurisdictions.
- Reviews in this directory are produced or assisted by AI and may contain mistakes or
  outdated interpretations; important points should be checked against the primary sources.

## Contents

```
UAE/
├── README.md                          # This file
├── source/                            # Source documents (PDFs)
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews and analyses (not yet started)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory, with collection
status and direct links to primary documents.

### Federal strategy and ethics
- **National Strategy for Artificial Intelligence 2031** (Oct 2017) — global AI leadership by
  2031; priority sectors; ties to UAE Centennial 2071.
- **UAE Charter for the Development and Use of AI** (Jun 2024) — voluntary, 12 ethical
  principles (human oversight, safety, bias mitigation, privacy, transparency, accountability).
- **AI Ethics Guide** (Dec 2022) — non-binding federal framework.

### Federal laws of general application (AI-relevant)
- **Federal Decree-Law No. 45 of 2021 (PDPL)** — the de-facto data-protection overlay on AI.
- **Copyright** (Decree-Law 38/2021) and **Cybercrime** (Decree-Law 34/2021) — apply to AI
  outputs and misuse.

### Emirate-level
- **Dubai AI Principles and Ethics Guidelines** (2019) + **AI Ethics Self-Assessment Tool** —
  Digital Dubai; voluntary; four sub-principles (fair, accountable, transparent, explainable).
- **Dubai Universal Blueprint for AI** (Apr 2024) — emirate-wide roadmap; Chief AI Officers;
  regulatory/governance sandbox; AI commercial licence.
- **Abu Dhabi Law No. 3 of 2024** — establishes the AI and Advanced Technology Council (AIATC).

### Financial free zones (binding AI-adjacent rules)
- **DIFC Data Protection Regulation 10** (Sep 2023, full enforcement Jan 2026) — processing
  personal data through autonomous/semi-autonomous systems; notices, AI registers,
  certification, Autonomous Systems Officer for high-risk processing. Definition drawn from
  OECD and EU AI Act concepts. Among the first instruments in the region to regulate AI directly.
- **ADGM Data Protection Regulations** (2021, amended 2024/2025) — automated decision-making,
  algorithmic transparency, human oversight; FSRA guidance on big-data analytics and AI.

### Sector: financial services
- **CBUAE Guidance on Responsible Use of AI and ML** (Feb 2026) — non-binding expectations for
  licensed financial institutions: documented governance, risk management, fairness, testing,
  transparency (Arabic + English), consumer right to human review, human oversight models.

## Analysis

### Completed
- [**Financial services AI governance**](analysis/financial-services-ai-governance.md) —
  the three parallel financial jurisdictions (onshore CBUAE/SCA, DIFC/DFSA, ADGM/FSRA), the
  CBUAE Feb 2026 Guidance Note (full 10-section text), the 2021 joint Enabling Technologies
  Guidelines, and DIFC Regulation 10. Includes a practical obligations checklist and open
  questions for a firm operating in the UAE.

### Candidate review set (following [`../methodology.md`](../methodology.md)):

| # | Suggested review | Priority |
|---|------------------|----------|
| 01 | National Strategy for AI 2031 | High |
| 02 | UAE Charter for the Development and Use of AI (Jun 2024) | High |
| 03 | DIFC Regulation 10 — autonomous/semi-autonomous systems | High |
| 04 | Dubai AI Principles, Ethics Guidelines and Self-Assessment Tool | Medium |
| 05 | Dubai Universal Blueprint for AI | Medium |
| 06 | Abu Dhabi AIATC (Law No. 3 of 2024) | Medium |
| 07 | ADGM data-protection AI provisions | Medium |
| 08 | CBUAE responsible AI guidance (financial services) | Medium |

## Key features of the UAE landscape

1. **No comprehensive binding AI law.** Federal posture is strategy plus a voluntary Charter,
   layered over generally applicable laws. This places the UAE alongside Singapore and the UK
   in the soft-law, pro-innovation camp rather than the EU's binding-statute camp.

2. **Free zones do the regulatory heavy lifting.** DIFC Regulation 10 and the ADGM regime are
   the only places with concrete, AI-specific binding obligations, and they reach only entities
   established in those zones. This produces meaningful intra-UAE divergence.

3. **State-as-adopter, not state-as-restrictor.** World-first AI minister (2017), Chief AI
   Officers, AI as advisory Cabinet member (Jan 2026), AI-assisted legislative drafting
   (Regulatory Intelligence Office, 2025). Governance is built around accelerating adoption.

4. **Emirate-level fragmentation.** Dubai (Digital Dubai, Universal Blueprint) and Abu Dhabi
   (AIATC) run their own AI strategies and bodies, on top of federal initiatives.

5. **Sector regulators fill gaps.** The Central Bank's 2026 responsible-AI guidance mirrors
   international expectations (governance, fairness, human oversight, redress) without being
   binding, echoing the FINMA / MAS pattern seen elsewhere in this repo.

## Position in comparative landscape

See [The UAE and the soft-law AI jurisdictions](../comparisons/uae-soft-law-comparison.md) for a
full four-way comparison with the UK, Singapore and Switzerland.


- **vs EU**: voluntary and adoption-led where the EU is binding and risk-tiered; no prohibited
  practices, GPAI chapter, or AI-specific penalties at federal level. DIFC Regulation 10 borrows
  EU AI Act and OECD concepts but in a data-protection frame, not a product-safety frame.
- **vs Singapore / UK**: same soft-law, pro-innovation philosophy, but the UAE adds binding
  free-zone rules (DIFC/ADGM) that Singapore and the UK lack, plus a far more pronounced
  state-as-adopter posture.
- **Unique features**: financial free zones as semi-autonomous AI regulators; deepest
  government embedding of AI (Cabinet advisor, legislative drafting); strong sovereign
  compute / model ambitions (TII Falcon, MBZUAI, Stargate UAE) as an industrial-policy backdrop.
