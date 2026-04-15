# EU GPAI Code of Practice (All Three Chapters) — Review

**Documents:**
- Code of Practice for General-Purpose AI Models — Transparency Chapter (6 pages)
- Code of Practice for General-Purpose AI Models — Copyright Chapter (6 pages)
- Code of Practice for General-Purpose AI Models — Safety and Security Chapter (43 pages)

**Published:** 10 July 2025
**Formally approved:** 1 August 2025 (by EU AI Office)
**Status:** Voluntary Code under Article 56 AI Act. Non-binding but serves as the primary route to demonstrating compliance with Articles 53 and 55 until harmonised standards are published

**Working Group leadership:**
- WG1 Transparency: Nuria Oliver (Co-Chair), Rishi Bommasani (Vice-Chair)
- WG1 Copyright: Alexander Peukert (Co-Chair), Céline Castets-Renard (Vice-Chair)
- WG2 Safety: Matthias Samwald (Chair), Marta Ziosi and Alexander Zacherl (Vice-Chairs)
- WG3 Systemic Risks: Yoshua Bengio (Chair), Daniel Privitera and Nitarshan Rajkumar (Vice-Chairs)
- WG4 Security: Marietje Schaake (Chair), Anka Reuel and Markus Anderljung (Vice-Chairs)

---

## Summary

The GPAI Code of Practice is the operational counterpart to the AI Act's Chapter V obligations for providers of general-purpose AI models. Where the Act sets the obligations (Articles 53 and 55), the Code provides the specific measures that signatories commit to implementing as the primary demonstrated route to compliance. The Code is structured in three chapters, each produced by dedicated working groups: Transparency (covering Article 53(1)(a)-(b) documentation obligations for all GPAI providers), Copyright (covering Article 53(1)(c) copyright policy obligations for all GPAI providers), and Safety and Security (covering Articles 55(1)(a)-(d) systemic risk obligations only for providers of GPAI models with systemic risk). The Transparency chapter centres on a single Commitment with a **Model Documentation Form** collecting Annex XI Section 1 and Annex XII information. The Copyright chapter centres on **five Measures** including mandatory robots.txt compliance and machine-readable rights reservation protocols. The Safety chapter is substantially more extensive — **10 Commitments across 25 Measures** including a mandatory **Safety and Security Framework**, four specified systemic risks (CBRN, Loss of Control, Cyber Offence, Harmful Manipulation), and four detailed Appendices covering systemic risk taxonomy, similarly-safe models, model evaluations, and security mitigations.

---

## Key Points

### Legal Architecture and Relationship to the Act

The Code works through the Article 56 mechanism: the AI Office facilitates codes of practice that providers can adhere to; adherence provides "a straightforward way of demonstrating compliance" with the obligations; the Commission can approve a code and give it general validity via implementing act (Article 56(6)). Non-signatories must demonstrate compliance via "other adequate means" — typically facing more information requests and scrutiny from the AI Office.

**Adherence is not compliance per se** — both chapters state explicitly that following the Code does not constitute conclusive evidence of compliance. The legal obligations flow from the Act itself; the Code is an interpretive and operational tool.

**Scope applicability:**
- Transparency and Copyright chapters — all GPAI providers (with open-source exception for some obligations per Guidelines)
- Safety and Security chapter — only providers of GPAI models with **systemic risk** (10^25 FLOP threshold or Commission designation)

### Transparency Chapter (Article 53(1)(a)-(b))

**One Commitment, three Measures.**

**Commitment 1 — Documentation**

- **Measure 1.1 Drawing up and keeping up-to-date model documentation.** Signatories document all information in the Model Documentation Form. Previous versions retained for **10 years** after market placement. The Model Documentation Form consolidates Annex XI Section 1 and Annex XII requirements into a single user-friendly form
- **Measure 1.2 Providing relevant information.** On request from AI Office (ex officio or on behalf of national authorities under Articles 91 or 75(3)): provide requested information in most up-to-date form within the period specified in the AI Office's request under Article 91(4). To downstream providers: provide Annex XII information plus additional information necessary for a good understanding of capabilities/limitations, within **14 days of request** save exceptional circumstances
- **Measure 1.3 Ensuring quality, integrity, and security.** Protected from unintended alteration; retained as evidence of compliance

**Model Documentation Form** — indicates for each item whether intended for:
- Downstream providers (provided on request)
- AI Office / national competent authorities (provided on request, with Article 78 confidentiality applying — IP rights, trade secrets, confidential business information)

**Key interpretive points (Recitals):**
- Fine-tuning/modification downstream providers: Commitments limited to the modification (proportionality per recital 109)
- Information should account for market and technological developments to continue serving the purpose (Article 56(2)(a))
- Annex XI Section 2 (systemic risk additional documentation) is covered by Safety Chapter Measure 10.1

### Copyright Chapter (Article 53(1)(c))

**One Commitment, five Measures.** Focused specifically on Article 53(1)(c) — the obligation to put in place a policy to comply with Union copyright law, in particular to identify and comply with Article 4(3) DSM Directive rights reservation.

**Commitment 1 — Copyright Policy**

- **Measure 1.1 Draw up, keep up-to-date, and implement a copyright policy.** Single document incorporating all chapter measures; internal responsibility allocation. Signatories encouraged (not required) to publish a summary
- **Measure 1.2 Reproduce and extract only lawfully accessible content when crawling the Web.** Two substantive commitments:
  - Not circumvent TPMs (Article 6(3) Directive 2001/29/EC) — respect paywalls, access restrictions
  - **Exclude from web-crawling** websites that are "recognised as persistently and repeatedly infringing copyright and related rights on a commercial scale" by courts or public authorities. EU-level dynamic list of such sites to be maintained
- **Measure 1.3 Identify and comply with rights reservations.** Two technical requirements:
  - **Employ web-crawlers that read and follow robots.txt** (IETF RFC 9309)
  - **Identify and comply with other state-of-the-art machine-readable protocols** for Article 4(3) rights reservations (asset-based or location-based metadata adopted by international/European standardisation bodies, or widely adopted by rightsholders)
  - Support development of such protocols
  - Enable rightsholders to obtain information about web-crawlers and rights-reservation implementation (such as via web feed syndication)
  - Search engine operators encouraged to ensure TDM/training compliance does not adversely affect indexing of content whose rightsholders have expressed TDM rights reservations
- **Measure 1.4 Mitigate the risk of copyright-infringing outputs.** Two obligations:
  - Implement "appropriate and proportionate technical safeguards" to prevent output that reproduces training content in an infringing manner
  - Prohibit copyright-infringing uses in acceptable use policy, terms and conditions, or (for open-source) alert users to the prohibition in accompanying documentation
- **Measure 1.5 Designate a point of contact and enable complaints.** Electronic communication with rightsholders; mechanism for rightsholders or collective management organisations to submit "sufficiently precise and adequately substantiated complaints"; act on complaints in a diligent, non-arbitrary manner within a reasonable time

**Key interpretive points:**
- The Chapter is complementary to the Article 53(1)(d) training data summary obligation (separate AI Office template)
- Applies irrespective of whether the Signatory integrates the model into its own AI system or provides it to other entities
- Signatories remain responsible for verifying that copyright policies comply with Member States' implementation of Union copyright law, particularly Article 4(3) DSM Directive
- Web-crawler and TDM activities are the primary compliance flashpoint

### Safety and Security Chapter (Article 55(1)(a)-(d))

**10 Commitments, 25 Measures, 4 Appendices.** Applies only to providers of GPAI models with systemic risk.

#### Architecture

The Chapter establishes a lifecycle compliance architecture: a **Safety and Security Framework** (C1) operationalises everything through continuous risk identification (C2), analysis (C3), acceptance determination (C4), and mitigation (C5 safety, C6 security). Each model requires a **Model Report** (C7) before market placement. Organisational responsibility (C8), serious incident reporting (C9), and additional documentation/transparency (C10) complete the framework.

#### Key Commitments

**Commitment 1 — Safety and Security Framework**
- Framework confirmed no later than 4 weeks after Commission notification under Article 52(1), and no later than 2 weeks before placing model on market
- Must contain: trigger points for lighter-touch evaluations; systemic risk tiers and acceptance criteria; mitigations per tier; timeline estimates for exceeding highest tier; external input description
- Assessment updates every 12 months or on material changes, serious incidents, material risk changes
- Unredacted Framework notification to AI Office within 5 business days of confirmation

**Commitment 2 — Systemic Risk Identification**
- Use Appendix 1.1 risk types (public health, safety, public security, fundamental rights, society)
- Apply nature (Appendix 1.2) and sources (Appendix 1.3) analysis
- Develop scenarios for each identified risk
- **Mandatory consideration of four specified systemic risks** (Appendix 1.4): CBRN, Loss of Control, Cyber Offence, Harmful Manipulation

**Commitment 3 — Systemic Risk Analysis**
- Model-independent information (OSINT, literature, market, incident databases, forecasting, expert panels)
- State-of-the-art model evaluations (Appendix 3): Q&A sets, benchmarks, red-teaming, human uplift studies, model organisms, simulations, proxy evaluations
- Risk modelling building on scenarios
- Risk estimation: qualitative score, qualitative matrix, or quantitative matrix
- Post-market monitoring (11 listed methods): end-user feedback, anonymous reporting, serious incident forms, **bug bounties**, community evaluations, stakeholder dialogues, monitoring repos/social media, privacy-preserving logging with watermarks
- **Independent external evaluators** — free access via API, on-premise, provider-provided hardware, or open weights — to: most capable version, chains-of-thought, helpful-only version. **Safe harbour** for evaluators adhering to responsible vulnerability disclosure that cannot delay publication more than 30 business days
- **Qualified evaluator teams** requirements (Appendix 3.4): PhD + peer-reviewed publications, OR designed peer-reviewed/widely-used evaluation method, OR 3 years relevant experience
- **Minimum 20 business days** for most novel evaluations; adequate compute and engineering budgets

**Commitment 4 — Systemic Risk Acceptance Determination**
- Define systemic risk tiers — measurable, capability-dependent, at least one tier not yet reached
- Require safety margin for: risk source limitations, assessment uncertainties, mitigation effectiveness (circumvention, deactivation, subversion)
- If risks not acceptable: don't place on market, implement mitigations, re-assess

**Commitment 5 — Safety Mitigations**
- Must be robust under adversarial pressure (fine-tuning attacks, jailbreaking)
- Examples: training data filtering, input/output monitoring, fine-tuning for refusal, staged API access, emerging mitigations (chain-of-thought transparency, subversion defence)

**Commitment 6 — Security Mitigations**
- Exemption: inferior to at least one open-weight model
- Apply Appendix 4 mitigations (or equivalent alternatives):
  - **4.1 General security** — MFA, 802.1x authentication, zero trust architecture, email filtering, patching
  - **4.2 Protection of unreleased model parameters** — encryption with 256-bit keys on TPM, confidential computing with hardware-attested trusted execution environments, physical access restrictions
  - **4.3 Hardening interface access** — MFA, 6-monthly review, output rate limiting
  - **4.4 Insider threats** — background checks, sandboxes around models, training data tampering checks
  - **4.5 Security assurance** — independent external reviews, red-teaming, bug bounties, EDR/IDS tools, dedicated security team

**Commitment 7 — Model Reports**
- Before placing on market
- Contents (Measures 7.1-7.5): architecture/capabilities/propensities/affordances; development and training; intended uses; model versions; model specification; risk acceptance justification with safety margins; risk identification/analysis/mitigation documentation; at least **5 random samples** of inputs/outputs/trajectories per evaluation; external evaluator and security reviewer reports; material changes to risk landscape
- **Reference to RAND's "Securing AI Model Weights"** report for security standard alignment
- **Updates at least every 6 months** for most-capable models; notifications to AI Office within 5 business days (may delay up to 15 with interim report)

**Commitment 8 — Systemic Risk Responsibility Allocation (three-lines-of-defence model)**
- 1. Systemic risk oversight — supervisory management body/committee
- 2. Systemic risk ownership — executive management body (Head of Research, Head of Product)
- 3. Systemic risk support and monitoring — Chief Risk Officer or VP Safety & Security Framework, must NOT be responsible for risk-producing activities
- 4. Systemic risk assurance — Chief Audit Executive or Head of Internal Audit

Healthy risk culture indicators include: active internal reporting channels; annual whistleblower policy notification; no retaliation.

**Commitment 9 — Serious Incident Reporting**

Tiered reporting timelines after becoming aware:

| Incident type | Initial report deadline |
|---------------|------------------------|
| Serious + irreversible critical infrastructure disruption | **≤ 2 days** |
| Serious cybersecurity breach (including model weight self-exfiltration, cyberattacks) | **≤ 5 days** |
| Death of a person | **≤ 10 days** |
| Serious harm to health, fundamental rights, property, environment | **≤ 15 days** |

Intermediate reports every **4 weeks** until resolved; final report within **60 days** after resolution. Documentation retained for **at least 5 years**.

**Commitment 10 — Additional Documentation and Transparency**
- Annex XI Section 2 information for AI Office on request
- Retained **10 years** after market placement
- Public transparency: summarised Framework and Model Reports (unless similarly-safe-or-safer model)

#### Appendix 1 — Specified Systemic Risks (Mandatory Scientific Framework)

All signatories MUST identify these four:

1. **Chemical, Biological, Radiological and Nuclear (CBRN)** — lowering barriers to entry for malicious actors, or significantly increasing potential impact in weapon/material design, development, acquisition, release, distribution, or use
2. **Loss of Control** — humans losing ability to reliably direct, modify, or shut down a model; emerging from misalignment, self-reasoning, self-replication, self-improvement, deception, resistance to goal modification, power-seeking behaviour, or autonomously creating/improving AI models
3. **Cyber Offence** — enabling large-scale sophisticated cyberattacks including on critical systems; automated vulnerability discovery, exploit generation, operational use, attack scaling
4. **Harmful Manipulation** — strategic distortion of human behaviour/beliefs targeting large populations or high-stakes decision-makers via persuasion, deception, personalised targeting (particularly multi-turn); could undermine democratic processes and fundamental rights

#### Appendix 1.3 — Sources of Systemic Risk

- **14 model capabilities** including: offensive cyber; CBRN/weapon acquisition; manipulation/persuasion/deception; autonomous operation; long-horizon planning; self-reasoning; evasion of human oversight; self-replication/self-improvement; automating AI R&D; tool use including computer use
- **10 model propensities** including: misalignment with intent/values; hallucination; discriminatory bias; lawlessness; goal-pursuing with harmful resistance to goal modification; power-seeking; colluding with other AI
- **13 model affordances and other sources** including: tools/compute/physical systems; release/distribution strategies; adversarial guardrail removal vulnerability; exfiltration vulnerability; user count; offence-defence balance; AI-AI interactions

---

## Observations

### Clarity

The Code is unusually clear for a technical compliance document. The Transparency chapter reduces to a single Model Documentation Form — a pragmatic design that allows providers to satisfy multiple documentation obligations (Annex XI Section 1, Annex XII) in one place. The Copyright chapter's five measures are concretely actionable: crawler hygiene (Measure 1.2), robots.txt compliance (Measure 1.3), output safeguards (Measure 1.4), complaint channels (Measure 1.5).

The Safety chapter is more complex but well-structured. The lifecycle compliance architecture — Framework → Identification → Analysis → Acceptance → Mitigation → Model Report — provides a clear process. The distinction between Commitments (what to achieve) and Measures (how to achieve it) is consistent. The Appendices are appropriately granular: Appendix 1 provides the taxonomy, Appendix 3 details evaluation requirements, Appendix 4 specifies security mitigations.

The Code's clarity strength is **specificity of thresholds**:
- 2/5/10/15-day serious incident reporting
- 20-business-day minimum for novel evaluations
- 30-business-day maximum publication delay for responsible disclosure
- 5 random samples per evaluation in Model Reports
- 6-month update cycle for most-capable models
- 10-year retention for documentation
- 5-year retention for incident documentation
- 256-bit encryption minimum
- 4-week intermediate reporting cadence
- 60-day final report after resolution

Clarity weaknesses:

**"State-of-the-art" pervasively underdefined.** The Code relies on "state-of-the-art" for evaluations, risk modelling, safety mitigations, and security measures. While this allows evolution, it creates assessment uncertainty — what is the current state of the art, and who determines when practice falls below it?

**"Reasonable foreseeability" thresholds.** Framework notification timing, Model Report triggering events, and material change assessments all depend on what providers can "reasonably foresee." The Code doesn't provide thresholds for this judgement.

**Safety margin specification.** Commitment 4 requires safety margins "accounting for risk source limitations, assessment uncertainties, and mitigation effectiveness" but provides no quantitative guidance on margin sizes.

### Measurability

Highly measurable for process and documentation obligations (timelines, retention periods, sample sizes). Less measurable for substantive risk determinations (is the risk acceptable? is the mitigation effective? has the state of the art shifted?).

The Code implicitly treats the four specified systemic risks as the primary substantive evaluation matrix. Providers must identify, analyse, and mitigate CBRN, Loss of Control, Cyber Offence, and Harmful Manipulation risks for every model. This creates a standardised evaluation lattice even if the individual assessments remain judgement-based.

### Gaps

**Compute scaling as risk signal.** The Code references Appendix 1.3 capabilities (including adaptive learning, long-horizon planning, self-improvement) but does not tie systemic risk tier definitions to specific compute or capability benchmarks. Providers determine their own tiers, which the AI Office can challenge but cannot prescribe. The result: compliance-via-self-definition.

**Mitigation effectiveness testing.** Measure 5.1 requires mitigations "robust under adversarial pressure (fine-tuning attacks, jailbreaking)" but doesn't specify adversarial testing budgets, diversity of attack vectors, or pass/fail thresholds. A provider could claim fine-tuning robustness based on limited red-teaming.

**Open-source models within systemic risk scope.** The open-source exemption from Chapter V does NOT apply to systemic risk models. But the Safety chapter doesn't specifically address what Loss of Control or Cyber Offence mitigations look like for an open-weight systemic risk model, where typical safety mitigations (staged API access, input/output monitoring) are not applicable.

**External evaluator ecosystem.** Commitment 3.5 requires independent external evaluators, with qualifications defined and a 20-business-day public call required to demonstrate effort. But the ecosystem of qualified external evaluators is nascent. In practice, the pool is small, reputations matter, and evaluator selection may effectively be constrained.

**Model Report publication.** Measure 10.2 requires public transparency of Framework and Model Reports "where necessary to assess/mitigate risk" — but the determination of necessity rests with the provider. Competitive sensitivity will push toward minimal disclosure; safety advocates will push for maximum. The Code does not resolve this tension.

**Copyright chapter's gap on generative output.** Measure 1.4 requires safeguards against output reproducing training content in an infringing manner. This is challenging to implement technically at scale; "appropriate and proportionate" leaves significant interpretive space. Rightsholders may view current practice as inadequate; providers may view stringent requirements as impractical.

**Downstream provider information boundaries.** Transparency Measure 1.2 requires information beyond Annex XII "necessary to enable [downstream providers] to have a good understanding of capabilities and limitations" and to comply with their obligations. What is "necessary" is fact-dependent and will generate disputes.

### Feasibility

Feasibility varies by chapter and by provider profile:

**Transparency chapter** — highly feasible for all provider types. The Model Documentation Form is a consolidated template. Large providers already produce substantial documentation (Model Cards, technical reports); this formalises and extends existing practice. Smaller providers face new documentation burden.

**Copyright chapter** — mostly feasible but with sharp implementation questions:
- robots.txt compliance is straightforward (Measure 1.3(a))
- Non-circumvention of TPMs and exclusion of infringing sites is achievable (Measure 1.2)
- Machine-readable protocols beyond robots.txt (Measure 1.3(b)) depend on ecosystem development — if rightsholders don't adopt standard protocols, provider compliance depends on good-faith effort
- Technical safeguards against infringing outputs (Measure 1.4) is the most challenging element — current technical capabilities can reduce but not eliminate this risk

**Safety chapter** — feasible for well-resourced frontier labs, challenging for others:
- OpenAI, Anthropic, Google DeepMind, Meta AI already operate safety teams, red-teaming programmes, and incident response infrastructure that can be adapted
- Academic consortia and smaller providers of sub-frontier models at the systemic risk threshold face substantial compliance cost
- The three-lines-of-defence governance structure (Commitment 8) requires organisational structures not universal in tech companies

### Internal Consistency

The three chapters are consistent with the AI Act and with each other. Cross-references are explicit:
- Transparency chapter handles Article 53(1)(a)-(b); Safety chapter Measure 10.1 handles Annex XI Section 2 (systemic risk additions)
- Copyright chapter complements Article 53(1)(d) training data summary (separate AI Office template)
- Safety chapter's incident reporting timelines align with the Commission's separate Serious Incident Reporting Guidance (Sep 2025)

One small tension: the Copyright chapter's Measure 1.3(a) explicitly requires robots.txt compliance, while the Commission Guidelines on Prohibited AI Practices (July 2025) state that "the respect of opt-out of internet protocols such as robot.txt does not affect the untargeted nature of the scraping" under Article 5(1)(e). This reflects different functions — robots.txt is necessary but not sufficient for copyright compliance and is not sufficient to render facial-image scraping targeted. But the treatment in the two documents could confuse practitioners.

### Coverage

The three chapters collectively cover the complete Chapter V obligation set:
- Article 53(1)(a): technical documentation → Transparency Chapter Measure 1.1
- Article 53(1)(b): information for downstream providers → Transparency Chapter Measure 1.2
- Article 53(1)(c): copyright policy → Copyright Chapter Commitment 1
- Article 53(1)(d): training data summary → covered by separate AI Office template (referenced but not elaborated)
- Article 55(1)(a): adversarial testing → Safety Chapter Measure 3.2, Appendix 3
- Article 55(1)(b): systemic risk assessment/mitigation → Safety Chapter Commitments 2-5
- Article 55(1)(c): serious incident reporting → Safety Chapter Commitment 9
- Article 55(1)(d): cybersecurity → Safety Chapter Commitment 6, Appendix 4

Transparency and Copyright chapters treat their domains concisely because the Act's Annexes (XI, XII) and Directive 2019/790 already provide substantive content. Safety chapter operates extensively because Article 55 is where the Act is most operationally underspecified.

### International Alignment

The Code draws from international sources:
- **NIST AI Risk Management Framework** — systemic risk identification approach echoes NIST structure
- **ISO/IEC 42001** — AI management systems standard; governance structure in Commitment 8 is compatible
- **UK AI Safety Institute evaluation approach** — Safety chapter's emphasis on adversarial testing, uplift studies, independent evaluators aligns with AISI methodology
- **Bletchley/Seoul Declaration principles** — four specified systemic risks (CBRN, Loss of Control, Cyber Offence, Harmful Manipulation) map closely to concerns in the Bletchley process
- **RAND "Securing AI Model Weights"** — directly referenced in Commitment 7 for security standards

For UK and US frontier providers, the Code's substantive content is largely compatible with existing internal practices. The compliance burden is more about documentation formalisation and regulatory notification than about new substantive requirements.

**Code of Practice versus harmonised standards.** The Code is explicitly temporary — it provides the primary compliance route until harmonised standards (under Article 40) are developed by European Standards Organisations (CEN/CENELEC/ETSI). Those standards, once published and adopted, provide presumption of conformity (Articles 53(4), 55(2)). This follows the EU's New Legislative Framework approach.

---

## Overall Assessment

The GPAI Code of Practice is the operational bridge between the EU AI Act's abstract Chapter V obligations and concrete compliance action for GPAI providers. Its three chapters divide work sensibly: Transparency focuses on documentation architecture, Copyright on TDM and rights respect, Safety on the substantive systemic risk management for frontier models.

The Transparency chapter is the most elegant — a single Model Documentation Form consolidates multiple obligations into a unified template. The pragmatism here is notable: rather than require separate documentation streams for AI Office requests and downstream providers, the Form handles both with role-based access.

The Copyright chapter is substantively the most consequential for the AI training data ecosystem. The combination of mandatory robots.txt compliance (Measure 1.3(a)) and the requirement to implement other state-of-the-art machine-readable rights reservation protocols (Measure 1.3(b)) establishes a compliance floor that many current practices may not meet. The chapter effectively formalises the opt-out approach established in Directive 2019/790 Article 4(3), converting what was a legal right for rightsholders into an operational requirement for AI providers.

The Safety chapter is the regulatory innovation. No prior jurisdiction has specified a compliance framework for frontier AI safety at this level of operational detail. The four specified systemic risks (CBRN, Loss of Control, Cyber Offence, Harmful Manipulation) create a standardised evaluation lattice. The three-lines-of-defence governance structure imports financial-services risk management paradigms. The tiered incident reporting timelines (2/5/10/15 days) create concrete reporting obligations.

For UK-based firms providing GPAI models to EU customers, the practical implications are:

1. **Sign the Code or demonstrate adequate alternatives.** Non-signatories face more AI Office scrutiny. The Code provides a structured compliance narrative; bespoke compliance requires bespoke documentation
2. **Implement the Model Documentation Form** — this satisfies the Transparency obligations and is useful internal documentation regardless of regulatory status
3. **Audit web-crawling and TDM practices** — particularly robots.txt compliance (Measure 1.3(a)), exclusion of infringing sites (Measure 1.2(b)), and rights reservation protocol implementation
4. **If providing a systemic risk model (10^25 FLOP):** the Safety chapter is extensive. Establish a Safety and Security Framework, allocate three-lines-of-defence responsibilities, implement the security mitigations in Appendix 4, and plan for Model Reports every 6 months
5. **Plan for external evaluator requirements** — publicly advertise evaluator searches (20-business-day minimum), provide required access (API, on-premise, or helpful-only variants), respect safe harbour provisions
6. **Align with RAND Securing AI Model Weights standard** for security. The Code references this publication specifically; demonstrating alignment provides defensible security compliance
7. **Prepare for 2027 retrospective compliance deadline** for models placed on market before 2 August 2025

The Code is a temporary bridge until harmonised standards develop. Its substantive content will likely inform those standards, but the standards themselves may be more detailed and prescriptive. Providers relying on the Code for compliance should anticipate a transition to standards-based compliance in 2026-2028.

For firms across the compliance spectrum, the Code rewards engagement. Signatories benefit from the presumption of compliance, reduced AI Office information requests, mitigation of fines, and formalised trust with regulators. The operational cost — documentation, governance structures, external evaluations — is substantial but bounded. For frontier labs already operating sophisticated safety programmes, much of the Code codifies existing practice.

The Code's most significant substantive contribution is the **four specified systemic risks framework**. CBRN, Loss of Control, Cyber Offence, and Harmful Manipulation now form the standard evaluation matrix for frontier AI across EU-accessible operations. Whether by Code adherence, alternative compliance, or eventual harmonised standards, providers will need to demonstrate assessment and mitigation of these specific risk categories. This is the most operationally consequential harmonisation in global AI safety governance to date.

---

## Sources

- [GPAI Code of Practice — Transparency Chapter (PDF)](../../source/GPAI-Code-of-Practice-Transparency-Jul-2025.pdf)
- [GPAI Code of Practice — Copyright Chapter (PDF)](../../source/GPAI-Code-of-Practice-Copyright-Jul-2025.pdf)
- [GPAI Code of Practice — Safety and Security Chapter (PDF)](../../source/GPAI-Code-of-Practice-Safety-Security-Jul-2025.pdf)
- [GPAI Code of Practice — Official EU landing page](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai)
- Related reviews in this repo:
  - [EU AI Act (review 01)](01-eu-ai-act.md)
  - [Guidelines on Definition of AI System (review 02)](02-guidelines-definition-ai-system.md)
  - [Guidelines on Prohibited AI Practices (review 03)](03-guidelines-prohibited-ai-practices.md)
  - [Commission GPAI Guidelines (review 04)](04-commission-gpai-guidelines.md)
- External references:
  - IETF RFC 9309 (Robots Exclusion Protocol)
  - RAND Corporation, "Securing AI Model Weights" report
  - Directive (EU) 2019/790 Article 4(3) — DSM text and data mining rights reservation
