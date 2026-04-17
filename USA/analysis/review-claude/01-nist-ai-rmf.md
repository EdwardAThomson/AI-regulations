# NIST AI Risk Management Framework (AI RMF 1.0) — Review

**Document:** Artificial Intelligence Risk Management Framework (AI RMF 1.0), NIST AI 100-1
**Published:** January 2023
**Issuing body:** National Institute of Standards and Technology (NIST), U.S. Department of Commerce
**Legal status:** Voluntary; non-binding; designed to be sector-agnostic and use-case-agnostic
**Length:** ~42 pages + appendices
**Mandated by:** National Artificial Intelligence Initiative Act of 2020 (P.L. 116-283)
**Companion:** AI RMF Playbook (online, regularly updated)

---

## Summary

The NIST AI RMF is the **foundational voluntary AI governance framework in the United States** and arguably the most widely referenced AI risk management framework globally. It is designed for organisations of all sizes across all sectors, offering a structured approach to identifying, assessing, and managing AI risks throughout the AI system lifecycle. The Framework comprises two parts: Part 1 provides foundational information on AI risk, trustworthiness characteristics, and challenges; Part 2 defines the **Core** — four functions (**GOVERN, MAP, MEASURE, MANAGE**) broken into categories and subcategories. The RMF is explicitly voluntary, rights-preserving, and intended as a living document with formal community review planned no later than 2028.

**Political significance:** The AI RMF is the most durable US AI governance instrument, surviving the Biden-to-Trump administration transition intact (though the July 2025 AI Action Plan directs NIST to revise it to remove references to "misinformation, DEI, and climate change"). Its bipartisan origins (National AI Initiative Act of 2020, signed under Trump's first term) and NIST's institutional independence give it stability that executive orders lack.

---

## Key Points

### Seven Trustworthiness Characteristics (Part 1)

The RMF identifies seven characteristics of trustworthy AI systems:

1. **Valid and Reliable** — necessary condition and base for all others; system performs as intended under expected and unexpected conditions
2. **Safe** — conditions where AI systems operate within acceptable risk levels, and do not endanger human life, health, property, or the environment
3. **Secure and Resilient** — ability to maintain confidentiality, integrity, and availability; resilience to adversarial attacks
4. **Accountable and Transparent** — cross-cutting characteristic relating to all others; includes documentation, auditability, and clear assignment of responsibility
5. **Explainable and Interpretable** — explainability (representation of reasons for AI output) and interpretability (meaning of outputs in context of designed functional purpose)
6. **Privacy-Enhanced** — human autonomy and dignity through data protection; values and principles for data collection, use, and governance
7. **Fair — with Harmful Bias Managed** — equity and equality in AI; managing bias across all stages of the lifecycle

Valid & Reliable is positioned as the foundation (necessary condition); Accountable & Transparent as the vertical cross-cutting dimension connecting all others.

### Four Core Functions (Part 2)

#### GOVERN (cross-cutting)
Cultivates and implements a culture of risk management across the organisation. Applies to all stages and functions. Categories include:
- GV-1: Policies reflecting risk management commitments
- GV-2: Accountability structures established
- GV-3: Workforce diversity, equity, inclusion, and accessibility
- GV-4: Organisational teams committed to culture of risk management
- GV-5: Processes for ongoing engagement with relevant AI actors
- GV-6: Policies and procedures addressing AI risks from third-party entities

#### MAP
Establishes context for the AI system. Identifies and documents risks. Categories include:
- MP-1: Context established and understood
- MP-2: Categorisation of AI system
- MP-3: AI risks and benefits mapped for all components
- MP-4: Risks and benefits mapped to affected communities
- MP-5: Likelihood and magnitude of each risk assessed

#### MEASURE
Analyses, assesses, benchmarks, and monitors AI risk and related impacts. Categories include:
- MS-1: Appropriate methods and metrics identified
- MS-2: AI system evaluated and results documented
- MS-3: Mechanisms for tracking identified risks over time
- MS-4: Feedback about efficacy of measurement approaches

#### MANAGE
Allocates risk resources; develops plans for risk response. Categories include:
- MN-1: Plans for prioritised risks
- MN-2: Strategies to maximise AI benefits and minimise negative impacts
- MN-3: Risks from third-party entities managed
- MN-4: Risk treatments documented, with residual risks communicated

### Key Design Principles

- **Risk-based, not compliance-based** — organisations determine their own risk tolerance
- **Lifecycle approach** — risk management throughout design, development, deployment, operation
- **Socio-technical framing** — AI systems are inherently socio-technical; risk emerges from interplay of technical and societal factors
- **Unacceptable risk**: "In cases where an AI system presents unacceptable negative risk levels — such as where significant negative impacts are imminent, severe harms are actually occurring, or catastrophic risks are present — development and deployment should cease in a safe manner until risks can be sufficiently managed."
- **Residual risk** — must be documented and communicated to end users
- **Organisational integration** — AI risk management should integrate into broader enterprise risk management

### Relationship to International Frameworks

The RMF explicitly references and aligns with:
- **OECD AI Principles** (2019) and OECD Framework for Classification of AI Systems (2022)
- **ISO 31000:2018** (Risk Management)
- **ISO/IEC 22989:2022** (AI Concepts and Terminology)
- **ISO/IEC TR 24368:2022** (Ethical and Societal Concerns)
- **ISO 26000:2010** (Social Responsibility)

The RMF's four-function structure (Govern, Map, Measure, Manage) influenced the EU AI Act's quality management system requirements and Singapore's AI Verify testing framework.

---

## Observations

### Clarity

Exceptionally well-structured. The four-function framework is intuitive, memorable, and comprehensive. The trustworthiness characteristics provide a clear vocabulary. Appendices add practical depth.

Clarity strengths:
- GOVERN as cross-cutting function is a strong design choice — governance infuses all other activities
- The lifecycle and key dimensions diagram (adapted from OECD) is widely reproduced
- Clear distinction between explainability and interpretability
- Honest about challenges: risk measurement limitations, inscrutability, human baselines

Clarity weaknesses:
- No prescriptive requirements — everything is contextual
- No pass/fail criteria or minimum standards
- Subcategories use aspirational language ("should," "can") throughout

### Measurability

The RMF explicitly acknowledges the measurement challenge: "The current lack of consensus on robust and verifiable measurement methods for risk and trustworthiness, and applicability to different AI use cases, is an AI risk measurement challenge." The MEASURE function provides a structure for measurement but not the measurements themselves.

### Gaps

**No binding obligations.** Entirely voluntary — even more explicitly so than Singapore's frameworks, which at least carry industry expectation.

**No prohibited practices.** The RMF does not identify any AI use that should not occur, though it acknowledges that "development and deployment should cease" when unacceptable risks are present.

**No GPAI-specific provisions.** Pre-dates the GPAI governance discussion. NIST AI 600-1 (GenAI Profile, July 2024) partially addresses this.

**No enforcement mechanism.** No regulator, no penalties. The RMF is a self-governance tool.

**Political vulnerability.** The July 2025 AI Action Plan directs NIST to "revise the NIST AI Risk Management Framework to eliminate references to misinformation, Diversity, Equity, and Inclusion, and climate change." This instruction to remove specific content from a technical framework based on political rather than technical grounds is unprecedented for NIST and raises questions about the RMF's continued technical independence.

### Feasibility

Highly feasible as a self-governance framework. The four-function structure can be adopted by organisations of any size. The companion Playbook provides implementation guidance. The RMF is already widely adopted in US industry and referenced internationally.

### International Alignment

The RMF is the most internationally referenced US AI governance instrument:
- Referenced in the **UK's Pro-Innovation Consultation Response** as one of several international frameworks
- Referenced in the **CMA Foundation Models report**
- Aligned with **OECD** principles and classification frameworks
- Compatible with **ISO/IEC AI standards**
- Influenced **Singapore's AI Verify** testing framework structure
- Referenced in the **EU AI Act** impact assessment

---

## Overall Assessment

The NIST AI RMF is the **gold standard for voluntary AI risk management frameworks globally**. Its four-function structure, seven trustworthiness characteristics, and lifecycle approach provide a comprehensive and practical governance scaffold. It is sector-agnostic, scale-agnostic, and internationally aligned.

Its greatest strength is **durability**: mandated by bipartisan legislation, maintained by NIST's institutional infrastructure, and widely adopted across sectors. It has survived one administration transition and will likely survive future ones.

Its greatest weakness is **voluntariness**: without binding force, adoption is uneven and accountability is limited. The political direction to revise its content (July 2025 AI Action Plan) raises new concerns about whether the RMF will remain a technically independent document.

For UK-based firms:
1. The NIST AI RMF is a useful complement to EU AI Act compliance and UK governance frameworks. Its four-function structure maps cleanly onto most internal governance architectures.
2. If you serve US clients, RMF alignment is the expected governance standard.
3. The GOVERN-MAP-MEASURE-MANAGE framework can serve as the internal scaffold on which jurisdiction-specific obligations (EU AI Act, UK principles, Singapore frameworks) are layered.

---

## Sources

- [NIST AI RMF 1.0 (PDF)](../../source/NIST-AI-RMF-1.0-Jan-2023.pdf)
- [NIST AI RMF website and Playbook](https://www.nist.gov/itl/ai-risk-management-framework)
- National Artificial Intelligence Initiative Act of 2020 (P.L. 116-283)
- Related reviews:
  - [US Executive Orders and AI Action Plan (review 02)](02-executive-orders-and-action-plan.md) — the political overlay on the NIST framework
  - [Singapore Model AI Governance Framework (SG review 01)](../../Singapore/analysis/review-claude/01-model-ai-governance-framework-2020.md) — comparable voluntary framework
  - [EU HLEG Ethics Guidelines (EU review 08)](../../EU/analysis/review-claude/08-ethics-guidelines-trustworthy-ai-2019.md) — comparable foundational framework
