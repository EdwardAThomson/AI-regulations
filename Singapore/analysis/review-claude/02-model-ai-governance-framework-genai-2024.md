# Model AI Governance Framework for Generative AI (2024) — Review

**Document:** Model AI Governance Framework for Generative AI
**Published:** June 2024 (at IMDA/AI Verify Foundation event)
**Issuing body:** Infocomm Media Development Authority (IMDA) and AI Verify Foundation, Singapore
**Legal status:** Voluntary; non-binding; "living document"
**Length:** ~35 pages
**Builds on:** Model AI Governance Framework (2020); Discussion Paper on Generative AI (June 2023)
**Contributors:** ~70 organisations across industry (Adobe, Anthropic, Google, Meta, Microsoft, OpenAI, AWS, Mastercard, SAP, etc.), government (including US Department of Commerce), research institutions, and associations

---

## Summary

This framework extends Singapore's voluntary AI governance approach from traditional AI (covered by the 2020 Model Framework) to generative AI. It is organised around **nine dimensions** — Accountability, Data, Trusted Development and Deployment, Incident Reporting, Testing and Assurance, Security, Content Provenance, Safety and Alignment R&D, and AI for Public Good — each addressing a specific governance concern. The framework is ecosystem-oriented: it assigns responsibilities across the development chain (model developers, application deployers, cloud service providers, end-users) rather than treating AI governance as a single organisation's problem. It is explicitly non-binding and designed to evolve as technology and policy develop. Notable features include a "food labels" disclosure concept for model transparency, a shared-responsibility model adapted from cloud computing, and concrete mention of AI safety institute cooperation (UK, US, Japan, Singapore).

---

## Key Points

### Nine Dimensions

#### 1. Accountability
- **Shared responsibility model** adapted from cloud computing: allocate responsibility based on level of control each stakeholder has in the development chain
- **Ex ante** (upfront): model developers, application deployers, and cloud providers each take responsibility for their layer. Model type matters (closed-source vs open-weights vs open-source)
- **Ex post** (safety nets): industry-led indemnity (e.g., copyright indemnification by Adobe, Anthropic, Google, Microsoft, OpenAI); legal frameworks for emerging risks (references EU AI Liability Directive); no-fault insurance as residual safety net
- Open-weights models place greater responsibility on application deployers who can modify them

#### 2. Data
- **Personal data**: clarify how existing data protection law applies to GenAI; Privacy Enhancing Technologies (PETs) as emerging enabler
- **Copyright**: balanced approach acknowledging competing interests (creators seeking remuneration; developers arguing training doesn't copy expression; practical challenges of consent from all copyright owners). No prescriptive position — calls for open dialogue
- **Data quality**: data governance best practices (annotation, debiasing, removing inappropriate content); expansion of trusted datasets including culturally representative data for low-resource languages

#### 3. Trusted Development and Deployment
- **Development**: baseline safety practices (RLHF, RAG, input/output filters, few-shot learning)
- **Disclosure ("food labels")**: standardised transparency for all models covering:
  - Data used (training sources, processing)
  - Training infrastructure (including environmental impact)
  - Evaluation results
  - Mitigations and safety measures
  - Risks and limitations
  - Intended use
  - User data protection
- Greater transparency to government for models with national security or societal implications — "space for policymakers to define the model risk thresholds"
- **Evaluation**: benchmarking + red teaming; acknowledges both fall short of comprehensive safety assessment. References AI Verify Foundation's "Cataloguing LLM Evaluations" (October 2023) as starting point for standardised safety evaluations

#### 4. Incident Reporting
- **Vulnerability reporting**: adapt CVE-style bug-bounty programmes for AI safety vulnerabilities; 90-day patch window
- **Incident reporting**: internal processes for timely notification and remediation; materiality threshold for formal reporting; align with existing sector-specific regimes (telecoms, finance, cybersecurity)
- References EU AI Act's Article 73 serious-incident reporting (15 days for providers of high-risk AI systems) as one reference point
- Proportionate and context-specific — not a one-size-fits-all regime

#### 5. Testing and Assurance
- **How to test**: standardised benchmarks and methodologies; common tooling; eventual codification through ISO/IEC and IEEE
- **Who to test**: independent third-party testers; accreditation mechanism for competency and independence
- Third-party testing provides external validation complementing internal testing

#### 6. Security
- **Adapt security-by-design** for GenAI: natural-language input creates new attack surfaces; probabilistic outputs challenge traditional evaluation
- **New tools needed**: input filters/moderation, digital forensics for GenAI, adversarial threat modelling (MITRE ATLAS referenced)
- Distinguish traditional software security concerns (addressed by current approaches) from novel AI-model threat vectors

#### 7. Content Provenance
- **Digital watermarking** (SynthID, Stable Signature) and **cryptographic provenance** (C2PA standard) as technical solutions for AI-generated content identification
- Limitations acknowledged: provenance can be stripped; consumer understanding is low; malicious actors will circumvent
- Publisher support critical — most content consumed through social media, browsers, media outlets
- Standardise types of edits to be labelled (fully AI-generated vs partially modified)
- Complementary enforcement mechanisms likely needed alongside technical solutions

#### 8. Safety and Alignment R&D
- "Forward alignment" (developing more aligned models — RLAIF, Constitutional AI) and "backward alignment" (post-training evaluation — emergent capability testing, mechanistic interpretability)
- **AI Safety Institutes** (UK, US, Japan, Singapore's Digital Trust Centre — S$50M investment) as positive development for R&D acceleration
- Global cooperation needed to optimise limited talent and resources
- Systematically map research directions; prioritise collectively; share results

#### 9. AI for Public Good
Four touchpoints:
- **Democratising access**: digital literacy; human-centric design; SME support (Generative AI Sandbox)
- **Public service delivery**: coordinated government AI adoption; AI developers help identify public-sector use cases
- **Workforce**: concerted upskilling; redesign jobs; develop training programmes; core skills (creativity, critical thinking, complex problem-solving) alongside AI-specific skills
- **Sustainability**: track and measure carbon footprint of GenAI training/inference; green computing R&D; energy-efficient data centres

---

## Observations

### Clarity

Excellent structure. Nine dimensions are clearly labelled and each follows a consistent "context → design → examples/references" pattern. The "food labels" analogy for model disclosure is memorable and implementable.

Clarity strengths:
- Shared-responsibility model adapted from cloud computing gives deployers a familiar mental model
- Concrete references (CVE for vulnerability reporting, C2PA for content provenance, EU AI Act for incident reporting)
- Contributor list demonstrates genuine multi-stakeholder input

Clarity weaknesses:
- No prescriptive requirements — everything is framed as "design considerations" or "there is value in..."
- The framework deliberately avoids taking positions on contested issues (copyright, risk thresholds) — diplomatic but unhelpful for compliance
- "Model risk thresholds" for additional oversight are mentioned but not defined

### Measurability

Minimal. No quantitative thresholds, no certification standards, no compliance metrics. The "food labels" concept is directionally useful but the baseline content is not specified. Testing and assurance calls for standardisation but defers to future work.

### Gaps

**No binding obligations.** Entirely voluntary — no mechanism to compel adoption or enforce compliance.

**Copyright approach is deliberately inconclusive.** Acknowledges competing interests but does not take a position. Contrast with EU GPAI Code of Practice's Copyright chapter.

**Risk thresholds mentioned but not defined.** The framework notes "space for policymakers to define the model risk thresholds, above which additional oversight measures would apply" but does not propose any. No FLOP-based classification, no capability-based classification, no deployment-scale classification.

**Open-weights governance under-specified.** Notes that open-weights models shift responsibility to deployers but does not specify what deployer obligations should look like.

**No prohibited practices.** No AI use is prohibited under this framework.

**Enforcement absent.** No regulator, no penalties, no conformity assessment.

### Feasibility

Highly feasible as a voluntary governance reference. The nine dimensions map to functions most large organisations already have (security, data governance, incident management, testing). SME applicability is supported by the AI for Public Good dimension's Generative AI Sandbox.

### Internal Consistency

Internally consistent. The nine dimensions cover the GenAI lifecycle from development through deployment, incident management, and societal impact. The shared-responsibility model in Dimension 1 (Accountability) creates a framework for allocating obligations across the remaining eight dimensions.

### International Alignment

Deliberately positioned at the intersection of multiple international frameworks:
- **EU AI Act**: explicitly referenced for incident reporting; acknowledged as one approach to risk-based regulation
- **OECD**: referenced for incident definitions and privacy principles
- **US**: references White House Voluntary Commitments; US Department of Commerce listed as contributor
- **UK**: references UK AISI; UK copyright code of practice mentioned
- **C2PA**: for content provenance (Adobe, Microsoft-led)
- **ISO/IEC, IEEE**: for eventual standards codification

Singapore positions this framework as a multilateral reference point — useful for international dialogue without committing to any single jurisdiction's approach.

---

## Overall Assessment

The GenAI Framework extends Singapore's practical, voluntary, multi-stakeholder governance approach to generative AI. Its nine dimensions cover the full ecosystem — from accountability allocation through development, deployment, incident management, security, content provenance, safety R&D, and public good.

Its greatest strength is **ecosystem thinking**: the shared-responsibility model, the multi-stakeholder contributor base, and the attention to the full development chain (model developer → deployer → cloud provider → end-user) reflect the reality that GenAI governance is not a single-organisation problem.

Its greatest weakness is the same as the 2020 Model Framework: **voluntary non-specificity**. No obligations, no thresholds, no enforcement. The framework is a sophisticated conversation-starter rather than a compliance framework.

For UK-based firms:

1. **The framework is useful as an internal governance reference**, particularly the nine-dimension structure and the "food labels" disclosure concept.

2. **If you serve Singapore-based enterprise clients**, the framework establishes the expected governance vocabulary. Alignment with the nine dimensions demonstrates responsible AI use.

3. **The shared-responsibility model** is a useful framing for contractual allocation of AI-related responsibilities between model providers, deployers, and cloud infrastructure providers.

4. **For compliance, the EU AI Act remains the binding floor.** Singapore's framework complements but does not substitute for binding obligations in jurisdictions where they apply.

---

## Sources

- [Model AI Governance Framework for Generative AI (PDF)](../../source/Model-AI-Governance-Framework-GenAI-Jun-2024.pdf)
- [IMDA AI Governance page](https://www.imda.gov.sg/how-we-can-help/ai-governance)
- [AI Verify Foundation](https://aiverifyfoundation.sg)
- Related reviews:
  - [Model AI Governance Framework 2020 (review 01)](01-model-ai-governance-framework-2020.md) — the foundational framework this extends
  - [Agentic AI Governance Framework (analysis 01)](../01-agentic-ai-governance-framework.md) — the 2026 extension for agentic systems
  - [EU GPAI Code of Practice (EU review 05)](../../EU/analysis/review-claude/05-gpai-code-of-practice.md) — binding counterpart for GPAI governance
  - [EU Transparency Code (EU review 07)](../../EU/analysis/review-claude/07-transparency-code-ai-generated-content.md) — operationalises content provenance/labelling obligations
