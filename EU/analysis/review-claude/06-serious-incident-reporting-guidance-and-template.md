# EU AI Act Article 73 — Serious Incident Reporting Draft Guidance and Template — Review

**Documents:**
- Draft Guidance Article 73 AI Act — Incident Reporting (High-risk AI Systems) — 13 pages
- Incident Report for Serious Incidents under the AI Act (High-risk AI Systems) — Reporting Template (Version 1.0.0) — 7 pages

**Published:** 26 September 2025
**Issuing body:** European Commission (public consultation closed 7 November 2025)
**Legal status:** Draft — non-binding; final version pending post-consultation revision
**Enters into application:** 2 August 2026 (when Article 73 AI Act applies)

---

## Summary

These paired documents operationalise Article 73 of the EU AI Act, which requires providers of high-risk AI systems to report serious incidents to national market surveillance authorities. The Draft Guidance clarifies key terms ("serious incident," "malfunction," "widespread infringement," "irreversible disruption," "serious harm to property/environment"), maps obligations across the value chain (providers, deployers, authorised representatives, market surveillance authorities, national competent authorities, Commission, AI Board), and addresses interplay with sector-specific incident reporting regimes (NIS2, CER, DORA, MDR/IVDR, GDPR). The Template is a structured 5-section form with categorised incident types, submitter/provider/authorised representative fields, AI system identification (including EU database registration ID), free-text incident description, and provider analysis including root cause investigation. Together they establish the UK's most salient operational obligation for providers of high-risk AI systems serving EU clients: within 2, 10, or 15 days (depending on severity) of becoming aware, submit a structured report to the market surveillance authority of the Member State where the incident occurred. Article 73 does not apply to systemic risk GPAI (Article 55(1)(c) handles that separately).

---

## Key Points

### What Triggers Reporting (Article 3(49), Article 73(2))

A **serious incident** is an incident or malfunction of an AI system that directly or indirectly leads to any of:

- **(a)** Death of a person, or serious harm to a person's health
- **(b)** Serious and irreversible disruption of management or operation of critical infrastructure
- **(c)** Infringement of obligations under Union law intended to protect fundamental rights
- **(d)** Serious harm to property or the environment

A **widespread infringement** (Article 3(61)) additionally triggers reporting — an act or omission contrary to Union law protecting individual interests that (a) has harmed or is likely to harm collective interests in at least two Member States other than where originated, OR (b) caused/causes/is likely to cause harm to collective interests and has common features (same unlawful practice or same interest being infringed, concurrent, by the same operator) in at least three Member States.

### Incident vs Malfunction (Paragraphs 7-12)

The AI Act defines "serious incident" but not "incident." The Draft Guidance distinguishes:
- **Incident** — an event where development or use of an AI system results in **actual harm** (OECD definition)
- **AI hazard** — an event where development or use is **potentially harmful** (OECD definition)
- **Malfunction** — any function not performing as intended, OR the AI system fails to uphold performance stated in technical documentation for its intended purpose and reasonably foreseeable misuse

Practical examples of incidents/malfunctions: **misclassifications, significant drops in accuracy, temporary system downtime, unexpected system behaviour**.

### Causation: Direct or Indirect (Paragraphs 13-14)

The incident/malfunction must be causal, or reasonably likely to be causal, for the specified harms. Without the incident, the harm would not have occurred (or reasonably likely not have occurred).

**Indirect causation examples** (paragraph 13):
- AI provides incorrect analysis of medical imaging → physician makes incorrect diagnosis → patient harm
- AI credit scoring incorrectly flags unreliability → loan denied
- AI classifies patient as low-risk → doctor fails to detect condition
- AI recruitment discards highly qualified candidates by gender/ethnicity → hiring organisation pursues only post-AI-screened applications

**Limit on causation** (paragraph 14): direct or indirect causation applies only when the AI system is used in accordance with its intended purpose and reasonably foreseeable misuse — not when the incident is due to wrong, unexpected use or unexpected user errors.

### Categories of Harm — Interpretive Detail

**Death / Serious harm to health** (paragraph 15, from MDR-inspired criteria):
- Life-threatening illness or injury
- Temporary or permanent impairment of body structure/function
- Condition necessitating hospitalisation or prolongation of existing hospitalisation
- Medical/surgical intervention to prevent the above
- Chronic disease or serious psychological disease (impairing significant life activities)
- Foetal distress, foetal death, or congenital abnormality/birth defects

**Critical infrastructure disruption** (paragraphs 16-22):
- Cross-reference to CER Directive 2022/2557 definition
- Disruption "serious" if: imminent threat to life/physical safety, destruction of key infrastructure, disruption to social/economic activities
- **Must also be irreversible**. Considerations for "irreversibility":
  - Rebuilding physical infrastructure or destroying specialised equipment not readily available
  - Contamination of water, soil, air
  - Loss or corruption of essential records (patient data, civil registries, financial transactions) that cannot be restored
  - Permanent disablement of critical nodes (rail junction, power substation, landing station)
  - Loss of space-based assets (GNSS satellite) vacating orbital slot for years
- Interplay with NIS2: reported NIS2 incidents with severe operational disruption that is irreversible AND caused by AI system malfunction should also be considered AI Act serious incidents

**Fundamental rights infringement** (paragraphs 23-26):
- "Fundamental rights" = Charter of Fundamental Rights of the EU
- "Intended to protect fundamental rights" interpreted narrowly
- Only infringements that "significantly interfere with Charter-protected rights on a large scale" are reportable
- Examples: AI recruitment excluding candidates by ethnicity/gender; credit scoring excluding persons by name origin or neighbourhood; biometric system frequently misidentifying people of different ethnic backgrounds

**Serious harm to property** (paragraph 27): economic impact including cost of repair/replacement (damage considered serious if impairs intended usability/substance; in any case exceeding 5% of purchase price), cultural/historical significance, livelihood impact, permanence, ripple effects.

**Serious harm to environment** (paragraphs 28-30):
- Guidance drawn from Environmental Liability Directive 2004/35/EC and Environmental Crime Directive 2024/1203
- Assessment elements: baseline condition, duration (short/medium/long-term), extent, reversibility
- Examples: contamination of environmental resources, disruption of natural ecosystems

**Widespread infringement** (paragraphs 31-36):
- Implicit reference: widespread infringement must ALSO qualify as a serious incident to be covered by Article 73(3)
- "Act or omission" interpreted broadly
- "Collective interests" = interests shared by a group (distinct from individual preferences). Examples: environmental protection, public health, functioning of democratic institutions
- "Occurring concurrently" = simultaneous harmful practices

### Reporting Timelines (Article 73(2)-(5))

| Type of serious incident | Deadline to report (after awareness) |
|--------------------------|--------------------------------------|
| Widespread infringement OR serious and irreversible disruption of critical infrastructure | **2 days** |
| Death of a person | **10 days** |
| All other serious incidents | **15 days** |

Article 73(5): If necessary to ensure timely reporting, an **initial incomplete report** may be submitted, followed by a complete report.

For medical devices (safety components or themselves medical devices under MDR/IVDR): Article 73 notification is **limited to fundamental rights infringements** (Article 73(10)). The standard sectoral regime covers the other harm categories.

### Obligations by Actor

**Providers of high-risk AI systems (Article 73(1)-(7)):**
- Report to market surveillance authority of Member State where incident occurred (if location unknown, use deployer's business location)
- Timelines as above
- Perform investigations without delay — risk assessment of incident and corrective action (Article 73(6))
- **Must not alter the AI system** in a way that may affect subsequent evaluation of causes, prior to informing competent authorities
- Alterations considered subject to notification: components directly involved, changes affecting data availability for investigation (overwriting training datasets, disabling monitoring tools), changes affecting reconstruction of event sequence (log file modifications, sensor data, decision-making algorithms)
- Cooperate with competent authorities and notified body — respond within reasonable time but not later than **24 hours**

**Deployers of high-risk AI systems (Article 26(5)):**
- Upon identifying serious incident, immediately inform provider, then importer or distributor, and market surveillance authority
- "Immediately" = within 24 hours
- If deployer cannot reach provider (provider does not answer within 24 hours), provider obligations apply mutatis mutandis to the deployer

**Providers of GPAI models with systemic risk (Article 55(1)(c)):**
- Report to AI Office (not market surveillance authority)
- The Draft Guidance explicitly does NOT cover this — it is covered by the Commission GPAI Guidelines (referenced review 04) and GPAI Code of Practice Safety chapter Commitment 9 (referenced review 05)

**Market surveillance authority (Article 73(8)):**
- Must take appropriate measures within **7 days** from notification (per Article 19 of Regulation 2019/1020)
- For fundamental rights incidents: inform national public authorities or bodies supervising respect of Union law protecting fundamental rights (referred to in Article 77)

**National competent authorities (Article 73(11)):**
- Immediately notify the Commission of any serious incident, whether or not they have taken action

**Commission:** Establishes alert system to inform other market authorities

**AI Board:** May evaluate and review incident reporting (Article 66(e))

### Interplay with Other Union Incident Reporting (Section 4)

Article 73(9) AI Act establishes **interplay rule**: where high-risk AI systems in Annex III are subject to Union legislative instruments laying down reporting obligations equivalent to Article 73, notification is **limited to fundamental rights infringements** (Article 3(49)(c)).

**CER Directive 2022/2557** (Critical Entities Resilience): 24-hour notification for incidents disrupting essential services. Annex III point 2 sectors (digital infrastructure, road traffic, water, gas, heating, electricity) are subject to CER. Under AI Act, obligation for these sectors is **limited to fundamental rights** violations (paragraphs 57-59).

**NIS2 Directive (EU) 2022/2555**: 24-hour early warning, 72-hour incident notification, one-month final report. Annex III point 2 sectors overlap; same limitation to fundamental rights under AI Act.

**DORA (Digital Operational Resilience Act) and Regulation 2025/302**: Financial entities report ICT-related incidents. AI systems under Annex III 5(b) and 5(c) (credit scoring, insurance pricing) — reporting limited to fundamental rights violations under AI Act (paragraphs 61-63). Examples: ML model embedding postcode as feature leading to systematic loan rejections for minority neighbourhoods; AI risk scoring tool inferring genetic predispositions from pharmacy-purchase data.

**GDPR Article 33**: Personal data breach notification. May overlap with Article 73; Commission will later specify interplay.

**MDR / IVDR** (Regulations 2017/745 and 2017/746): For AI systems that are safety components of medical devices or themselves medical devices, Article 73 AI Act notification is **limited to fundamental rights infringements**. Other harms go via the sectoral regime.

**Cyber Resilience Act (Regulation 2024/2847)**: Commission will specify interplay at a later point.

**Annex I Section B products** (motor vehicles, aviation, marine, rail): Article 2(2) AI Act establishes these AI systems are deemed sufficiently regulated under sectoral frameworks and **do not fall under Article 73** (paragraph 67).

### The Reporting Template (5 sections)

**Section 1 — Administrative information:**
- 1.1 Responsible market surveillance authority (country + reference number)
- 1.2 Date, type (Initial / Follow up / Combined initial-and-final / Final reportable / Final non-reportable), classification of serious incident (death, health harm, critical infrastructure disruption, fundamental rights infringement, property harm, environmental harm, other reportable)
- 1.3 Submitter information (provider / deployer / authorised representative / other):
  - 1.3.1 Submitter role
  - 1.3.2 Provider organisation + full contact details
  - 1.3.3 Authorised representative organisation + contact (if applicable)
  - 1.3.4 Submitter details if not provider or authorised representative
  - 1.3.5 Information about other incident obligations (which regulation/law the incident has already been reported under)

**Section 2 — AI System information:**
- 2.1 EU Database registration ID (Article 71 — confirms registration)
- 2.2 System name (brand/trade/proprietary/common), description, nomenclature, model, catalogue/reference, serial number, lot/batch number, software version, firmware version

**Section 3 — Incident information:**
- 3.1 Nature of incident — free text description: (1) what went wrong, (2) effects, (3) likely causality
- 3.2 AI System information — number of users affected, operator (professional user or other), remedial actions
- 3.3 Initial reporter — full contact details of the person who initially reported

**Section 4 — Provider analysis:**
- 4.1 Provider's preliminary comments — preliminary results and conclusions of investigation, initial corrective/preventive actions, planned further investigations
- 4.2 Cause investigation and conclusion:
  - For Final (Serious incident): root cause / causative factors description and conclusion
  - For Final (Non-reportable): rationale for why not reportable
  - Risk assessment review: has it been reviewed? If yes, is it still adequate? Results of assessment

**Section 5 — General comments** (free text)

**Disclaimer on template:** "Submission of this report does not represent a conclusion by the provider and/or authorised representative or the market surveillance authority that the content of this report is complete or accurate, that the AI system(s) listed failed in any manner and/or that the AI system(s) caused or contributed to the alleged serious incident."

### Initial Report vs Complete Report vs Final Report

The framework supports staged reporting:
- **Initial report** — may be incomplete, submitted to meet the timeline
- **Follow-up report** — updates as investigation progresses
- **Combined initial and final** — if investigation completes within timeline
- **Final (reportable incident)** — substantiated serious incident
- **Final (non-reportable incident)** — initial report submitted but investigation concluded no reportable incident (with rationale)

---

## Observations

### Clarity

The Draft Guidance provides operationally valuable definitions. The distinction between "incident" and "malfunction" (paragraphs 7-12), the examples of indirect causation (paragraph 13), and the criteria for irreversibility of critical infrastructure disruption (paragraphs 19-21) are precise enough to support compliance analysis.

The interplay section (Section 4) is the most useful part of the document. The AI Act's Article 73(9) "equivalent reporting regime" rule could have produced extensive uncertainty; the Guidance maps each sectoral regime to the AI Act explicitly:
- CER (critical infrastructure): AI Act limited to fundamental rights
- NIS2 (cybersecurity): AI Act limited to fundamental rights for overlap sectors
- DORA (finance): AI Act limited to fundamental rights for credit/insurance AI
- MDR/IVDR (medical devices): AI Act limited to fundamental rights
- Annex I Section B (transport, aviation, marine, rail): AI Act does not apply

This produces a usable compliance matrix: providers of regulated-sector AI systems report fundamental rights incidents via Article 73 and everything else via sectoral regimes, avoiding double reporting of substantive harms while preserving AI-specific fundamental rights oversight.

Clarity weaknesses:

**The 5% of purchase price threshold for serious property damage** (paragraph 27) is numerically specific but substantively arbitrary. A 4% damage to a multi-million EUR asset is not "serious"; a 10% damage to a low-value asset is. The threshold is a floor, not a ceiling, but its presence may push assessors toward mechanical application.

**"Significantly interferes with Charter-protected rights on a large scale"** (paragraph 26) is necessary but difficult. "Large scale" is undefined. A single algorithmic hiring decision discriminating against one candidate is probably not reportable; systematic discrimination affecting thousands clearly is. Where the threshold sits between these is left to market surveillance authority interpretation.

**Investigation alterations** (paragraphs 42-43) require providers to refrain from changes that "may affect subsequent evaluation of causes." In practice, operational pressure to mitigate ongoing harm may conflict with evidentiary preservation. The Guidance flags this tension but does not resolve it — providers face a genuine dilemma where immediate corrective action may prejudice investigation.

### Measurability

Highly measurable on timing:
- 2/10/15-day initial report deadlines
- 24-hour deployer-to-provider escalation
- 24-hour provider cooperation response time
- 7-day market surveillance action window
- Immediate Commission notification from national authorities

Less measurable on substantive thresholds:
- Serious harm to health (qualitative criteria)
- Serious disruption of critical infrastructure (qualitative criteria)
- Significant interference with fundamental rights (qualitative)
- Serious harm to property (5% floor, then qualitative)
- Serious harm to environment (baseline-dependent)

The template standardises reporting content but cannot standardise threshold judgements. Providers must decide whether a given incident reaches the threshold, document their reasoning, and be prepared to defend it. The market surveillance authority's 7-day review window means decisions are second-guessed quickly.

### Gaps

**Automatic reporting mechanisms**. The template is designed for manual form submission. For high-volume AI systems (content moderation, credit scoring, healthcare diagnostics), serious incidents may occur frequently enough to warrant automated logging and filtering. The Guidance does not address automated reporting pipelines or the technical infrastructure providers should build.

**Pre-2026 incidents**. Article 73 applies from 2 August 2026. Incidents occurring before that date are not retroactively reportable, but what about incidents detected after August 2026 that began before? The Guidance does not address transitional scenarios.

**Value chain complexity for foundation models**. A high-risk AI system built on a GPAI model may fail due to the underlying model's behaviour. The provider of the high-risk system reports under Article 73; the GPAI provider reports under Article 55(1)(c). The relationship between these reports — whether they should cross-reference, whether the AI Office and national market surveillance authority should share data — is not specified.

**Deployer investigation capabilities**. Article 26(5) requires deployers to inform providers immediately of serious incidents. But deployers typically have limited technical visibility into AI system internals. The Guidance treats the deployer as the "front line" detector but does not address the practical challenge of deployer-detected incidents being misdiagnosed.

**Cross-border incidents** are addressed minimally. If a UK-based provider's AI system causes a serious incident affecting citizens across multiple EU Member States, which market surveillance authority receives the report? The Guidance says "where the incident occurred" (paragraph 37) but this is unclear for distributed digital incidents (e.g., algorithmic discrimination affecting EU-wide user bases).

**Market surveillance authority coordination**. With 27 Member States each with their own market surveillance authority, a provider may face coordination challenges when an incident affects multiple jurisdictions. The Commission's alert system is mentioned briefly but details are absent.

**Documentation retention**. The template does not specify how long submitted reports are retained by the market surveillance authority or the Commission. The Safety Chapter of the Code of Practice specifies 5 years for provider-side documentation, but public-sector retention is unclear.

**Template scope limits**. The template covers incidents but does not support "hazard" or "near-miss" reporting that could enable proactive learning. This is a policy choice — the AI Act requires incident reporting, not hazard reporting — but the Code of Practice's provision for near-miss tracking (Safety Chapter Measure 9.2) suggests the Commission recognises the value of broader reporting.

### Feasibility

For well-resourced providers (large vendors with established compliance programmes), Article 73 compliance is feasible:
- Incident logging infrastructure likely exists for operational reasons
- Legal and compliance staff can manage report drafting
- Market surveillance authority relationships can be established pre-incident

For smaller providers (especially those serving regulated sectors), compliance is more challenging:
- 2-day deadline for critical infrastructure incidents requires always-on incident response
- 24-hour deployer-to-provider notification requires dedicated contact points
- Investigation-preservation requirements (paragraph 42) require technical discipline that constrains operational flexibility

The template itself is reasonably designed. Required fields are clear; free-text sections (Nature of Incident, Provider Preliminary Comments, Cause Investigation) allow flexibility. The Version 1.0.0 designation suggests iteration is planned.

**Administrative burden** will be substantial across the ecosystem. Each reportable incident potentially generates:
- Initial report within tight deadline
- Follow-up reports as investigation progresses
- Final report with root cause analysis
- Coordination with deployer, importer, distributor, authorised representative
- Notification to sectoral regulators where applicable
- Cooperation with market surveillance authority investigation

Providers should expect this to be a material operational function from August 2026 onward.

### Internal Consistency

The Guidance is internally consistent and aligns well with other Commission guidance:

- **Compatible with GPAI Code of Practice Commitment 9** (serious incident reporting for systemic risk GPAI) — differential obligations (AI Office vs market surveillance authority) are maintained
- **Compatible with Article 26(5)** deployer obligations
- **Compatible with Article 73(10)** sector-specific reporting exemptions
- **Compatible with Article 71** EU database registration requirement (template Section 2.1)

One small inconsistency: the 5% of purchase price threshold for serious property damage (paragraph 27) is not mirrored elsewhere in the AI Act framework. It appears to originate in product safety traditions but is not grounded in a specific AI Act provision.

### Coverage

Coverage within scope is comprehensive. All harm categories are addressed, all actor obligations are mapped, sectoral interplay is documented, and the template covers the essential reporting fields.

What is deliberately outside scope:
- Article 55(1)(c) systemic risk GPAI incident reporting (covered by Code of Practice Safety Chapter)
- Annex I Section B products (subject to sectoral regimes only)
- Personal data breach reporting under GDPR (separate regime)
- Near-miss / hazard reporting (not required by the AI Act)

### International Alignment

The Guidance explicitly references OECD work:
- **OECD AI Incidents Monitor** and **Common Reporting Framework** — the AI Act incident monitoring "seeks to align with the OECD framework wherever possible" (paragraph 3)
- OECD definitions of "AI incident" (actual harm) and "AI hazard" (potential harm) are adopted

This alignment is significant for cross-border incident data sharing. If UK and EU regulators are working with OECD-aligned definitions, incidents reported in one jurisdiction are more tractable for analysis in another. For UK-based firms serving EU clients, documentation prepared for EU reporting should be reusable for UK incident reporting (where applicable) and for international benchmarking.

For the UK specifically, the AI Act incident reporting regime sits alongside:
- UK sector-specific incident regimes (e.g., ICO data breach reporting, FCA operational incident reporting)
- Product safety regimes (MHRA for medical devices, OPSS for other products)
- No UK-wide AI-specific incident reporting requirement (yet)

UK-based providers serving EU markets will find themselves reporting incidents to EU authorities that they are not required to report to UK authorities. This creates asymmetric compliance but is not inherently problematic — Article 73 is comparable in burden to existing UK GDPR/sectoral reporting obligations.

---

## Overall Assessment

The Draft Guidance and Template are well-designed, operationally focused documents that transform Article 73's abstract obligations into a compliance workflow. Combined, they give providers of high-risk AI systems a clear answer to the question: "what do we do when something goes wrong?"

Their greatest strength is the sectoral interplay section. The AI Act's Article 73(9) "equivalent reporting regime" rule could have been a source of significant compliance uncertainty; the Guidance resolves it pragmatically by limiting AI Act reporting to fundamental rights issues when sectoral reporting covers the other harm categories. This avoids duplicate reporting while preserving AI-specific oversight of the dimension the AI Act uniquely addresses.

Their greatest weakness is the threshold ambiguity. "Serious harm," "significant interference," "irreversible disruption," "large scale" — these require judgement. The Guidance provides criteria and examples but cannot eliminate the interpretive burden. Providers should expect to err on the side of over-reporting in borderline cases, at least until enforcement patterns develop.

For UK-based firms serving EU clients, the practical implications are:

1. **Determine scope first.** Is the AI system high-risk under Article 6(2) (Annex III) or Article 6(1) (safety component of Annex I legislation)? If yes, Article 73 applies from 2 August 2026.

2. **Identify the responsible market surveillance authority.** For each Member State where the AI system operates or produces output, identify the market surveillance authority and establish a reporting channel.

3. **Establish incident detection infrastructure.** Build logging, monitoring, and anomaly detection appropriate to the AI system's intended purpose and risk profile. Deployer contract terms should require 24-hour notification of detected incidents.

4. **Map sectoral interplay.** If the AI system is subject to DORA, NIS2, CER, MDR/IVDR, or other sectoral regimes, align incident response workflows so that fundamental rights issues are reported under Article 73 and other categories via sectoral channels.

5. **Prepare template fields in advance.** The Section 1 (administrative) and Section 2 (AI system) fields can be pre-populated: provider contact, EU database registration ID, system name/model/version. Section 3-5 fields require incident-specific content.

6. **Preserve investigation integrity.** Before altering the AI system post-incident, consider whether alterations affect evidence. Document decisions carefully. The 24-hour cooperation window with authorities constrains unilateral action.

7. **Plan for staged reporting.** The 2/10/15-day deadlines are tight. Initial reports may be incomplete; follow-up and final reports will update. Build the organisational capacity to submit multiple reports per incident.

8. **Consider cross-border complexity.** For AI systems with EU-wide reach, incidents may affect multiple Member States. Establish Commission alert system awareness and coordinate with market surveillance authorities across jurisdictions where needed.

The Template is lightweight and the Guidance is operational. Unlike the 459-page AI Act or 134-page Prohibited Practices Guidelines, these documents are reference material that a compliance team can internalise in a day. The substantive challenge is not understanding the regime but building the organisational infrastructure to comply — incident detection, escalation pathways, investigation discipline, and reporting workflows.

One final observation: the Draft Guidance was in public consultation until 7 November 2025. The final version may adjust interpretive positions (particularly on property damage thresholds, fundamental rights "large scale" interpretation, and sectoral interplay details). UK firms preparing for August 2026 compliance should track the final published version and expect template Version 2.0.0 or later iterations.

---

## Sources

- [Draft Guidance Article 73 AI Act — Incident Reporting (PDF)](../../source/Serious-Incident-Reporting-Draft-Guidance-Sep-2025.pdf)
- [Incident Report Template for Serious Incidents (PDF)](../../source/Serious-Incident-Reporting-Template-Sep-2025.pdf)
- [Commission consultation page](https://digital-strategy.ec.europa.eu/en/consultations/ai-act-commission-issues-draft-guidance-and-reporting-template-serious-ai-incidents-and-seeks)
- Related reviews:
  - [EU AI Act (review 01)](01-eu-ai-act.md) — Article 73 source
  - [Commission GPAI Guidelines (review 04)](04-commission-gpai-guidelines.md) — systemic risk GPAI reporting (Article 55(1)(c))
  - [GPAI Code of Practice (review 05)](05-gpai-code-of-practice.md) — Safety Chapter Commitment 9 for systemic risk GPAI
- Cross-referenced EU sectoral regimes: CER Directive 2022/2557, NIS2 Directive 2022/2555, DORA Regulation 2025/302, MDR Regulation 2017/745, IVDR Regulation 2017/746, Cyber Resilience Act Regulation 2024/2847, Environmental Liability Directive 2004/35/EC, Environmental Crime Directive 2024/1203
- OECD AI Incidents Monitor and Common Reporting Framework
