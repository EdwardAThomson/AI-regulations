# Data (Use and Access) Act 2025 — Review

**Document:** Data (Use and Access) Act 2025 (DUAA) — enacted UK legislation
**Royal Assent:** 19 June 2025
**Reference:** 2025 c. 18
**Issuing body:** UK Parliament
**Source form:** Government guidance summary (detailed analysis below); full Act text at https://www.legislation.gov.uk/ukpga/2025/18

**Note:** This is the only piece of primary legislation reviewed in this series. The DUAA is not AI-specific but contains provisions — particularly on automated decision-making, recognised legitimate interests, and scientific research — that are materially relevant to AI use in the UK. This review focuses on those AI-relevant provisions rather than the Act as a whole.

---

## Summary

The Data (Use and Access) Act 2025 is the UK's first substantive post-Brexit data protection reform. It amends rather than replaces UK GDPR, the Data Protection Act 2018, and the Privacy and Electronic Communications Regulations. The Act's breadth is substantial — it covers Smart Data schemes (including Open Banking extensions), digital verification services, the National Underground Asset Register, plus data protection reforms. From an AI governance perspective, the most consequential provisions are the relaxation of solely automated decision-making restrictions (previously under Article 22 UK GDPR), the introduction of Recognised Legitimate Interests as a new lawful ground, the clarification that scientific research includes commercial research, the new requirement for services likely accessed by children to consider child protection, and the simplification of international data transfer rules. The Act received Royal Assent in June 2025 and commences in stages between August 2025 and June 2026.

---

## Key Points

### Legislative Architecture

- **Royal Assent: 19 June 2025** (c. 18)
- **Amends** UK GDPR, Data Protection Act 2018, Privacy and Electronic Communications Regulations — does not replace them
- **Phased commencement** 2-12 months post-Royal Assent (August 2025 to June 2026)
- Parliamentary passage: https://bills.parliament.uk/bills/3825

### Automated Decision-Making (the most AI-relevant provision)

Previously, Article 22 UK GDPR prohibited "decisions based solely on automated processing that have legal or similarly significant consequences" (phrase cited repeatedly in the AI Playbook and FCA AI Update). The DUAA establishes a **more permissive framework**:

- Organisations may make decisions based solely on automated processing with legal or similarly significant effects — provided safeguards are in place
- **Safeguards include:**
  - Providing people with information about significant decisions made about them
  - Enabling them to make representations about and challenge such decisions
  - Enabling them to obtain human intervention
- **Law enforcement processing exemptions** — for limited reasons (safeguarding national security, avoiding inquiry obstruction). Exemptions require reconsideration "as soon as reasonably practicable" with meaningful human involvement

**Implication:** This is the single most significant AI-relevant change in recent UK data protection law. Many AI deployments were constrained by the Article 22 prohibition; the DUAA moves the UK toward a broader use-with-safeguards model.

### Recognised Legitimate Interests

A **new lawful ground for processing** — giving organisations greater confidence to use personal data for:
- Crime prevention
- Safeguarding
- Emergency response
- Other specified legitimate interests

This sits alongside the existing "legitimate interests" ground but does not require the organisation to conduct a legitimate interest assessment balancing the controller's interests against the data subject's — making compliance simpler for the specified categories.

### Scientific Research Clarifications

- Scientific research **encompasses commercial research** (clarified, not expanded in scope)
- Researchers permitted to seek consent for **broad related research areas** rather than specific projects
- Clear safeguards for personal data use in research activities

**Implication:** This is directly relevant to AI R&D where data reuse across projects is common. It provides legal clarity for industry-academia collaborations and commercial AI research use of personal data.

### Children's Data Protection

- New rules require certain online services "likely accessed by children" to consider child protection and support measures when designing services
- Builds on existing ICO Age Appropriate Design Code

### Subject Access

- Clarifies response time limits for subject access requests
- **"Stop the clock" rule** — organisations may pause response time when needing additional requester information
- Reasonable and proportionate searches required

### International Data Transfers

- Simplifies and clarifies rules for transferring personal data internationally
- Relevant to AI supply chains that span jurisdictions (e.g., UK user data processed by US-hosted AI)

### Smart Data Schemes

- New powers to establish Smart Data schemes — consumers and businesses share data securely
- Open Banking referenced as the precedent
- Applications: household financial management, SME finance access, transaction speed
- Per AI Opportunities Action Plan One Year On: 36 million GBP investment in new Smart Data schemes

### Digital Verification Services

- Framework for trusted digital verification services
- Relevant to AI-enabled identity systems

### Law Enforcement and Intelligence Services

- Amends Parts 3 and 4 of DPA 2018 (law enforcement / intelligence processing)
- Some amendments mirror UK GDPR changes for consistency
- Others simplify legislation for law enforcement efficiency and UK intelligence agency collaboration

### Complaint Handling

- Requires organisations to handle complaints from individuals about data protection breaches
- Must provide electronic complaint forms
- Must inform individuals about complaint outcomes

### Storage and Access Technologies (Cookies)

- Permits cookie-style technology use without explicit consent in certain "low-risk" situations

---

## Observations

### Clarity

As primary legislation, the DUAA is necessarily technical. The government guidance summary provides a clear map but cannot substitute for the Act text when legal compliance is at stake.

The guidance's clarity virtue is that it identifies which provisions amend which existing instruments. This is important because many organisations' compliance infrastructure is built around UK GDPR and DPA 2018 — the guidance tells practitioners where to look for the changes.

The clarity weakness is that a short guidance cannot adequately address the interpretive complexity of "significant decisions," "appropriate safeguards," "recognised legitimate interests," and the other critical terms that will shape how the Act operates in practice. The ICO's forthcoming regulatory guidance (referenced in the government document) will be where practitioners actually find operational clarity.

### Measurability

Legislation does not typically include success metrics, and this Act is no exception. The measurable elements come from implementation:

- 2-12 month commencement window (i.e., complete implementation by June 2026)
- 36 million GBP investment in Smart Data schemes (per One Year On report)
- ICO guidance to be published

What is not measurable without additional policy infrastructure: whether the relaxation of automated decision-making constraints produces the intended innovation benefits, whether safeguards protect individuals effectively, whether Recognised Legitimate Interests are used appropriately, whether the scientific research clarifications enable beneficial R&D or inappropriate data reuse. The Act does not propose outcome monitoring.

### Gaps

**The relationship to AI regulation is not articulated.** The DUAA is a data protection reform; it does not reference the UK's pro-innovation AI regulatory framework, AISI, or any AI-specific governance structure. Yet the automated decision-making provisions are the most AI-relevant change in UK law for years. The lack of explicit cross-reference means that practitioners must connect the dots themselves.

**Human-in-the-loop requirements underspecified.** The DUAA allows solely automated decisions with safeguards including "human intervention." The AI Playbook (February 2025) still references "meaningful human intervention" requirements. What constitutes "meaningful" is not defined in either document. For AI deployments at scale (e.g., millions of credit decisions, content moderation, benefit eligibility), whether humans can meaningfully intervene in any reasonable timeframe is an open question. The Act relaxes the prohibition without specifying the replacement standard.

**Recognised Legitimate Interests scope.** The new lawful ground is "specified" — but the specification is delegated to regulations (the Act grants powers for Secretary of State to add categories). This is a rational legislative design but means that the practical scope depends on subsequent regulations. AI applications that might benefit (fraud detection, cybersecurity, content moderation) are not guaranteed to be included.

**Scientific research commercial clarification.** The clarification that scientific research "encompasses commercial research" is welcomed by industry but creates interpretive risk. Commercial research has wider scope than academic research; the extent to which commercial AI training can claim scientific research exemptions — and evade UK GDPR restrictions on personal data use — is not addressed in the Act. The Google v. CNIL (France) precedent on Google's commercial research claims suggests this is contested territory.

**Children's protections scope.** "Services likely accessed by children" is an Age Appropriate Design Code-style standard. AI services and chatbots — many of which are likely accessed by children — would fall in scope. But the Act does not specifically address AI. Whether the duty applies to, e.g., a general-purpose AI assistant that might be used by children is left to interpretation.

**International transfer simplification.** UK transfers to third countries (including to US AI companies) are a recurring compliance issue. The Act simplifies but the EU adequacy decision for the UK remains conditional on UK data protection standards. UK relaxation of protections could threaten adequacy — which would be commercially consequential for UK businesses exporting data to the EU. The Act does not address this risk explicitly.

**Enforcement mechanism unchanged.** The ICO remains the enforcement body. No additional resources or powers for AI-specific enforcement are created by the Act. Given the AI Playbook's extensive reliance on ICO guidance and the practical shift that automated decision-making relaxation will require, ICO capability to supervise this expanded scope is a constraint not addressed.

**No provision for AI developer obligations.** The DUAA is a data protection Act; it addresses data controllers and processors. AI model developers (upstream of deployers who use the models) face no new obligations under this Act. The EU AI Act by contrast creates obligations for general-purpose AI providers regardless of their role as data controllers. The UK's continued reliance on data protection law to regulate AI — rather than AI-specific legislation — means AI developer obligations remain voluntary.

**Workers' rights in AI-driven decisions absent.** The Act addresses "data subjects" making representations about solely automated decisions. Workers subject to algorithmic management at work (shift scheduling, performance monitoring, promotion decisions) are also data subjects, but the employer-employee context raises specific issues the Act does not address. TUC and other labour organisations have called for AI-specific workers' rights legislation; the DUAA does not provide it.

### Feasibility

The Act is law — feasibility is no longer a forward-looking question. Phased commencement (2-12 months) is a standard approach that gives organisations time to adjust. ICO guidance is the commitment that determines practical feasibility.

The aspects requiring ongoing feasibility assessment:
- **Automated decision-making safeguards at scale** — whether organisations can implement meaningful human intervention for high-volume AI use
- **Smart Data schemes implementation** — technical and commercial feasibility of each specific scheme
- **Digital verification services** — whether the framework produces a functioning market

### Internal Consistency

The Act is internally consistent as legislation. The broader consistency question is with other UK AI governance documents:

- **Consistent with** the pro-innovation framework — the Act relaxes restrictions, consistent with pro-innovation framing
- **Consistent with** the AI Playbook's concerns about human oversight — the Act creates safeguards rather than eliminating human involvement requirements
- **In tension with** the Pro-Innovation Consultation Response's "more permissive automated decision-making regime" framing — the Consultation Response anticipated exactly this legislative change, so the inconsistency is minor
- **In tension with** EU AI Act alignment — the UK's relaxation of automated decision-making constraints diverges from the EU's direction of travel, creating cross-border compliance complexity

### Coverage

The Act's scope is broader than AI (Smart Data, digital verification, underground assets). Within AI-relevant scope, it covers:
- Automated decision-making (relaxation + safeguards)
- Lawful grounds for processing (Recognised Legitimate Interests)
- Scientific research for data use
- Children's protections
- International transfers
- Complaints handling
- Cookies

What it does not cover (AI-relevantly): AI developer obligations, AI safety requirements, AI-specific fairness requirements beyond existing Equality Act, AI-specific transparency beyond existing UK GDPR, AI-specific liability, AI-specific enforcement.

### International Alignment

The Act is the clearest post-Brexit expression of the UK's intention to diverge from EU data protection orthodoxy where the UK judges it beneficial for innovation. The relaxation of automated decision-making restrictions is particularly notable — it contrasts with the EU AI Act's strengthening of oversight for high-risk AI systems.

The EU-UK adequacy decision (permitting EU-to-UK data transfers without additional safeguards) was re-affirmed in December 2024 but depends on UK maintaining "essentially equivalent" protections. Whether the DUAA's relaxations put this at risk is contested. The ICO and government have argued not; consumer and civil society groups in the UK and EU have argued yes. The outcome matters substantially for UK businesses relying on EU data flows.

The Council of Europe AI Convention (Vilnius 2024) and UK commitments to international AI governance frameworks are not referenced in the Act or guidance.

---

## Overall Assessment

The Data (Use and Access) Act 2025 is the most legally consequential UK AI-relevant development in recent years. While it is not AI-specific legislation, it substantially changes the legal landscape in which AI is deployed in the UK — particularly through the automated decision-making relaxation, the new lawful grounds, and the scientific research clarifications.

Its greatest strength, from a pro-innovation perspective, is that it addresses a real constraint. The Article 22 UK GDPR prohibition on solely automated decisions with legal or significant effects was a genuine impediment to AI deployment in credit scoring, insurance, recruitment, content moderation, and related use cases. The DUAA's framework — permit with safeguards — is more workable than the previous default prohibition.

Its greatest weakness, from an AI governance perspective, is that it ducks the hard questions. The safeguards it requires (information provision, representation, human intervention) are vague. The definition of "meaningful human intervention" is absent. The interaction with the pro-innovation AI framework is not articulated. The relationship to Equality Act fairness requirements is not specified. The ICO is left to provide operational guidance, and ICO's capacity to do so for rapidly evolving AI systems is constrained.

For UK AI governance specifically, the DUAA represents the maturation of the UK's approach: rely on general frameworks (data protection, competition, consumer protection, Equality Act, Human Rights Act) rather than AI-specific rules, and reform those general frameworks to be more permissive of AI innovation where the government judges it beneficial. This is a coherent strategy. Whether it proves sufficient is a question that will be answered over the commencement period (August 2025 - June 2026) and beyond.

The Act's consequential tension is with the EU. The EU AI Act is moving in the opposite direction on automated decision-making (strengthening, classifying as high-risk). The UK's DUAA is moving toward permission with safeguards. Organisations operating in both jurisdictions face divergent compliance requirements. Whether UK divergence proves to be a competitive advantage (attracting AI investment) or a regulatory burden (requiring dual compliance) will shape the UK AI governance position over the next decade.

One notable omission from the DUAA: no provisions specifically for frontier AI development. The UK's Pro-Innovation Consultation Response (February 2024) set out the case for binding measures on frontier AI developers. The AI Opportunities Action Plan: Government Response (January 2025) committed to establishing AISI as a statutory body. Neither is in the DUAA. The DUAA is a data protection reform; frontier AI regulation remains on the UK's to-do list, not the statute book.

For the UK analysis in this repository, the DUAA is the piece of legislation that the other documents presuppose without (before its enactment) having. The AI Playbook's references to Article 22 UK GDPR prohibitions are effectively superseded by the DUAA's more permissive framework. The Pro-Innovation Consultation Response's argument for updated automated decision-making rules has been delivered. The question of what comes next — binding rules for frontier AI developers — remains open.

---

## Sources

- [Data (Use and Access) Act 2025 (legislation.gov.uk)](https://www.legislation.gov.uk/ukpga/2025/18)
- [Data (Use and Access) Act 2025 guidance (GOV.UK)](https://www.gov.uk/guidance/data-use-and-access-act-2025-data-protection-and-privacy-changes)
- [ICO — Data (Use and Access) Act 2025](https://ico.org.uk/about-the-ico/what-we-do/legislation-we-cover/data-use-and-access-act-2025/)
- [Parliamentary record](https://bills.parliament.uk/bills/3825)
