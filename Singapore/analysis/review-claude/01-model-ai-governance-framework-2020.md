# Model AI Governance Framework (Second Edition, 2020) — Review

**Document:** Model AI Governance Framework, Second Edition
**Published:** 21 January 2020 (at World Economic Forum, Davos); First Edition 23 January 2019
**Issuing body:** Personal Data Protection Commission (PDPC) / Infocomm Media Development Authority (IMDA), Singapore
**Legal status:** Voluntary; non-binding; accountability-based framework
**Length:** ~65 pages (including industry illustrations, annexes, acknowledgements)
**Companion documents:** Implementation and Self-Assessment Guide for Organisations (ISAGO); Compendium of Use Cases

---

## Summary

Singapore's Model AI Governance Framework is the **foundational document** in the Singapore AI governance stack. Published first in January 2019 and updated in January 2020, it translates ethical principles into practical, implementable guidance for organisations deploying AI at scale. It is organised around **four pillars**: (1) internal governance structures and measures, (2) determining the level of human involvement in AI-augmented decision-making, (3) operations management, and (4) stakeholder interaction and communication. The framework is explicitly algorithm-agnostic, technology-agnostic, sector-agnostic, and scale-agnostic — designed as a baseline for any organisation. It is voluntary and does not create legal obligations, but adopting it helps organisations demonstrate accountability-based practices aligned with the PDPA and OECD Privacy Principles. The Second Edition added industry examples (CUJO AI, Mastercard, Grab, Suade Labs, DBS Bank, Alibaba, Microsoft, and others) illustrating real-world implementation.

**Historical significance:** This framework predated the EU AI Act by five years and established Singapore as a leading voice in practical, voluntary AI governance. It directly influenced the ASEAN Guide on AI Governance and Ethics (2024) and served as the foundation for the subsequent GenAI Framework (2024) and Agentic AI Framework (2026).

---

## Key Points

### Two Guiding Principles

1. **Explainability, transparency and fairness** — organisations using AI in decision-making should ensure the process is explainable, transparent, and fair, acknowledging that perfect attainment is impossible
2. **Human-centric AI** — AI should amplify human capabilities; protection of human interests, wellbeing, and safety should be primary considerations

### Four Pillars

#### Pillar 1 — Internal Governance Structures and Measures

- Adapt existing or set up new internal governance structures for AI ethics
- Top management and board sponsorship is crucial
- Clear roles and responsibilities (development, deployment, monitoring, stakeholder communication)
- Risk management and internal controls addressing AI-specific risks (data bias, model performance, knowledge transfer, personnel changes)
- Periodic review of governance structures
- **Industry examples**: CUJO AI (Research Board, Architecture Steering Group, PhD-level oversight, Code of Ethics); Mastercard (Governance Council chaired by EVP of AI CoE, with CDO, CPO, CISO, data scientists, and business representatives; initial risk scoring for all AI projects; high-risk referral to Council)

#### Pillar 2 — Determining the Level of Human Involvement

Three approaches to human oversight in AI-augmented decision-making:

1. **Human-in-the-loop** — human retains full control; AI provides recommendations; decisions require affirmative human action (e.g., doctor making final diagnosis based on AI suggestions)
2. **Human-out-of-the-loop** — no human oversight over execution; AI has full control (e.g., product recommendations, demand forecasting)
3. **Human-over-the-loop** (human-on-the-loop) — human in monitoring/supervisory role with ability to intervene (e.g., GPS navigation where driver can alter route)

**Probability-severity matrix** for determining appropriate level: 2×2 grid (low/high severity × low/high probability of harm). Other factors to consider: nature of harm (physical vs intangible), reversibility, availability of recourse, operational feasibility.

For safety-critical systems: always allow human to assume control, with AI providing sufficient information for meaningful decisions or safe shutdown.

**Industry examples**: Suade Labs (human-in-the-loop for regulatory compliance due to domain knowledge requirement; human-over-the-loop for model tuning); Grab (human-out-of-the-loop for trip allocation — 5,000+ per minute makes human review infeasible; low harm from suboptimal allocation)

#### Pillar 3 — Operations Management

Covers the AI model development and deployment lifecycle in three stages:

- **Stage 1 — Data preparation**: data governance, provenance tracking, quality assurance, bias assessment, minimisation, consent management
- **Stage 2 — Model building**: algorithm selection, training, validation, bias testing, repeatability, robustness, reproducibility
- **Stage 3 — Deployment and monitoring**: ongoing performance monitoring, drift detection, threshold triggers, retraining, fallback mechanisms

Key measures include:
- Data lineage and provenance tracking
- Minimisation of personal data use
- Bias detection in datasets and outputs
- Reproducibility and auditability
- Robustness testing (including adversarial scenarios)
- Ongoing monitoring with threshold-based alerts
- Fallback and human override mechanisms

#### Pillar 4 — Stakeholder Interaction and Communication

- **General disclosure**: organisations should generally disclose AI use to individuals, especially when it augments or automates decision-making with significant impact
- **Context-specific communication**: level of disclosure should match the stakeholder and purpose (regulators need technical detail; consumers need plain language)
- **Feedback channels**: establish accessible mechanisms for individuals to provide feedback, raise concerns, or seek recourse regarding AI decisions
- **Internal stakeholders**: employees dealing with AI should understand benefits, risks, and limitations

### Definitions

- **AI**: "a set of technologies that seek to simulate human traits such as knowledge, reasoning, problem solving, perception, learning and planning"
- **AI Solution Providers**: developers of AI solutions/applications
- **Organisations**: companies deploying AI in operations
- **Individuals**: end users, consumers, customers

### Algorithm Audits (Annex B)

Algorithm audits should be conducted **only if necessary** to discover actual operations of algorithms, and **only at the request of a regulator** (as part of forensic investigation). This positions auditing as an investigative tool rather than a routine compliance requirement — lighter than the EU AI Act's conformity assessment approach.

### Annex A — Compilation of Ethical Principles

Reference compilation from various global frameworks. Not all listed principles are addressed in the Model Framework. Organisations encouraged to select principles relevant to their context.

---

## Observations

### Clarity

Exceptionally clear for a governance framework. The four-pillar structure is intuitive. Industry examples (6+ detailed case studies) make abstract guidance concrete. The probability-severity matrix for human oversight is a genuinely useful decision tool.

Clarity strengths:
- Four-agnostic positioning (algorithm, technology, sector, scale) makes it broadly applicable
- Industry examples show real-world implementation by named companies
- Three human-oversight models (in-the-loop, out-of-the-loop, over-the-loop) predate and directly parallel the EU AI Act's Article 14 HITL/HOTL/HIC terminology
- ISAGO companion provides implementation pathway

Clarity weaknesses:
- Voluntary nature means "should" rather than "must" throughout
- No minimum standards — everything is contextual and proportionate
- The framework predates generative AI; examples are traditional ML-focused

### Measurability

Very limited by design. No KPIs, no quantitative thresholds, no certification standards. The probability-severity matrix provides a decision framework but no pass/fail criteria. This is consistent with Singapore's voluntary, accountability-based philosophy.

### Gaps

**Pre-generative AI.** The framework was written before GPT-2 had public impact. Generative AI, foundation models, and GPAI governance are not addressed. The subsequent GenAI Framework (June 2024) and Agentic AI Framework (January 2026) extend coverage.

**No prohibited practices.** No AI use is prohibited. Contrast with EU AI Act Article 5.

**No incident reporting.** No obligation to report AI-related incidents.

**No enforcement mechanism.** Voluntary adoption only. No regulator enforces compliance.

**No extraterritorial reach.** Applies to organisations deploying AI in Singapore; no mechanism to reach foreign providers.

**Limited developer-side obligations.** Framework focuses on deployer organisations; AI solution providers are mentioned but not given specific obligations.

### Feasibility

Highly feasible. The framework is designed for practical adoption by any organisation regardless of size. The ISAGO companion provides a self-assessment tool. Industry examples demonstrate that real companies have implemented the guidance. The main barrier is motivation (voluntary), not capability.

### Internal Consistency

Internally consistent. The four pillars progress logically from governance → decision-making → operations → communication. Each pillar builds on the previous. The probability-severity matrix in Pillar 2 informs the risk management approach in Pillar 3.

### International Alignment

The framework explicitly references:
- EU HLEG Ethics Guidelines (participated in Expert Group)
- OECD AI Principles and OECD Privacy Principles
- FEAT Principles (MAS, Singapore financial sector)
- PDPA (Singapore data protection)
- Various national frameworks compiled in Annex A

The framework's human-oversight terminology (HITL/HOTL/HOOTL) directly parallels and predates the EU AI Act's Article 14 framework. The EU HLEG acknowledged Singapore's Model Framework in its own work.

---

## Overall Assessment

The Model AI Governance Framework is a **well-crafted, practical, globally influential** voluntary governance document. It established Singapore as a pioneer in translating AI ethics from principles to implementable guidance. Its four-pillar structure, probability-severity matrix, and industry examples remain useful today despite the framework's pre-generative-AI vintage.

For UK-based firms:

1. **The framework is a useful self-governance tool** even if you don't serve Singapore. Its accountability-based approach and practical industry examples can inform internal AI governance regardless of jurisdiction.

2. **If you serve Singapore-based clients**, the framework is the expected governance standard. Alignment demonstrates responsible AI use to Singaporean partners and regulators.

3. **The framework is the foundation** for the GenAI Framework (2024) and Agentic AI Framework (2026) — understanding it provides context for Singapore's later, more specific instruments.

4. **Comparison to EU**: Singapore's approach is philosophically opposite to the EU's — voluntary vs binding, accountability-based vs compliance-based, proportionate vs categorical. Both produce workable governance outcomes through different mechanisms.

---

## Sources

- [Model AI Governance Framework, Second Edition (PDF)](../../source/Model-AI-Governance-Framework-2nd-Ed-2020.pdf)
- [PDPC Model AI Governance Framework page](https://www.pdpc.gov.sg/help-and-resources/2020/01/model-ai-governance-framework)
- Related reviews:
  - [Agentic AI Governance Framework (analysis 01)](../01-agentic-ai-governance-framework.md) — 2026 extension for agentic AI
  - [EU HLEG Ethics Guidelines (EU review 08)](../../EU/analysis/review-claude/08-ethics-guidelines-trustworthy-ai-2019.md) — contemporary European equivalent
