# FINMA Guidance 08/2024 — Governance and Risk Management When Using Artificial Intelligence — Review

**Document:** FINMA Guidance 08/2024: Governance and Risk management when using artificial intelligence
**Published:** 18 December 2024
**Issuing body:** Swiss Financial Market Supervisory Authority (FINMA)
**Legal status:** Supervisory guidance; non-binding but reflects FINMA's supervisory expectations; non-compliance may trigger supervisory action
**Length:** 7 pages
**Audience:** All FINMA-supervised institutions (banks, insurance companies, financial market infrastructures, collective investment schemes, securities dealers)

---

## Summary

This is the first dedicated AI governance document from a Swiss financial regulator. FINMA draws on findings from its ongoing supervisory activities — supervisory discussions and initial on-site reviews — to outline expectations for how supervised institutions should govern and manage risks from AI use. The guidance covers seven areas: governance, inventory and risk classification, data quality, tests and ongoing monitoring, documentation, explainability, and independent review. FINMA's approach is explicitly **technology-neutral, principle-based, and proportionate** — it does not create new AI-specific rules but clarifies how existing regulatory requirements (particularly operational risk management) apply to AI. The guidance is observational rather than prescriptive: it describes what FINMA has assessed and found, rather than mandating specific measures. The outlook section signals that FINMA will refine its expectations as understanding of AI risks develops.

---

## Key Points

### Regulatory Framework

FINMA notes that "there is no AI-specific legislation in Switzerland." It positions AI governance within existing technology-neutral, principle-based financial market regulation, particularly:

- **Operational risk management** — AI risks are classified primarily as operational risks (Art. 89 CAO), including model risks (robustness, correctness, bias, explainability) and IT/cyber risks
- **Third-party dependency risks** — growing concentration in hardware providers, model providers, and cloud services
- **Legal and reputational risks** — from autonomous and difficult-to-explain AI actions
- **Scattered responsibility risks** — from decentralised AI development within institutions

The guidance expects supervised institutions to align their AI governance, risk management, and control systems with their size, complexity, risk profile, **and** the materiality and risk probability of their specific AI applications.

### Materiality and Proportionality

FINMA applies a materiality test to determine what level of governance is appropriate. Factors influencing materiality include:

- Significance for compliance with supervisory law
- Financial impact on the institution
- Legal and reputational risks
- Relevance of the product to the institution
- Number and type of clients/investors affected (retail vs institutional)
- Importance of the product to clients/investors
- Consequences of errors or failure

Factors influencing probability of risk materialising:

- Complexity (explainability, predictability)
- Type and amount of data (unstructured, integrity, personal data)
- Development or monitoring process quality
- Degree of autonomy and process integration
- Dynamics (calibration frequency)
- Model linkage (multiple chained models)
- Attack surface (increased by outsourcing)

This is a proportionate framework: not all AI requires the same governance. A simple rule-based model with low materiality requires less oversight than a complex generative AI system making credit decisions.

### Seven Areas of Supervisory Assessment

#### 1. Governance

**FINMA found**: Institutions focus primarily on data protection risks but less on model risks (robustness, correctness, bias, stability, explainability). AI development is often decentralised, making it challenging to implement consistent standards, assign responsibilities clearly, and address all risks. For externally purchased applications, institutions had difficulty determining whether AI is included, what data and methods are used, and whether sufficient due diligence exists.

**FINMA assessed**: Whether institutions with many or significant AI applications have AI governance in place, including:
- Centrally managed inventory with risk classification
- Defined responsibilities and accountabilities for AI development, implementation, monitoring, and use
- Requirements for model testing and system controls
- Documentation standards
- Training measures
- For outsourced AI: additional tests, controls, contractual clauses, and verification of third-party skills/experience

#### 2. Inventory and Risk Classification

**FINMA found**: Some institutions defined AI narrowly to focus on "supposedly larger or new risks." Many found it challenging to ensure completeness of inventories, as AI development is widely spread and generative AI tools are accessible to everyone. Not all institutions had consistent criteria for identifying high-materiality applications.

**FINMA assessed**: Whether institutions had:
- Sufficiently broad AI definition (FINMA references the OECD definition approach)
- Complete AI inventories
- Risk classification of AI applications

**Key FINMA position**: "AI is not a high-risk application per se. The risk associated with it depends on the complexity, adaptivity and autonomy of the respective application, its area of application and its integration into processes." This is explicitly **not** the EU AI Act's approach (which pre-classifies by category in Annex III) — it is context-specific assessment analogous to the UK's sector-regulator approach.

#### 3. Data Quality

**FINMA found**: Some institutions had not defined requirements or controls for data quality in AI applications.

**FINMA assessed**: Whether institutions defined requirements for data completeness, correctness, integrity, availability, and access security. Specifically flagged: historical bias, environmental change invalidating training data, purchased solutions with unknown underlying data, and the increasing use of unstructured data (text, images).

#### 4. Tests and Ongoing Monitoring

**FINMA found**: Weaknesses in performance indicator selection, testing, and monitoring.

**FINMA assessed**: Whether institutions:
- Schedule pre-deployment tests including accuracy, robustness, stability, and bias checks
- Involve domain experts in defining test expectations
- Define performance indicators in advance
- Define thresholds or validation methods for ongoing output quality
- Monitor input data drift
- Analyse cases where users override AI outputs (manual corrections as signal of weakness)
- Consider exception handling in advance

Test types mentioned: backtesting, out-of-sample testing, sensitivity analysis, stress testing, adversarial testing, benchmark models, repeatability checks.

#### 5. Documentation

**FINMA found**: Some institutions lack centralised documentation requirements; existing documentation is insufficiently detailed and not audience-targeted.

**FINMA assessed**: For material applications, whether documentation covers:
- Purpose
- Data selection and preparation
- Model selection
- Performance measures
- Assumptions and limitations
- Testing and controls
- Fallback solutions
- Data sources and quality checks (integrity, correctness, appropriateness, relevance, bias, stability)
- Robustness, reliability, and traceability measures
- Risk categorisation with justification and review

#### 6. Explainability

**FINMA found**: Results often cannot be understood, explained, or reproduced and therefore cannot be critically assessed.

**FINMA assessed**: Where decisions must be justified to investors, clients, employees, the supervisory authority, or audit firms, whether institutions ensure explainability — including understanding drivers of the application and behaviour under different conditions. This is a proportionate requirement: explainability depth scales with the justification obligation.

#### 7. Independent Review

**FINMA found**: Not all institutions clearly separate AI development from independent review. Only a few carry out independent review of the entire model development process.

**FINMA assessed**: For material applications, whether independent review includes an objective, informed, and unbiased opinion on the appropriateness and reliability of the process for a particular application, and whether review results are incorporated into development.

### Outlook

FINMA signals continued evolution: "The understanding of risks associated with the use of AI by supervised institutions is still developing." It will "refine its expectations" and "make them transparent in the market" based on supervisory experience and international developments. The guidance strives for a "technology-neutral, proportional and standardised approach across all sectors."

This signals that the December 2024 guidance is a **floor, not a ceiling** — FINMA may tighten expectations as the market matures and as international standards (including EU AI Act enforcement precedent) develop.

---

## Observations

### Clarity

For a 7-page document, remarkably well-structured. Seven areas, each with a "FINMA observed" (finding) + "FINMA assessed" (expectation) structure. Practical and operationally useful.

Clarity strengths:
- Materiality factors are specific and non-exhaustive — institutions can apply them to their own context
- Test types are named concretely (backtesting, adversarial testing, sensitivity analysis, stress testing)
- Documentation requirements are specific enough to implement
- OECD AI definition referenced for institutional AI scope

Clarity weaknesses:
- No thresholds or pass/fail criteria. What constitutes "sufficient" governance, "adequate" documentation, or "enough" testing is left to institutional and supervisory judgment.
- No worked examples (in contrast to the EU Commission Guidelines, which provide extensive scenarios).

### Measurability

Very limited. No KPIs, no quantitative benchmarks, no minimum testing frequencies. This is consistent with FINMA's principle-based supervisory philosophy — but it means institutions must interpret the guidance in light of their own risk assessments. Two institutions with identical AI deployments could adopt very different governance levels and both claim compliance.

### Gaps

**No GPAI / foundation model provisions.** FINMA does not distinguish between traditional ML, deep learning, and generative AI in terms of governance requirements — though generative AI's accessibility to all employees is flagged as an inventory challenge.

**No specific AI use prohibitions.** FINMA does not prohibit any AI use in financial services. Contrast with the EU AI Act's Article 5 prohibitions (some of which apply regardless of sector) and with the UK FCA's existing restrictions on automated decision-making under Consumer Duty.

**No incident reporting requirements.** No AI-specific reporting timeline. Existing FINMA incident reporting channels apply, but without AI-specific thresholds or categorisation.

**No customer-facing transparency obligations.** FINMA assesses explainability for regulatory/audit/client justification purposes but does not require customer-facing disclosure that AI is being used (contrast: EU AI Act Article 52 chatbot disclosure requirement, now Article 50).

**No enforcement specifics.** The guidance is supervisory expectation, not rule. Non-compliance exposes institutions to supervisory risk (FINMA dialogue, remediation requirements, potentially enforcement proceedings) but no AI-specific penalties are defined.

### Feasibility

Highly feasible for large Swiss financial institutions (UBS, Credit Suisse/UBS successor, Zurich Insurance, Swiss Re) that already have model risk management frameworks. The guidance largely asks these institutions to extend existing model governance to AI applications.

More challenging for smaller institutions (cantonal banks, independent asset managers, smaller insurers) that may not have dedicated model risk functions. The proportionality principle helps but doesn't eliminate the governance burden.

### Internal Consistency

Internally consistent. The seven areas form a logical chain: governance → inventory → data → testing → documentation → explainability → independent review. Each area links to the others.

### Coverage

Covers financial-sector AI governance comprehensively within its 7-page scope. Does not cover:
- Non-financial-sector AI use
- Consumer-facing AI transparency
- AI in insurance underwriting (mentioned implicitly but not developed)
- Algorithmic trading (covered by existing FINMA regulations, not in this guidance)
- AI in compliance/RegTech (mentioned implicitly — "significance for compliance with supervisory law" as materiality factor)

### International Alignment

**Closely aligned with FSB recommendations.** The guidance explicitly references the FSB's "Financial Stability Implications of Artificial Intelligence" (14 November 2024). FINMA's seven areas mirror international supervisory consensus.

**Aligned with UK FCA approach.** Both FINMA and FCA apply AI governance through existing supervisory frameworks without AI-specific legislation. The FCA AI Update (April 2024) and this FINMA Guidance share philosophical DNA: principle-based, proportionate, technology-neutral, sector-specific.

**Contrasts with EU approach.** The EU AI Act imposes horizontal obligations that apply across sectors including financial services. EU financial institutions face both the AI Act's horizontal requirements and EBA/ESMA sector-specific AI guidance. Swiss financial institutions face only FINMA guidance (plus EU AI Act if they serve EU markets).

---

## Overall Assessment

FINMA Guidance 08/2024 is a **concise, practical, and internationally aligned** document that represents the most operationally relevant Swiss AI governance instrument today. It demonstrates the sector-specific approach that the Federal Council endorsed in February 2025.

Its greatest strength is **proportionality**: the materiality framework allows institutions to calibrate governance to actual risk rather than categorical classification. A simple internal chatbot does not require the same governance as a credit-scoring model.

Its greatest weakness is **non-specificity**: no thresholds, no quantitative benchmarks, no pass/fail criteria. Institutions must interpret the guidance in the context of their own operations and supervisory relationship with FINMA.

For UK-based firms with Swiss financial-sector operations:

1. **Treat this as the primary Swiss AI compliance reference for financial services.** It is more operationally useful than the Federal Council's announcement.

2. **Map FINMA's seven areas to your existing model risk management framework.** If you have MRM, extending it to cover AI is the natural compliance pathway.

3. **Build an AI inventory.** FINMA's emphasis on complete inventories with broad AI definition is the highest-priority operational step.

4. **Document materiality assessments.** FINMA's proportionality framework requires documented risk classification — this is the institutional evidence that your governance level is appropriate.

5. **Expect FINMA to tighten.** The outlook section signals continued evolution. As EU AI Act enforcement generates precedent, FINMA will likely align its expectations toward international standards.

6. **If you also serve EU markets, FINMA compliance is necessary but not sufficient.** EU AI Act obligations apply independently. Build a single governance framework that satisfies both.

---

## Sources

- [FINMA Guidance 08/2024 (PDF)](../../source/FINMA-Guidance-08-2024-AI-Governance.pdf)
- [FINMA website](https://www.finma.ch)
- FSB, "The Financial Stability Implications of Artificial Intelligence" (14 November 2024)
- OECD, "Explanatory Memorandum on the Updated OECD Definition of an AI System" (March 2024, No. 8)
- Related reviews:
  - [Federal Council AI Regulation Approach (review 01)](01-federal-council-ai-regulation-approach.md) — the policy framework FINMA operates within
  - [UK FCA AI Update (review 12)](../../UK/analysis/review-claude/12-fca-ai-update.md) — closest international comparator
  - [EU AI Act (review 01)](../../EU/analysis/review-claude/01-eu-ai-act.md) — the binding framework Swiss firms serving EU must also comply with
