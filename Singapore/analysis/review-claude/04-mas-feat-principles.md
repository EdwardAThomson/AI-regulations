# MAS FEAT Principles — Review

**Document:** Principles to Promote Fairness, Ethics, Accountability and Transparency (FEAT) in the Use of Artificial Intelligence and Data Analytics in Singapore's Financial Sector
**Published:** 12 November 2018 (MAS); this source is a PwC analysis published December 2018
**Issuing body:** Monetary Authority of Singapore (MAS)
**Legal status:** Non-binding principles; supervisory expectations
**Length:** 14 principles across 4 areas (the PwC analysis is 9 pages)
**Sector:** Financial services (banks, asset managers, insurance companies)

---

## Summary

MAS published the FEAT Principles as the first financial-sector-specific AI governance framework in Singapore. The 14 principles are organised around four pillars — Fairness (4 principles), Ethics (2), Accountability (5), and Transparency (3). They are non-binding but establish MAS's supervisory expectations for firms using AI and data analytics (AIDA). The principles apply when firms assess existing or develop new internal governance frameworks for AIDA, calibrated to the materiality of AIDA-driven decisions. MAS later complemented these with the FEAT Assessment Methodology and the Veritas toolkit for validation.

**Note:** The collected source is a PwC Singapore analysis of the MAS Principles, not the MAS document itself. This review draws on both the PwC analysis and the underlying MAS principles it summarises.

---

## Key Points

### The 14 FEAT Principles

**Fairness (4 principles)**
1. Individuals/groups not systematically disadvantaged by AIDA-driven decisions unless justified
2. Use of personal attributes as input factors is justified
3. Data and models regularly reviewed for accuracy, relevance, and to minimise unintentional bias
4. AIDA-driven decisions regularly reviewed to ensure models behave as designed

**Ethics (2 principles)**
5. Use of AIDA aligned with firm's ethical standards, values, and codes of conduct
6. AIDA-driven decisions held to at least the same ethical standards as human-driven decisions

**Accountability (5 principles)**
7. Use of AIDA approved by appropriate internal authority
8. Firms accountable for both internally developed and externally sourced AIDA models
9. Firms proactively raise management and Board awareness of AIDA use
10. Data subjects provided channels to enquire, appeal, and request reviews of AIDA-driven decisions
11. Verified and relevant supplementary data from data subjects taken into account in reviews

**Transparency (3 principles)**
12. Use of AIDA proactively disclosed to data subjects
13. Data subjects provided, upon request, clear explanations of data used and how it affects decisions
14. Data subjects provided, upon request, clear explanations of consequences of AIDA-driven decisions

### Sector-Specific Implementation Guidance (PwC analysis)

The PwC analysis maps the principles to practical actions for three financial sub-sectors:

- **Banks**: simulation tools for online banking channels using AIDA; processes for client recourse/explanation
- **Asset managers**: detailed documentation of AIDA-based trading/portfolio risk models; explainable robo-advice; data/model governance before further AIDA rollout
- **Insurance**: simulation tools for underwriting/claims; investigation of models for bias; client recourse processes

**Overarching actions** for all financial firms:
- Data governance framework (ownership, architecture, quality criteria, model governance)
- Internal accountability and oversight for AIDA-driven decisions
- Documentation of all AI models (including libraries and input data)
- Explainability techniques evaluation (especially for deep learning)
- AI-specific risk clarification and additional controls
- AIDA solutions covered by outsourcing registry and governance

---

## Observations

### Comparison with UK FCA and Switzerland FINMA

The FEAT Principles, UK FCA AI Update (April 2024), and FINMA Guidance 08/2024 share a common approach: principle-based, proportionate, technology-neutral, operating within existing supervisory frameworks. Key differences:

- **MAS FEAT** (2018): earliest of the three; most structured (14 named principles in 4 categories); subsequently supplemented by dedicated testing toolkit (Veritas)
- **FCA AI Update** (2024): maps government's 5 principles onto existing FCA frameworks without adding AI-specific requirements
- **FINMA Guidance** (2024): 7 assessment areas based on supervisory findings; most concrete (describes what FINMA actually observed and assessed)

All three rely on existing supervisory authority rather than AI-specific legislation. For firms operating across all three jurisdictions, the principles are compatible — a governance framework satisfying FEAT likely satisfies FCA and FINMA expectations, with minor mapping adjustments.

### Gaps

- No definition of "justified" differentiation vs "unjustified" bias — left to firm interpretation
- Limited guidance on recourse channels, review criteria, and what constitutes "verified and relevant supplementary data"
- Pre-generative AI (2018) — does not address foundation model, chatbot, or generative AI scenarios in financial services
- No quantitative thresholds or pass/fail criteria

---

## Sources

- [MAS FEAT Principles — PwC analysis (PDF)](../../source/MAS-FEAT-Principles-Nov-2018.pdf)
- [MAS FEAT Principles — original publication](https://www.mas.gov.sg/publications/monographs-or-information-paper/2018/FEAT)
- Related reviews:
  - [UK FCA AI Update](../../UK/analysis/review-claude/12-fca-ai-update.md) — UK financial-sector comparator
  - [Switzerland FINMA Guidance 08/2024](../../Switzerland/analysis/review-claude/02-finma-guidance-ai-governance.md) — Swiss financial-sector comparator
  - [Model AI Governance Framework 2020 (review 01)](01-model-ai-governance-framework-2020.md) — cross-sectoral framework FEAT complements
