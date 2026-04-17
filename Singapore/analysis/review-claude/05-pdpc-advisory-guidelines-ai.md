# PDPC Advisory Guidelines on Use of Personal Data in AI — Review

**Document:** Advisory Guidelines on Use of Personal Data in AI Recommendation and Decision Systems
**Published:** 1 March 2024
**Issuing body:** Personal Data Protection Commission (PDPC), Singapore
**Legal status:** Advisory; non-binding; does not modify PDPA
**Length:** ~19 pages
**Legal basis:** Personal Data Protection Act 2012 (PDPA)

---

## Summary

These Guidelines clarify how Singapore's PDPA applies to the collection, use, and disclosure of personal data in AI systems — covering the full lifecycle from development and training through deployment and procurement. The central contribution is providing **legal certainty** on two consent exceptions that enable AI development without individual consent: the **Business Improvement Exception** (for enhancing existing products/services) and the **Research Exception** (for commercial research with public benefit, e.g., precision medicine). The Guidelines also set expectations for transparency, accountability, and data protection when deploying AI systems that use personal data to make recommendations, predictions, or decisions.

---

## Key Points

### Three Lifecycle Stages

**Part III — Development, Testing, and Monitoring**
- Organisations may use personal data to train AI systems without individual consent under two PDPA exceptions:
  - **Business Improvement Exception**: applicable when enhancing existing products/services, improving operational efficiency, or personalising offerings. Permits interdepartmental and intra-group sharing.
  - **Research Exception**: applicable for commercial research with public benefit (e.g., precision medicine, population health). More restrictive; research purpose must be genuine.
- Data protection considerations: anonymisation, data minimisation, purpose limitation, retention limits

**Part IV — Deployment (B2C)**
- PDPA applies fully to collection and use of personal data in deployed AI systems
- **Consent and notification**: organisations must provide sufficient information at point of collection for meaningful consent. Should explain whether AI is used in decision-making and, where outcomes have high impact, explain how the AI system works in non-technical language.
- **Accountability**: organisations should include in written data protection policies information about safeguards ensuring AI trustworthiness, especially for high-impact decisions

**Part V — Procurement (B2B)**
- Service Providers developing bespoke AI systems are **data intermediaries** under PDPA
- Obligations: Protection and Retention Obligations apply
- Good practices: data mapping, labelling, provenance records
- Service Providers should guard against unauthorised modification of personal data during processing

### Practical Guidance

- Organisations encouraged to conduct **data protection impact assessments** before deploying AI systems using personal data
- Organisations encouraged to use **AI Verify** for governance testing
- Transparency is emphasised: explain AI use to consumers at collection point; include AI governance practices in published data protection policies
- High-impact AI decisions (credit, employment, healthcare) warrant more detailed transparency and accountability measures

---

## Observations

### Comparison with EU and UK

- **EU**: GDPR Article 22 provides a right not to be subject to solely automated decisions with legal/significant effects (with exceptions). The EU AI Act layers additional obligations for high-risk AI. Singapore's PDPA has no equivalent to Article 22 — instead, it relies on accountability and transparency principles.
- **UK**: DUAA 2025 relaxed Article 22 UK GDPR, moving closer to Singapore's permit-with-safeguards model. Singapore's approach predates and conceptually resembles the UK's post-DUAA position.

### Value of the Business Improvement Exception

The Business Improvement Exception is practically significant: it allows firms to use existing customer data to train AI systems that improve their products/services without going back for fresh consent. This removes a major friction point for AI adoption that exists under GDPR (where the legal basis for training on existing personal data is contested). Singapore's clarification is pragmatic and business-enabling.

### Gaps

- Advisory only — no enforcement consequences for non-compliance with the Guidelines (PDPA itself remains enforceable)
- No specific thresholds for what constitutes "high impact" AI decisions requiring enhanced transparency
- Does not address generative AI specifically (published March 2024, pre-dating the GenAI Framework by 3 months)

---

## Sources

- [PDPC Advisory Guidelines on Use of Personal Data in AI (PDF)](../../source/PDPC-Advisory-Guidelines-Personal-Data-AI-Mar-2024.pdf)
- [PDPC website](https://www.pdpc.gov.sg)
- Related reviews:
  - [Model AI Governance Framework 2020 (review 01)](01-model-ai-governance-framework-2020.md) — cross-sectoral governance
  - [Model AI Governance Framework for GenAI (review 02)](02-model-ai-governance-framework-genai-2024.md) — data dimension covers similar territory
  - [UK DUAA 2025](../../UK/analysis/review-claude/14-data-use-and-access-act.md) — UK's post-GDPR data protection reform
