# AI Governance in Financial Services: A Cross-Jurisdictional Overview

Financial services is the sector with the most developed AI governance across jurisdictions. Every major financial regulator has addressed AI — through principles, supervisory guidance, or binding regulation. For firms operating across borders, this creates a layered compliance environment where domestic financial regulation sits alongside horizontal AI regulation.

This overview covers five jurisdictions: the EU, UK, Singapore, Switzerland, and USA.

---

## The landscape at a glance

| Jurisdiction | Financial AI governance instrument | Binding? | Approach |
|-------------|-----------------------------------|----------|----------|
| **EU** | AI Act (horizontal) + EBA/ESMA/EIOPA sectoral guidance | Yes (AI Act); sectoral guidance varies | Risk-classification: high-risk AI in creditworthiness, insurance pricing, and fraud detection falls under Annex III. Horizontal AI Act obligations apply on top of existing prudential regulation |
| **UK** | FCA AI Update (Apr 2024) | Non-binding guidance | Maps government's 5 cross-sectoral principles onto existing FCA frameworks (Principles for Business, SYSC, SM&CR, Consumer Duty). No AI-specific rules added |
| **Singapore** | MAS FEAT Principles (Nov 2018) + Veritas Toolkit | Non-binding principles | 14 principles across Fairness, Ethics, Accountability, Transparency. Supported by the Veritas validation toolkit. MAS supervisory expectations |
| **Switzerland** | FINMA Guidance 08/2024 | Supervisory guidance (non-binding but carries supervisory weight) | 7 areas of supervisory assessment based on on-site findings. Proportionate, materiality-based. Technology-neutral |
| **USA** | No AI-specific financial regulation. Existing agency authority (OCC, Fed, FDIC, SEC, CFPB) | Existing law applies | Agencies enforce under existing authority (fair lending, consumer protection, prudential). No dedicated AI guidance from primary banking regulators. FTC enforcement under Section 5 |

---

## What they share

All five jurisdictions' financial-sector AI approaches share common DNA:

1. **Principle-based, not rule-based.** None prescribes specific technical requirements for financial AI. All rely on principles (fairness, transparency, accountability) operationalised through existing supervisory relationships.

2. **Proportionality.** All scale governance expectations to the materiality and risk of the AI application. A simple rule-based fraud filter requires less oversight than an AI credit-scoring model.

3. **Existing frameworks as foundation.** All position AI governance within existing prudential and conduct regulation rather than creating standalone AI regimes for financial services. The logic: financial regulation already addresses most relevant risks (consumer protection, fair lending, operational resilience, model risk management); AI governance extends rather than replaces these frameworks.

4. **Model risk management as entry point.** For firms with existing model risk management (MRM) frameworks, AI governance is an extension of MRM. All five jurisdictions effectively ask: does your model governance cover AI models? If not, extend it.

5. **Third-party / outsourcing risk.** All recognise that financial firms increasingly use AI from external providers (cloud-hosted models, vendor AI tools) and expect firms to manage these dependencies — whether through outsourcing risk frameworks (MAS, FINMA, FCA) or supply-chain governance (EU AI Act Article 17).

---

## Where they differ

### Binding vs voluntary

The EU is the outlier: the AI Act creates **binding horizontal obligations** that apply to financial services AI on top of existing prudential regulation. If a bank's credit-scoring system uses AI, it is potentially high-risk under Annex III point 5(b) (creditworthiness assessment) — triggering the full suite of high-risk obligations (conformity assessment, QMS, human oversight, incident reporting, etc.).

All other jurisdictions rely on **supervisory expectations** within existing frameworks. The FCA, MAS, and FINMA can challenge a firm's AI governance through the supervisory process, but they don't have AI-specific binding rules.

**Practical consequence:** A bank operating in the EU and UK uses the same AI credit model in both jurisdictions. In the EU, it faces AI Act high-risk obligations (conformity assessment, Article 14 human oversight, Article 73 incident reporting). In the UK, it faces FCA supervisory expectations under Consumer Duty and existing model governance — but no AI-specific conformity assessment.

### Specificity of guidance

**FINMA** (Switzerland) is the most specific: it describes what it actually found during supervisory reviews (governance gaps, narrow AI definitions, weak data quality controls, insufficient testing) and what it assessed. This "findings from supervision" format gives firms concrete signals about regulatory expectations.

**MAS** (Singapore) is the most structured: 14 named principles across four pillars, supported by a dedicated validation toolkit (Veritas). The structure makes self-assessment straightforward.

**FCA** (UK) is the most deferential: it maps government principles onto existing frameworks without adding AI-specific requirements. Firms must interpret what existing rules mean for AI.

**EU** is the most prescriptive: binding obligations with specified timelines, documentation requirements, and penalty structures.

**USA** is the most fragmented: no single AI governance reference for financial services. Multiple agencies (OCC, Fed, FDIC, SEC, CFPB, FTC) apply existing authority case-by-case.

### Credit scoring and lending

This is the use case with the most direct cross-jurisdictional comparison:

- **EU**: AI-based credit scoring is high-risk under Annex III point 5(b). Full high-risk obligations apply. Additionally, GDPR Article 22 provides individuals a right not to be subject to solely automated decisions with legal or significant effects.
- **UK**: FCA Consumer Duty requires fair treatment. DUAA 2025 relaxed Article 22 UK GDPR — broader automated decision-making now permitted with safeguards. No AI-specific classification.
- **Singapore**: FEAT Principles 1-4 (fairness) require that individuals are not systematically disadvantaged. Model accuracy and bias reviewed regularly. No binding classification.
- **Switzerland**: FINMA expects risk classification, testing, documentation, and explainability for material AI applications including credit models. No binding AI classification.
- **USA**: Fair lending laws (ECOA, FHA) prohibit discrimination. OCC/Fed model risk management guidance (SR 11-7) applies to AI models. CFPB has signalled enforcement interest in AI lending. No AI-specific classification.

### Insurance underwriting

- **EU**: AI-based risk assessment and pricing for life and health insurance is high-risk under Annex III point 5(c). Less clear for property/casualty.
- **UK**: FCA principles apply; no AI-specific classification for insurance AI.
- **Singapore**: FEAT Principles apply through MAS supervisory expectations.
- **Switzerland**: FINMA Guidance covers insurance AI through the same materiality framework.
- **USA**: State insurance regulators are primary; NAIC has issued AI guidance; no federal AI classification.

### Algorithmic trading

- **EU**: MiFID II already covers algorithmic trading extensively. AI Act adds limited additional obligations for trading AI (likely minimal risk unless safety-critical).
- **UK**: FCA rules on algorithmic trading under UK MiFID.
- **Singapore**: MAS existing framework covers algorithmic trading.
- **Switzerland**: FINMA existing framework applies.
- **USA**: SEC and CFTC regulate algorithmic trading under existing authority. No AI-specific overlay.

---

## For firms operating across jurisdictions

### The compliance architecture

For a financial services firm operating across multiple jurisdictions, the practical compliance architecture has three layers:

1. **Domestic financial regulation** — the existing prudential and conduct framework in each jurisdiction where you operate. This is your baseline regardless of AI.

2. **AI-specific obligations** — in the EU, the AI Act adds binding requirements on top. In other jurisdictions, AI governance expectations layer onto existing supervisory relationships.

3. **Group-level AI governance** — an internal framework covering all jurisdictions. Most firms build this on the NIST AI RMF structure (Govern, Map, Measure, Manage) or the Singapore Model Framework structure (governance, human oversight, operations, stakeholders), because these are the most internationally referenced voluntary frameworks.

### The key question for each AI application

For each AI application in financial services, the cross-jurisdictional compliance question is:

- **Is this a high-risk AI system under the EU AI Act?** If yes: full high-risk obligations in EU operations, regardless of what other jurisdictions require.
- **Does this touch consumer decisions?** If yes: consumer protection obligations in all jurisdictions (Consumer Duty in UK, FEAT fairness in Singapore, fair lending in USA).
- **Is this a material application under internal risk classification?** If yes: MRM-level governance in all jurisdictions where you operate.
- **Does this involve personal data?** If yes: GDPR/UK GDPR/PDPA/revFADP data protection obligations apply alongside AI governance.

### Where deeper analysis adds value

This overview maps the landscape. For individual firms, the deeper work includes:

- **Mapping specific AI applications** to obligation matrices across jurisdictions
- **Gap analysis** between existing MRM frameworks and AI Act high-risk requirements
- **Conformity assessment preparation** for EU high-risk financial AI systems
- **Cross-jurisdictional incident-reporting protocols** — EU Article 73 timelines interact with existing prudential incident reporting
- **Human oversight architecture** — Article 14 EU requirements vs sector-regulator expectations elsewhere
- **Third-party AI governance** — managing vendor AI through outsourcing and supply-chain frameworks across jurisdictions

---

## Sources

This overview draws on the following reviews from the [AI Regulations repository](https://github.com/EdwardAThomson/AI-regulations):

- [UK FCA AI Update](https://github.com/EdwardAThomson/AI-regulations/blob/main/UK/analysis/review-claude/12-fca-ai-update.md)
- [Singapore MAS FEAT Principles](https://github.com/EdwardAThomson/AI-regulations/blob/main/Singapore/analysis/review-claude/04-mas-feat-principles.md)
- [Switzerland FINMA Guidance 08/2024](https://github.com/EdwardAThomson/AI-regulations/blob/main/Switzerland/analysis/review-claude/02-finma-guidance-ai-governance.md)
- [EU AI Act](https://github.com/EdwardAThomson/AI-regulations/blob/main/EU/analysis/review-claude/01-eu-ai-act.md)
- [USA NIST AI RMF](https://github.com/EdwardAThomson/AI-regulations/blob/main/USA/analysis/review-claude/01-nist-ai-rmf.md)
