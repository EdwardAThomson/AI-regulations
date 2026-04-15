# EU AI Act (Regulation (EU) 2024/1689) — Review

**Document:** Regulation (EU) 2024/1689 — Artificial Intelligence Act
**Published in OJ:** 12 July 2024
**Entry into force:** 1 August 2024
**Issuing bodies:** European Parliament and Council
**Length:** 459 pages (180 recitals, 113 articles across 13 chapters, 13 annexes)
**Legal basis:** Articles 16 and 114 TFEU
**EEA relevance:** Yes (extends to Iceland, Liechtenstein, Norway via EEA Agreement)

---

## Summary

The EU AI Act is the world's first comprehensive horizontal regulatory framework for artificial intelligence. It classifies AI by risk level and imposes proportionate binding obligations: prohibited practices (Article 5), high-risk systems (Chapter III with Annex III), general-purpose AI models (Chapter V), and limited transparency obligations for certain systems (Article 50). The Act applies extraterritorially — catching providers placing AI on the EU market regardless of establishment, deployers in the EU, and providers/deployers in third countries whose AI output is intended to be used in the EU. This last hook brings substantial UK-based activity into scope without any EU establishment. Application is phased: prohibitions and AI literacy from February 2025; GPAI rules from August 2025; high-risk AI system rules from August 2026; embedded-safety-component high-risk rules from August 2027. Fines reach up to 35M EUR or 7% of global annual turnover for Article 5 violations.

---

## Key Points

### Scope and Who Is Caught (Article 2)

**In scope:**
- Providers placing AI systems / GPAI models on the EU market, regardless of where established
- Deployers established or located in the EU
- **Providers and deployers in third countries whose AI system output is used in the EU** — the critical extraterritorial hook for UK firms
- Importers, distributors, product manufacturers placing AI with their product
- Authorised representatives
- Affected persons located in the EU

**Excluded:**
- Military, defence, national security (but becomes in-scope if later used for civilian/law-enforcement purposes)
- AI systems/models solely for scientific research and development
- Pre-market development and testing (except sandbox/real-world testing)
- Personal non-professional use
- Free and open-source AI (partially — still covered for prohibited practices, high-risk systems, Article 50 transparency, and GPAI)

**UK-specific reach:** UK-based organisations are caught via three routes: (1) placing AI systems or GPAI models on the EU market (e.g., API access to EU customers); (2) providing to / being used by EU-established deployers; (3) the "output-used-in-EU" test for third-country providers and deployers — this catches UK firms whose AI processes EU residents' data or produces output consumed in the EU. Non-EU providers must appoint an **EU-established authorised representative** by written mandate before placing systems on the EU market (Article 22 for AI systems; Article 54 for GPAI models).

### AI System Definition (Article 3(1))

"A machine-based system that is designed to operate with varying levels of autonomy and that may exhibit adaptiveness after deployment and that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments."

Key characteristic: the **capability to infer**, going beyond deterministic rules. Excludes systems based solely on rules defined by natural persons to automatically execute operations.

### Prohibited AI Practices (Article 5) — applied from 2 February 2025

Eight prohibitions, any of which makes an AI use unlawful:

**(a) Subliminal/manipulative/deceptive techniques** that materially distort behaviour causing or likely to cause significant harm. Intent not required. Includes techniques that subvert autonomy or free choice.

**(b) Exploitation of vulnerabilities** (age, disability, specific social/economic situation) causing or likely to cause significant harm.

**(c) Social scoring** by public or private actors leading to detrimental treatment unrelated to original data context or disproportionate to the assessed behaviour.

**(d) Predictive policing based solely on profiling or personality traits** — exception for AI supporting human risk assessment based on objective verifiable facts (e.g., fraud detection by undertakings).

**(e) Untargeted scraping** of facial images from internet or CCTV for facial recognition databases.

**(f) Emotion recognition in workplace or education** — exception for medical or safety reasons (e.g., pilot fatigue detection).

**(g) Biometric categorisation on sensitive attributes** — inferring race, political opinions, trade union membership, religion/philosophy, sex life, sexual orientation.

**(h) Real-time remote biometric identification (RBI) in publicly accessible spaces for law enforcement** — permitted only for narrowly defined purposes (victim search, imminent threat to life/terrorism, localisation of suspects of Annex II serious crimes with 4+ years custodial sentence). Requires prior judicial authorisation; 24-hour post-hoc urgency exception; FRIA; EU database registration; data protection authority notification.

### High-Risk Classification (Article 6, Annex III)

Two routes to high-risk:

**Route 1 — Article 6(1): AI as safety component or product under Union harmonisation legislation** (Annex I)
- AI system is high-risk if it is a safety component of a product (or is itself a product) covered by Annex I legislation (machinery, toys, lifts, medical devices, motor vehicles, civil aviation, etc.)
- AND that product is required to undergo third-party conformity assessment under the Annex I legislation

**Route 2 — Article 6(2): Stand-alone high-risk use cases** (Annex III). Eight categories:

1. **Biometrics** (where permitted): remote biometric identification; biometric categorisation by sensitive attributes; emotion recognition
2. **Critical infrastructure**: safety components in critical digital infrastructure, road traffic, water/gas/heating/electricity supply
3. **Education**: access/admission decisions; learning outcome evaluation; level-of-education assessment; test monitoring for prohibited behaviour
4. **Employment, workers management**: recruitment/selection; targeted job ads; application screening; decisions on promotion/termination; monitoring and evaluation
5. **Essential public and private services**: public assistance benefits eligibility; creditworthiness scoring (excludes fraud detection); life/health insurance risk assessment and pricing; emergency call evaluation and dispatch triage
6. **Law enforcement** (where permitted): victim risk assessment; polygraphs; evidence reliability; recidivism risk; profiling in investigations
7. **Migration, asylum, border control**: polygraphs; risk assessment of entrants; assisting examination of applications; detection/identification (except travel document verification)
8. **Administration of justice and democratic processes**: assisting judicial research/interpretation; influencing election/voting behaviour

**Article 6(3) derogation**: An Annex III system is NOT high-risk if it poses no significant risk AND one of the following applies: (a) narrow procedural task; (b) improving results of prior human activity; (c) detecting decision-making patterns without replacing human review; (d) preparatory task. **Crucial carve-out: profiling of natural persons is always high-risk**, regardless of derogation.

### High-Risk AI System Obligations (Chapter III, Section 2) — applied from 2 August 2026

Providers of high-risk AI systems must:

- **Risk management system** (Art. 9) — continuous iterative process; identify/estimate/evaluate risks; adopt mitigation measures; test against defined metrics
- **Data governance** (Art. 10) — training/validation/testing datasets must be relevant, representative, free of errors, with bias detection and mitigation. Special categories processing permitted only for bias correction under strict conditions
- **Technical documentation** (Art. 11, Annex IV) — comprehensive documentation before market placement; SMEs may use simplified form
- **Record-keeping / logging** (Art. 12) — automatic event logging throughout system lifetime. For remote biometric ID: period of each use, reference database, input data leading to match, verification identifications
- **Transparency / instructions for use** (Art. 13) — instructions must detail capabilities, limitations, accuracy metrics, foreseeable misuse, human oversight measures, maintenance
- **Human oversight** (Art. 14) — systems designed so natural persons can oversee effectively; understand capacities/limitations; interpret output; override/disregard; stop button or equivalent. For remote biometric ID in most cases: **no action based on identification unless verified by at least two natural persons**
- **Accuracy, robustness, cybersecurity** (Art. 15) — appropriate levels throughout lifecycle; metrics declared; resilience against data/model poisoning, adversarial examples, confidentiality attacks
- **Quality management system** (Art. 17) — documented policies/procedures covering all lifecycle aspects; proportionate to provider size
- **Documentation retention** (Art. 18) — **10 years** after market placement
- **Corrective actions** (Art. 20) — immediate action if non-conformity identified; informing operators and authorities
- **Conformity assessment** (Art. 43) — self-assessment (Annex VI internal control) for most Annex III systems; notified-body assessment (Annex VII) for biometric systems under Article 43(1)
- **EU declaration of conformity** (Art. 47, Annex V), **CE marking** (Art. 48), **EU database registration** (Art. 49)
- **Post-market monitoring** (Art. 72) — documented system analysing continuous compliance
- **Serious incident reporting** (Art. 73) — see below

Deployers of high-risk AI systems (Article 26) must:
- Take technical/organisational measures to use per instructions
- Assign competent, trained human oversight
- Ensure input data relevant and representative (where controlled)
- Monitor operation; inform providers of Article 79(1) risks
- Keep logs for at least 6 months
- **Employers must inform workers' representatives and affected workers** before deploying
- **Public authority deployers** must comply with EU database registration
- Use Article 13 information to complete **Data Protection Impact Assessment (DPIA)** under GDPR Article 35 / LED Article 27

Additional for certain Annex III deployers (public authorities, those providing public services, insurance/credit): **Fundamental Rights Impact Assessment (FRIA)** under Article 27.

### Transparency Obligations (Article 50) — applied from 2 August 2026

- **Chatbots / AI interacting with natural persons**: providers must ensure disclosure that the person is interacting with AI
- **Deepfakes** (AI-generated/manipulated image, audio, video resembling real persons/objects/events): deployers must label as artificially generated or manipulated
- **AI-generated text published for public interest matters**: deployers must label as AI-generated (with exceptions for editorially reviewed content)
- **Emotion recognition / biometric categorisation**: inform exposed natural persons
- **Synthetic content marking**: providers of AI systems generating synthetic audio/image/video/text must mark outputs as AI-generated/manipulated in a machine-readable format

Exceptions for law enforcement use; interaction with editorial review for public-interest text.

### General-Purpose AI Models (Chapter V) — applied from 2 August 2025

**GPAI model definition** (Article 3(63)): "An AI model... that displays significant generality and is capable of competently performing a wide range of distinct tasks, regardless of the way the model is placed on the market, and that can be integrated into a variety of downstream systems or applications."

**All GPAI providers (Article 53):**
- Technical documentation (Annex XI) including training methodology, data provenance, architecture, parameters, compute (FLOPs), energy consumption
- Information for downstream providers (Annex XII)
- **Policy to comply with Union copyright law**, including respecting Article 4(3) Directive (EU) 2019/790 text-and-data-mining opt-out
- **Publicly available "sufficiently detailed summary" of training data** (per AI Office template)

**Open-source exception**: Articles 53(1)(a) and (b) do NOT apply to free and open-source models with publicly available parameters. Copyright and training-data summary obligations STILL APPLY. Open-source exception does NOT APPLY to GPAI models with systemic risk.

**Systemic risk GPAI models (Article 51):** Presumed at **10^25 FLOPs** cumulative training compute. Also possible by Commission designation via Annex XIII criteria (capability benchmarks, 10,000+ EU business users reach, etc.).

**Additional obligations for systemic risk GPAI (Article 55):**
- Model evaluation using standardised protocols (including **adversarial testing / red teaming**)
- Systemic risk assessment and mitigation
- **Serious incident reporting to the AI Office without undue delay**
- Adequate cybersecurity for model and physical infrastructure

**Notification (Article 52):** Providers must notify the Commission within **2 weeks** of meeting (or expecting to meet) the systemic risk threshold. Non-EU providers must appoint an EU authorised representative by written mandate (Article 54).

**Codes of practice (Article 56):** AI Office facilitates; Commission may approve and give general validity via implementing act. Ready by 9 months post-entry-into-force (i.e., May 2025). Final GPAI Code of Practice published July 2025 (three chapters: transparency, copyright, safety/security).

### Serious Incident Reporting (Article 73) — applied from 2 August 2026

Providers of high-risk AI systems must report serious incidents to market surveillance authorities:
- **Widespread infringement or critical infrastructure disruption: within 2 days**
- **Death: within 10 days**
- **Other serious incidents: within 15 days**

"Serious incident" defined at Article 3(44): death/serious health harm; irreversible disruption of critical infrastructure; breach of fundamental rights obligations under Union law; serious property or environmental harm.

Post-reporting: investigate causes; do not alter system in ways affecting evaluation. Market surveillance authority acts within 7 days (per Regulation 2019/1020).

Draft guidance on reporting published September 2025 (consultation ended November 2025). Reporting obligations apply from August 2026.

### Innovation Support (Chapter VI)

- **AI regulatory sandboxes** (Article 57): at least one national sandbox per Member State operational by August 2026. Access free for SMEs including start-ups. Sandbox participants who observe the plan are exempt from administrative fines (Article 57(12)).
- **Real-world testing** outside sandboxes (Article 60): up to 6 months, extendable once, with market surveillance authority approval; subject registration informed consent (Article 61)
- **SME measures** (Article 62): priority sandbox access, reduced conformity assessment fees proportionate to size
- **Microenterprise derogations** (Article 63): simplified QMS compliance

### Governance (Chapter VII)

- **AI Office** — within Commission; develops expertise, supports enforcement (particularly for GPAI), encourages codes of practice
- **European Artificial Intelligence Board** — one representative per Member State; EDPS observer; coordinates national authorities; advises Commission
- **Advisory Forum** — balanced stakeholders (industry, start-ups, SMEs, civil society, academia). Permanent members: FRA, ENISA, CEN, CENELEC, ETSI
- **Scientific panel** — independent experts supporting AI Office; qualified alerts on GPAI systemic risk
- **National competent authorities** — each Member State designates at least one notifying authority and one market surveillance authority; single point of contact; adequate resources (reviewed annually)

### Enforcement and Fines (Article 99)

Fines structured by severity of infringement:

- **Up to 35M EUR or 7% of worldwide annual turnover** (whichever is higher) — for Article 5 prohibited practices violations
- **Up to 15M EUR or 3% of worldwide annual turnover** — for other obligations (provider/deployer obligations for high-risk systems, transparency, GPAI)
- **Up to 7.5M EUR or 1% of worldwide annual turnover** — for supply of incorrect or misleading information

For SMEs (including start-ups): fines calculated as the **lower** of the alternatives. Member States may adopt national rules for additional penalties (warnings, non-monetary measures) and may lay down rules on additional administrative sanctions.

Union institutions/bodies subject to fines up to 1.5M EUR (Article 100); GPAI provider fines up to 3% of annual global turnover or 15M EUR (Article 101).

### Application Timeline

| Date | Provisions applied |
|------|-------------------|
| 1 August 2024 | Regulation enters into force |
| 2 February 2025 | Prohibited practices (Art. 5), AI literacy (Art. 4), definitions |
| 2 August 2025 | GPAI rules (Chapter V); codes of practice ready; national competent authorities designated; penalty regime |
| 2 August 2026 | High-risk AI system rules (most Article 6(2) systems); Article 50 transparency; Article 73 serious incident reporting; enforcement |
| 2 August 2027 | Article 6(1) high-risk rules on embedded safety components |
| By end 2030 | Public authority deployers using existing systems must comply |

### Annexes

- **Annex I** — 20 pieces of Union harmonisation legislation (machinery, medical devices, motor vehicles, etc.) triggering product-based high-risk classification
- **Annex II** — 16 categories of criminal offences (terrorism, trafficking, serious crimes) for the RBI exception
- **Annex III** — 8 high-risk use case categories detailed above
- **Annex IV** — Technical documentation structure (9 sections) for high-risk AI systems
- **Annex V** — EU declaration of conformity
- **Annex VI** — Internal control conformity assessment (self-assessment)
- **Annex VII** — QMS-based conformity assessment (notified body)
- **Annex VIII** — EU database registration fields (3 sections: provider, not-high-risk claim, deployer)
- **Annex IX** — Real-world testing registration
- **Annex X** — Union large-scale IT systems (Schengen, VIS, Eurodac, ETIAS, ECRIS-TCN)
- **Annex XI** — GPAI provider technical documentation (all GPAI + systemic risk additions)
- **Annex XII** — Downstream provider information for GPAI integration
- **Annex XIII** — Criteria for systemic risk designation (parameters, dataset size, compute FLOPs, modalities, benchmarks, 10,000+ registered EU business users, end-user numbers)

---

## Observations

### Clarity

The EU AI Act is the most ambitious horizontal AI regulation attempted anywhere. Its clarity virtues are substantial:

- **Risk-based architecture** — prohibited / high-risk / limited risk / minimal risk provides a coherent organising framework
- **Definitional thoroughness** — 68 definitions in Article 3 provide a shared vocabulary that the rest of the Act can build on
- **Operationalisation via annexes** — the high-risk list (Annex III), documentation requirements (Annex IV), and GPAI technical documentation (Annex XI) are concrete and usable
- **Separation of provider and deployer obligations** — responsibilities follow the supply chain roles rather than lumping everything on "AI users"

The Act's clarity weaknesses:

- **Cross-reference density** — provisions frequently cross-reference other provisions, other Union law, annexes, and forthcoming implementing acts. Navigating a single compliance question typically requires consulting 5-10 cross-referenced elements
- **"Significant" undefined** — the threshold for "significant harm" (Article 5), "significant risk" (Article 6(3)), "significant generality" (Article 3(63)), "significant adverse effect" (Article 86) is left to interpretation
- **Article 6(3) derogation ambiguity** — the four carve-out conditions for non-high-risk Annex III systems are short statements that will generate substantial interpretive litigation
- **Article 50 transparency scope** — what counts as "interacting with an AI system," what constitutes "deepfake," and when editorial review exempts public-interest text all require clarification beyond the Act's text

These weaknesses are substantially addressed by the Commission guidelines (Article 3 AI system definition, February 2025; Article 5 prohibited practices, February 2025; GPAI guidelines, July 2025; serious incident reporting, September 2025) and the codes of practice (GPAI Code of Practice, July 2025; Transparency Code in development). The Act is not a self-contained compliance document; it operates alongside a growing body of secondary guidance.

### Measurability

The Act is remarkable for the specificity of its penalty structure (7%/3%/1% of global turnover, or 35M/15M/7.5M EUR) and the clarity of its application timeline. These elements are measurable.

The core compliance obligations are less measurable in outcome terms:

- **Risk management** (Art. 9): "continuous iterative process" without specific metrics
- **Data governance** (Art. 10): "relevant, sufficiently representative, to the best extent possible free of errors" — quality thresholds not specified
- **Accuracy/robustness/cybersecurity** (Art. 15): "appropriate levels" — appropriate by whose standard?
- **Human oversight** (Art. 14): design requirements but no quantitative thresholds for effectiveness

The Act delegates detailed metrics to **harmonised standards** (developed by CEN/CENELEC/ETSI following Commission request). Compliance with a harmonised standard provides **presumption of conformity**. This is a standard approach in EU product safety law and is the mechanism through which the Act's abstract obligations become testable.

The Act also delegates to **codes of practice** for GPAI (Chapter V). The July 2025 GPAI Code of Practice provides compliance routes for Article 53 (all GPAI) and Article 55 (systemic risk GPAI) obligations. Providers can follow the Code or demonstrate alternative adequate means for Commission approval.

### Gaps

**Labour market impact treated lightly.** Workers feature in Article 26(7) (deployers-as-employers must inform workers' representatives) and in Annex III point 4 (employment AI is high-risk). But the Act does not address labour market transformation, mass displacement, or sector-specific AI-workplace governance. The Platform Work Directive operates in parallel for gig economy; the Act does not integrate with it substantively.

**Environmental impact narrow.** Annex XI requires GPAI providers to document "known or estimated energy consumption." Article 40 references sustainability as a factor in standards development. But there are no operational limits on AI energy consumption, no disclosure obligations to end users or downstream providers about the environmental cost of specific inference operations, and no incentives for energy-efficient AI.

**Agentic AI / autonomous systems underdeveloped.** The Act's definitions and categories anticipate fixed-purpose AI systems. Autonomous AI agents that dynamically compose tools, execute multi-step plans, and interact with real-world systems fit uneasily into the framework. Systemic risk designation under Article 51 could catch some agent deployments, but the Act's risk categorisation (Annex III) does not explicitly address agentic use cases.

**Copyright enforcement unresolved.** Article 53(1)(c) requires GPAI providers to implement copyright compliance policies, including Article 4(3) DSM Directive opt-out respect. But the Act does not create a copyright enforcement mechanism — rights holders must rely on existing national copyright law. The training data summary (Article 53(1)(d)) may help rights holders identify infringement but imposes no takedown obligation.

**Downstream integration uncertainties.** Article 25 creates provider liability when a downstream actor makes "substantial modification" to a high-risk system or modifies the intended purpose of a GPAI system so it becomes high-risk. But the threshold for "substantial modification" and the practical implications for integrators of third-party foundation models will generate substantial litigation. The value chain documentation sharing requirements (Article 25(4)) help but do not eliminate ambiguity.

**Real-world testing framework narrow.** Article 60 permits real-world testing outside sandboxes only for Annex III high-risk systems (not for Annex I product-related high-risk). The 6-month limit (extendable once) may be inadequate for long-running deployments. Consent requirements (Article 61) may be impractical at scale.

**Public sector scope partial.** The Act catches public sector deployers of Annex III systems and imposes additional registration and FRIA obligations. But internal-use public sector AI (e.g., tax fraud detection, benefit fraud) may fall in scope while internal-use private sector AI at similar scale may not. The distinction between "public authority" and "private actor providing public services" is operationally complex.

**Lack of explicit AI worker protection.** The Act does not provide workers with specific AI-related rights (right to human review of algorithmic decisions at work, right to object to AI-driven performance monitoring, etc.) beyond what GDPR already provides. The UK has moved further on this with its Future of Work unit (January 2026); the EU Act treats AI-at-work as a subset of high-risk AI.

### Feasibility

The Act's feasibility varies sharply across provisions:

**Highly feasible:**
- **Prohibitions (Article 5)** — clear boundaries; enforcement via existing market surveillance authorities
- **Transparency obligations (Article 50)** — chatbot disclosure, deepfake labelling are operationally straightforward
- **EU database registration** — technically simple; Commission operates the database
- **CE marking and declaration of conformity** — leverages existing NLF infrastructure

**Feasibility with significant effort:**
- **High-risk compliance** — requires substantial documentation, testing, and governance effort, but follows established NLF patterns
- **GPAI documentation** — Annex XI requires significant transparency that providers may resist, but the July 2025 Code of Practice provides a route
- **Risk management / data governance** — resource-intensive, especially for SMEs
- **Serious incident reporting** — new infrastructure required; September 2025 draft guidance helps

**Feasibility questions:**
- **Systemic risk GPAI obligations (Article 55)** — "state of the art" adversarial testing at the frontier model scale requires capabilities few organisations have
- **Cross-border enforcement** — market surveillance authorities need to coordinate on global providers; the AI Office's coordination role is central but unproven
- **Extraterritorial enforcement against UK/US/China providers** — mechanisms exist (authorised representative, fines against EU-available products) but practical enforcement depends on provider cooperation and willingness of home states to enforce
- **Harmonised standards timeline** — CEN/CENELEC/ETSI developing AI standards take years; gap between Act application and standards availability creates compliance uncertainty

**Resource constraints for SMEs** are partially addressed (simplified technical documentation, reduced conformity assessment fees, sandbox priority access, microenterprise derogations). But SMEs deploying high-risk AI still face substantial compliance cost.

### Internal Consistency

The Act is largely internally consistent. Three notable tensions:

**Risk-based approach vs. entity-based approach for GPAI.** The core Act classifies AI by use case (prohibited, high-risk, limited, minimal). Chapter V instead regulates GPAI models by entity (the model developer) regardless of use case. This dual approach reflects the different regulatory problems (systemic risk from general-purpose capabilities cannot be addressed use-case-by-use-case) but creates parallel obligations for firms that develop GPAI models and integrate them into high-risk systems.

**Context-specific derogation vs. universal profiling classification.** Article 6(3) allows Annex III systems to be classified as non-high-risk if they meet one of four narrow conditions. But Article 6(3) final paragraph excludes any profiling of natural persons from the derogation. The result: a narrow procedural task performing profiling is always high-risk regardless of actual harm potential. This is defensible but creates the paradox that AI performing no profiling may escape high-risk classification while AI performing trivial profiling does not.

**Open-source exception complexity.** The open-source exception varies across the Act: some provisions fully exempt open source (market access for non-high-risk use); others (prohibited practices, high-risk systems, Article 50 transparency, GPAI obligations for copyright and training summary) apply regardless; GPAI systemic risk obligations apply to open-source models meeting the systemic risk threshold. The resulting compliance picture for open-source AI is complex and may discourage compliant open-source activity.

### Coverage

Coverage is comprehensive within the Act's chosen scope:

- **Actor types** — providers, deployers, importers, distributors, product manufacturers, authorised representatives, affected persons all addressed
- **Risk levels** — prohibited / high-risk / limited / minimal all covered
- **Model vs. system distinction** — GPAI models regulated separately from AI systems
- **Lifecycle** — pre-market (risk management, data, documentation, conformity assessment), market entry (declaration of conformity, CE marking, registration), deployment (oversight, monitoring, transparency), post-market (monitoring, serious incident reporting, corrective action), end-of-life (data retention obligations)
- **Enforcement** — market surveillance, cross-border cooperation, scientific panel, fines, complaint mechanisms, whistleblower protection

Out-of-scope areas (acknowledged): military/defence/national security, pure R&D, personal non-professional use. These are appropriate exclusions.

Areas the Act does not comprehensively address (discussed as gaps above): labour market impact, environmental impact, agentic AI specifics, copyright enforcement, public-private distinction.

### International Alignment

The EU AI Act is the global benchmark that other jurisdictions position against:

- **UK**: explicitly rejects the Act's horizontal regulatory approach in favour of context-specific, sector-regulator-led governance. UK's Data (Use and Access) Act 2025 relaxes Article 22 UK GDPR restrictions on solely automated decisions, moving in the opposite direction to the Act's strengthening of oversight
- **USA**: no comprehensive federal AI law; state-level regulation (Colorado AI Act) partially resembles the Act's risk-based approach. Biden's EO 14110 (revoked Jan 2025) was closer to the Act; Trump administration's approach is deliberately divergent
- **China**: sector-specific generative AI regulation (Interim Measures August 2023); broader digital governance under CAC. Different values framework, overlapping compliance surface
- **Brazil**: AI Bill (Bill 2338/2023) in legislative process at time of this review; influenced by the EU Act
- **Singapore**: voluntary governance frameworks layered over time; complementary to rather than competing with the Act

The Act has also influenced international standards through ISO/IEC 42001 (AI management systems) and related standards. The Council of Europe Framework Convention on AI (Vilnius 2024) operates in parallel — the EU is a signatory but the Convention is broader (human rights, democracy, rule of law) and weaker (framework) than the Act.

**UK-EU regulatory gap.** As of April 2026, the UK-EU gap is both framing (UK pro-innovation vs EU risk-based) and now enacted (DUAA 2025 relaxes what the EU AI Act strengthens). UK firms operating across both jurisdictions face divergent compliance regimes. The "Brussels effect" (firms applying EU standards globally) may narrow the practical divergence, but legal divergence is real.

---

## Overall Assessment

The EU AI Act is a legislative achievement of remarkable scope and ambition. As the world's first comprehensive horizontal AI regulation, it has set the global benchmark — other jurisdictions will be judged by whether they match, diverge from, or reject its approach. Its risk-based architecture, detailed obligations for high-risk systems, separate GPAI regime, and meaningful penalty structure create a regulatory framework that is both principled and operational.

Its greatest strength is structural coherence. The five-way risk classification (prohibited / high-risk / GPAI / limited / minimal), the provider/deployer/importer/distributor obligation architecture, and the interaction with existing Union product safety law through the New Legislative Framework produce a regulatory system that integrates with other EU law rather than sitting awkwardly alongside it. The extensive definitions (Article 3), detailed annexes, and delegation of technical specifications to harmonised standards make the Act adaptable without requiring constant legislative amendment.

Its greatest weakness is implementation dependency. The Act sets abstract obligations that require substantial secondary legislation, guidelines, codes of practice, and harmonised standards to operationalise. The Commission's parallel rollout of GPAI Guidelines (July 2025), GPAI Code of Practice (July 2025), serious incident reporting guidance (September 2025), AI-generated content transparency code (draft December 2025), and Article 5 and Article 3 guidelines (February 2025) demonstrates both the complexity of the operationalisation task and the speed at which it is being addressed. Firms face a genuinely moving compliance target until the secondary framework stabilises around 2026-2027.

For UK-based firms serving EU clients — the user's focus — the Act's practical implications are substantial. Any UK firm providing AI systems or GPAI models to EU customers is subject to the Act, regardless of UK establishment. The extraterritorial "output-used-in-EU" hook catches UK deployers whose AI produces output consumed in the EU. UK firms must:

1. **Determine their role** — provider, deployer, importer, distributor, or authorised representative. This shapes all subsequent obligations
2. **Classify their AI systems** — prohibited, high-risk (Annex I or Annex III), limited risk (Article 50), minimal risk, or GPAI model. Classification determines the compliance burden
3. **Appoint an EU authorised representative** if acting as a provider without EU establishment
4. **Prepare technical documentation** to Annex IV or Annex XI standard, as applicable
5. **Implement risk management, data governance, human oversight**, and other high-risk obligations
6. **Plan for phased timeline**: prohibitions (already in force), GPAI rules (in force), high-risk rules (August 2026), embedded safety components (August 2027)
7. **Monitor guidance and codes of practice** as they evolve
8. **Coordinate with UK compliance** (Data Protection Act, DUAA 2025, Equality Act, sector regulators) which is diverging from EU direction

The gap between UK and EU AI governance is now enacted rather than just framed. UK firms have two choices: (a) adopt EU Act compliance as the universal standard (the Brussels effect approach), accepting constraints the UK regulatory regime does not impose, or (b) maintain dual compliance regimes. For firms with material EU customer bases, option (a) is often the simpler engineering choice, even if it subjects UK operations to EU-origin constraints.

The Act's fundamental question — can comprehensive horizontal AI regulation work? — will be tested over the next 5-10 years. The application timeline extends to 2027-2030. Enforcement patterns will emerge. Harmonised standards will develop. The next iteration of the Act (Commission review due 2029, then every 4 years) will incorporate lessons learned. For UK-based practitioners and firms, the Act is a fixed feature of the European AI landscape to which adaptation is now required.

---

## Sources

- [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj) — official OJ text
- [EU AI Act portal (artificialintelligenceact.eu)](https://artificialintelligenceact.eu/) — unofficial but authoritative navigational aid
- [Shaping Europe's digital future — AI Act](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) — Commission landing page
- Associated reviews in this repo:
  - [Guidelines on the Definition of an AI System (Feb 2025)](../../source/Guidelines-Definition-AI-System-Feb-2025.pdf) — Article 3 scope
  - [Guidelines on Prohibited AI Practices (Feb 2025)](../../source/Guidelines-Prohibited-AI-Practices-Feb-2025.pdf) — Article 5
  - [Commission GPAI Guidelines (Jul 2025)](../../source/Commission-GPAI-Guidelines-Jul-2025.pdf) — Chapter V scope
  - [GPAI Code of Practice (Jul 2025)](../../source/) — three chapters (transparency, copyright, safety/security)
  - [Serious Incident Reporting Guidance (Sep 2025)](../../source/Serious-Incident-Reporting-Draft-Guidance-Sep-2025.pdf) — Article 73
  - [Transparency Code for AI-Generated Content (Draft, Dec 2025)](../../source/Transparency-Code-AI-Generated-Content-Draft1-Dec-2025.pdf) — Article 50
