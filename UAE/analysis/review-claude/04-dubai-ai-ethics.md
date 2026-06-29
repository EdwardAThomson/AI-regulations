# Dubai AI Ethics Principles & Guidelines

*Research and comparison only, not legal advice. AI-assisted analysis; may contain errors, so verify all claims against the primary source document.*

**Document:** Smart Dubai AI Ethics Principles & Guidelines (part of Dubai's Ethical AI Toolkit, which also includes an AI Ethics Self-Assessment Tool)
**Published:** January 2019 (document changelog runs through 30/12/2018; produced with Falcon and Associates)
**Issuing body:** Smart Dubai Office (now Digital Dubai), Government of Dubai
**Legal status:** Voluntary, non-binding guidance; published under a Creative Commons Attribution 4.0 licence; not legally enforceable and not audited
**Length:** ~33 pages

---

## Summary

The Dubai AI Ethics Principles & Guidelines is a voluntary, emirate-level soft-law document issued by Smart Dubai (now Digital Dubai) in January 2019. It sets out four high-level AI Principles (Ethics, Security, Humanity, Inclusiveness) and then elaborates only the Ethics principle into detailed, operational Guidelines built on four sub-principles: fair, accountable, transparent, and explainable. It forms the principles-and-guidelines half of a broader "Ethical AI Toolkit," whose third component is a separate AI Ethics Self-Assessment Tool that lets a developer or operator classify and score an AI system.

## Key points

- **Four AI Principles.** The document opens with four headline principles, each given a one-line definition:
  - **Ethics:** "AI systems should be fair, transparent, accountable and understandable."
  - **Security:** "AI systems should be safe and secure, and should serve and protect humanity."
  - **Humanity:** "AI should be beneficial to humans and aligned with human values, in both the long and short term."
  - **Inclusiveness:** "AI should benefit all people in society, be governed globally, and respect dignity and people rights."
  Each principle carries a short page of supporting bullets (for example the Security principle's call that systems "should be able to be overridden or their decisions reversed by designated people," and the Humanity principle's forward-looking bullets on AGI and superintelligence).

- **Principles vs Guidelines split.** The Principles are aspirational and cover the whole of AI. The Guidelines are deliberately narrower: they elaborate only the Ethics principle, and explicitly state that they "do not cover issues relating to employment, security or any other aspects of the governance of artificial intelligence besides those mentioned above." So three of the four principles (Security, Humanity, Inclusiveness) receive no detailed guidance in this document.

- **The Ethics principle and its four sub-principles.** The Guidelines map the Ethics principle onto the global FATE canon: fairness, accountability, transparency, explainability. The Definitions section makes this explicit, defining "Ethics (as applied to AI)" as "the concepts of fairness, accountability, transparency and explainability," and noting it deliberately excludes privacy, model accuracy, and employment. The four guideline clusters are:
  - **1.1 We will make AI systems fair** (representative data, avoiding non-operational bias, provably fair significant decisions, accessibility across user groups, effect of diversity).
  - **1.2 We will make AI systems accountable** (accountability lies with people not the system, risk mitigation, appeals/challenge procedures, opt-outs, quality checks at least as stringent as for a human decision-maker).
  - **1.3 We will make AI systems transparent** (traceability of significant decisions, informing people when a significant decision is made by AI, and that an AI impersonating a human must disclose it).
  - **1.4 We will make AI systems as explainable as technically possible** (high-level and decision-specific explanations, free of charge and user-friendly, with counterfactual or weighted-factor compromises where full explanation is not technically feasible).

- **Scope and definitions.** The Guidelines apply to both public and private sectors, but only to AI systems that make or inform "significant decisions" (individually significant, or part of a set of "significant-at-scale" decisions); a narrower "critical decision" category covers especially high-stakes cases. The document defines AI developer organisation, AI operator organisation, AI and AI system (consistent with ISO/IEC 2382:2015), bias, AI subject, and related terms, giving it more rigour than a pure principles statement.

- **Maturity / suspension framing.** The Guidelines use graduated language throughout ("should," "could," "should consider"), signalling intended maturity rather than fixed requirement. Notably, guideline 1.2.3 (external audit of AI systems informing critical decisions) is marked **SUSPENDED** with the stated reason that "no external auditing mechanism has yet been established."

- **AI Ethics Self-Assessment Tool.** The introduction frames this document as part of Dubai's "Ethical AI Toolkit," which "consists of principles and guidelines, and a self-assessment tool for developers to assess their platforms." The Self-Assessment Tool is a companion instrument (not reproduced inside this PDF): it lets a developer or operator classify an AI system against the guidelines and generate an ethics score, turning the four sub-principles into a self-administered checklist with an output rating.

## Observations

### Legal status

This is the central interpretive point. The document is voluntary and explicitly non-binding: the introduction states plainly that "the guidelines are non-binding," and the document is released under a Creative Commons Attribution 4.0 licence to encourage reuse by other governments and the private sector. A "Responsibility" notice disclaims that the Smart Dubai Office bears no responsibility for any misuse and that "the user bears all the consequences of their use." There is no statutory basis, no penalty, no licensing or registration requirement, and no compliance mechanism. Dubai government entities were directed to adopt the toolkit, but it imposes no obligation on private actors. The suspension of guideline 1.2.3 confirms the absence of any audit function: even the document's own strongest accountability clause is switched off because no auditing mechanism exists. Readers should not mistake adherence to this toolkit for compliance with any binding rule.

### Measurability

The Self-Assessment Tool is the document's genuine differentiator on measurability. Most ethics statements stop at values; here the toolkit produces a score, which is materially more measurable than a bare declaration of principles, and the guideline-level clauses are concrete enough to be checked against a system (representative data, appeals procedures, disclosure of AI involvement, traceability documentation). The hard limitation is that the score is self-declared and self-administered: there is no external verification, no audit (1.2.3 suspended), no regulator reviewing results, and no obligation to run the tool at all or to publish the outcome. The measurability is real at the level of self-reflection but unverified at the level of assurance.

### Clarity

The Guidelines are clearer and more operational than most national ethics texts. They are layered (principle, sub-principle, numbered clause), defined in a dedicated Definitions section, and illustrated with worked examples (job-screening bias, loan-decision challenge rights, credit-card explanations, a conversational agent disclosing it is not human). The graduated "should / could / should consider" verbs are honest about intent but blur where a practice is expected versus merely encouraged, so the operative strength of any given clause is often left to the reader.

### Gaps

- **Three principles left unelaborated.** Security, Humanity, and Inclusiveness get headline definitions but no guidelines; the detailed work covers only Ethics/FATE.
- **No enforcement or audit.** The one external-audit clause is suspended for want of a mechanism; nothing replaces it.
- **Self-declared only.** No independent assessment, certification, or registry sits behind the Self-Assessment Tool.
- **Privacy and employment deliberately excluded** from the Ethics scope, so two of the most contested AI harms are out of frame here (privacy is touched only at principle level under Inclusiveness).
- **Pre-generative.** As a 2018/2019 document it predates large generative models and agentic AI; its "significant decision" framing assumes discrete decision-support systems rather than general-purpose models, autonomous agents, or content generation at scale.

### Feasibility

Because the toolkit is voluntary and self-administered, it is trivially feasible to publish and to adopt, and the self-assessment workflow is a realistic, low-friction artefact that an organisation can actually run. The limiting factor is the same as for any soft-law instrument: without audit, certification, or legal backing, uptake and rigour depend entirely on goodwill, and the suspended audit clause shows the authors hit the practical ceiling of what they could operationalise in 2019.

### Coverage

Within the Ethics/FATE frame the coverage is strong and unusually concrete for its date: fairness and bias, accountability and redress, transparency and disclosure, and explainability are each broken into multiple testable clauses with examples. Across the wider AI-governance landscape the coverage is partial by design: it does not operationalise safety, societal/economic impact, or inclusiveness, and it does not address foundation models, agentic systems, or generative content. The definitional rigour (developer vs operator, significant vs critical decision, AI subject) is a strength other ethics statements lack.

### International alignment

The four sub-principles map directly onto the global FATE canon (fairness, accountability, transparency, explainability) and onto the OECD AI Principles (2019), with which they are broadly contemporaneous. The bibliography signals deliberate international borrowing: the UK Data Science Ethical Framework, Canada's Responsible AI work, the EU Commission's guidance on automated individual decision-making, the Toronto Declaration, Singapore's PDPC discussion paper, and others. The practical tooling angle puts Dubai in similar spirit to Singapore's later AI Verify: both pair principles with a usable self-assessment instrument rather than leaving values abstract, though Dubai's tool relies on self-declaration without the testing harness AI Verify later added.

### Internal consistency

The document is internally coherent: the Guidelines correctly trace back to the Ethics principle, the Definitions support the clauses, and the examples illustrate them. The visible tension is the suspended audit clause (1.2.3), which leaves the accountability section asserting that critical-decision systems "should be subject to appropriate external audit" while simultaneously disabling that requirement, a candid but unresolved gap between stated intent and available mechanism.

## Overall assessment

The Dubai AI Ethics Principles & Guidelines is one of the more substantive emirate-level soft-law artefacts of its era: four headline principles, a rigorously defined and example-rich set of guidelines built on the FATE canon, and a companion Self-Assessment Tool that produces an actual ethics score. That tooling is its real differentiator, putting it closer in spirit to Singapore's AI Verify than to a pure principles declaration, and giving it more measurability than most ethics statements achieve. The limits are equally clear and largely deliberate: it is voluntary, non-binding, and self-declared, with no audit (its one audit clause is suspended), no enforcement, and no obligation on private actors; it elaborates only the Ethics principle and leaves Security, Humanity, and Inclusiveness as headlines; and as a 2019 instrument it predates generative and agentic AI. It should be read as Dubai-emirate soft law within a wider UAE landscape (the federal UAE Charter of 2024, plus the separate DIFC, ADGM, and CBUAE regimes), valuable as practical, reusable guidance and self-reflection rather than as a source of enforceable obligation.
