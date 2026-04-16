# Ethics Guidelines for Trustworthy AI (HLEG, 2019) — Review

**Document:** Ethics Guidelines for Trustworthy AI
**Published:** 8 April 2019 (first draft 18 December 2018; revised following consultation with 500+ contributors)
**Issuing body:** High-Level Expert Group on Artificial Intelligence (AI HLEG), independent expert group set up by the European Commission in June 2018
**Legal status:** Non-binding guidelines; voluntary framework
**Length:** 41 pages (plus 3-page member/contributor list)
**Authors:** 52 expert members across industry, academia, civil society; Chair Pekka Ala-Pietilä (AI Finland, Huhtamaki, Sanoma); Vice-Chair Barry O'Sullivan (University College Cork); 9 Co-Rapporteurs including Virginia Dignum, Luciano Floridi, Thomas Metzinger, Francesca Rossi, Karen Yeung

**Relationship to AI Act:** The HLEG's seven requirements and four ethical principles directly influenced the AI Act's risk-based framework and high-risk obligations. Many concepts (human oversight, technical robustness, transparency, data governance, accountability) appear verbatim or near-verbatim as Chapter III Section 2 requirements in Regulation 2024/1689. The Guidelines pre-date the AI Act by five years and represent the intellectual foundation of EU AI regulation.

---

## Summary

The Guidelines establish the "Trustworthy AI" framework that shaped all subsequent EU AI policy. Trustworthy AI has three components — **lawful, ethical, and robust** — each necessary but not sufficient. The Guidelines focus on the second and third (ethical and robust), explicitly noting that lawful AI is addressed through existing EU law. Chapter I grounds ethics in fundamental rights (EU Charter) and distils four ethical principles: **respect for human autonomy, prevention of harm, fairness, and explicability**. Chapter II operationalises these principles into seven requirements: **(1) human agency and oversight, (2) technical robustness and safety, (3) privacy and data governance, (4) transparency, (5) diversity/non-discrimination/fairness, (6) societal and environmental well-being, (7) accountability**. Chapter III provides a pilot assessment list with concrete questions for each requirement. A final section identifies beneficial opportunities (climate, health, education) and critical concerns (biometric identification, covert AI, citizen scoring, lethal autonomous weapons). The Guidelines are voluntary, non-binding, and written as a "living document" — but they established the vocabulary and conceptual architecture that the EU AI Act later made legally binding.

---

## Key Points

### The Three Components of Trustworthy AI

1. **Lawful AI** — complies with all applicable laws and regulations (EU primary and secondary law, UN human rights treaties, Council of Europe conventions, Member State laws)
2. **Ethical AI** — adheres to ethical principles and values, even where these go beyond legal requirements
3. **Robust AI** — technically reliable and socially aware; prevents unintentional harm

Each component is necessary but not sufficient. Tensions between them (e.g., when law lags ethical norms) require alignment efforts.

### Chapter I — Foundations: Four Ethical Principles

Grounded in fundamental rights enshrined in the EU Charter. The Guidelines identify five families of fundamental rights as particularly relevant to AI:

- Respect for human dignity
- Freedom of the individual
- Respect for democracy, justice and the rule of law
- Equality, non-discrimination and solidarity — including rights of persons at risk of exclusion
- Citizens' rights

From these, four ethical principles are derived:

1. **Respect for human autonomy** — humans must keep full self-determination; AI should augment not subordinate humans; human oversight over work processes
2. **Prevention of harm** — AI must not cause or exacerbate harm; special attention to vulnerable persons and asymmetries of power (employer-worker, business-consumer, government-citizen); includes consideration for natural environment and living beings
3. **Fairness** — substantive (equal distribution of benefits/costs, freedom from bias) and procedural (ability to contest and seek redress); entity accountable for decisions must be identifiable
4. **Explicability** — processes transparent, capabilities openly communicated, decisions explainable; for "black box" systems, traceability and auditability may substitute direct explanation

**Tensions between principles**: The Guidelines acknowledge fixed solutions don't exist. Example given: predictive policing where prevention of harm (reducing crime) conflicts with human autonomy (individual liberty, privacy). Certain fundamental rights (e.g., human dignity) are absolute and cannot be subject to balancing.

### Chapter II — Seven Requirements for Trustworthy AI

#### 1. Human agency and oversight

- **Fundamental rights impact assessment** before development where risks exist
- **Human agency**: users must be able to self-assess or challenge the system; right not to be subject to solely automated decisions with legal or similarly significant effects (GDPR Article 22 reference)
- **Human oversight**: three governance models:
  - **Human-in-the-loop (HITL)** — intervention in every decision cycle
  - **Human-on-the-loop (HOTL)** — intervention during design cycle + monitoring operation
  - **Human-in-command (HIC)** — oversee overall activity, decide when/how to use the system
- Less oversight → more testing and stricter governance required

#### 2. Technical robustness and safety

- **Resilience to attack and security**: protection against data poisoning, model leakage, infrastructure attacks; dual-use consideration
- **Fallback plan and general safety**: switch from statistical to rule-based; ask human operator; level of safety measures proportionate to risk magnitude
- **Accuracy**: measured and assured; indicate likelihood of errors; especially crucial where AI directly affects human lives
- **Reliability and reproducibility**: same behaviour under same conditions; replication files; verification methods

#### 3. Privacy and data governance

- Privacy/data protection throughout lifecycle — including information generated about the user over interaction
- Quality and integrity of data — address socially constructed biases, inaccuracies; malicious data changes behaviour
- Access to data protocols — qualified personnel only, with oversight mechanism logging when/where/how/by whom data accessed

#### 4. Transparency

- **Traceability** — document data sets, processes, data gathering/labelling methods
- **Explainability** — technical explainability + human decision explainability; trade-off acknowledged between accuracy and explainability
- **Communication** — AI must not represent itself as human; option for human interaction where needed; capabilities and limitations communicated

#### 5. Diversity, non-discrimination and fairness

- Avoidance of unfair bias — in training data, in algorithm design
- Accessibility and universal design — EN 301 549, UN Convention on Rights of Persons with Disabilities referenced
- Stakeholder participation — consultation throughout lifecycle; worker consultation and participation

#### 6. Societal and environmental well-being

- Sustainable and environmentally friendly AI — critical examination of resource usage and energy consumption during training
- Social impact — effects of ubiquitous social AI on social agency, relationships, attachment
- Society and democracy — impact on institutions, democratic processes, electoral contexts

#### 7. Accountability

- **Auditability** — enablement of algorithm/data/design process assessment; for fundamental-rights applications, independent audit
- **Minimisation and reporting of negative impacts** — whistleblower protection; algorithmic impact assessments proportionate to risk
- **Trade-offs** — rational, methodological, documented; if no ethically acceptable trade-off exists, development should not proceed
- **Redress** — accessible mechanisms when unjust adverse impact occurs

### Chapter II — Technical and Non-Technical Methods

**Technical methods:**
- Architectures for Trustworthy AI ("white list" rules, "black list" restrictions)
- Ethics and rule of law by design (X-by-design; privacy-by-design, security-by-design)
- Explanation methods (XAI research)
- Testing and validating (red teams, bug bounties)
- Quality of Service indicators

**Non-technical methods:**
- Regulation
- Codes of conduct
- Standardisation (ISO, IEEE P7000 series, possible future "Trustworthy AI" label)
- Certification
- Accountability via governance frameworks (ethics officers, internal/external boards)
- Education and awareness (AI literacy across society)
- Stakeholder participation and social dialogue
- Diversity and inclusive design teams

### Chapter III — Pilot Assessment List

A non-exhaustive, use-case-adaptable assessment list organised by the seven requirements. Sample questions include:

- **Human agency**: Did you carry out a fundamental rights impact assessment? Can users detect they are interacting with AI? Is there a stop button or safe-abort procedure?
- **Technical robustness**: Vulnerability to data pollution, cyber-attacks? Fallback plan tested? Accuracy measured? Reproducibility verified?
- **Privacy**: Mechanism for flagging data protection issues? Minimisation of personal data use? DPO involved early?
- **Transparency**: Documentation of design method, training method, test scenarios, outcomes? Simplest interpretable model used?
- **Diversity**: Strategy to avoid unfair bias? Definition of fairness applied? Accessibility for users with disabilities?
- **Societal well-being**: Environmental impact measured? Social impacts assessed (job loss, de-skilling)?
- **Accountability**: Independent audit for fundamental-rights applications? Ethical AI review board? Redress mechanisms?

**Governance structure** for assessment list implementation:
- Management/Board — escalation and approval
- Compliance/Legal — monitors assessment list evolution
- Product/Service Development — uses list to evaluate products
- Quality Assurance — checks results, escalates if unsatisfactory
- HR — training and diversity
- Procurement — includes Trustworthy AI check in procurement
- Day-to-day Operations — developers/project managers document results

### Beneficial Opportunities (Section C)

- **Climate action and sustainable infrastructure** — intelligent transport, energy efficiency, reducing environmental footprint
- **Health and well-being** — smarter treatment, preventive care, elderly care support
- **Quality education and digital transformation** — forecasting skill needs, personalised education

### Critical Concerns (Section C)

Four specific concerns flagged:

1. **Identifying and tracking individuals with AI** — face recognition, biometric identification; proportionate use required; distinction between targeted and mass surveillance; meaningful consent mechanisms needed
2. **Covert AI systems** — humans must know they are interacting with AI or a machine; human-like robots require careful ethical assessment
3. **AI-enabled citizen scoring in violation of fundamental rights** — normative citizen scoring ("moral personality"/"ethical integrity") endangers autonomy and non-discrimination; opt-out where possible; transparency does not cure the problem
4. **Lethal autonomous weapons systems (LAWS)** — raises fundamental ethical concerns; European Parliament resolution 2018/2752(RSP) referenced

These four concerns became direct precursors to the AI Act's prohibited practices (Article 5) — particularly social scoring (5(1)(c)), real-time biometric identification (5(1)(h)), and emotion recognition (5(1)(f)).

### Potential Longer-Term Concerns

Briefly noted as hypothetical: Artificial General Intelligence, Artificial Consciousness, Artificial Moral Agents, Super-intelligence, Transformative AI. Presented with caveat that "many others believe these to be unrealistic." These later surfaced in the GPAI Code of Practice's specified systemic risks (Loss of Control) and in broader AI safety discourse.

### Definition of AI System (Glossary)

"Artificial intelligence (AI) systems are software (and possibly also hardware) systems designed by humans that, given a complex goal, act in the physical or digital dimension by perceiving their environment through data acquisition, interpreting the collected structured or unstructured data, reasoning on the knowledge, or processing the information, derived from this data and deciding the best action(s) to take to achieve the given goal. AI systems can either use symbolic rules or learn a numeric model, and they can also adapt their behaviour by analysing how the environment is affected by their previous actions."

This definition sits alongside a separate HLEG document "A definition of AI: Main capabilities and scientific disciplines." It is narrower and more descriptive than the AI Act's later Article 3(1) definition, but the conceptual emphasis on autonomy, data-driven operation, and adaptive behaviour is carried forward.

---

## Observations

### Clarity

The Guidelines are well-structured with three layers of abstraction (principles → requirements → assessment list). Each layer builds on the previous. Chapter III's pilot assessment list gives implementers concrete questions. Clarity strengths:

- The **three components** (lawful/ethical/robust) provide a simple mnemonic that later appears in industry compliance frameworks
- The **four principles** (autonomy, harm prevention, fairness, explicability) are principled yet operationalisable
- The **seven requirements** decompose ethical abstraction into concrete design criteria
- The **three human oversight models** (HITL/HOTL/HIC) give designers a governance vocabulary

Clarity weaknesses:

- "Ethics" is defined but operationalisation remains contextual — the Guidelines acknowledge reliance on practitioner judgment
- The assessment list uses open-ended "Did you...?" questions without pass/fail thresholds
- The distinction between "ethical" and "lawful" is stated but the Guidelines never address what to do when law and ethics conflict (only note the tension)

### Measurability

Very limited. The Guidelines are principle-based and do not prescribe metrics. Where measurability appears, it is aspirational:

- "Assess the level and definition of accuracy required"
- "Measure the environmental impact of the AI system's development"
- "Measurement or assessment mechanism of the potential impact" of variability on fundamental rights
- "Quantitative analysis or metrics to measure and test the applied definition of fairness"

No thresholds, no scoring rubric, no benchmark comparison. The assessment list is self-assessment; no external validation required. This reflects the Guidelines' 2019 vintage and their positioning as a non-binding framework. Later EU instruments (the AI Act, the GPAI Code of Practice, the Transparency Code) introduce specific measurable obligations.

### Gaps

**No legal obligations.** The Guidelines are explicitly voluntary. The HLEG positioned them as a "living document" to be revised through stakeholder piloting (revision due early 2020). They do not create rights or obligations.

**GPAI and foundation models.** Written before the 2022-2023 emergence of large foundation models, the Guidelines do not address GPAI-specific challenges: emergent capabilities, systemic risks, downstream deployment chains, compute-based classification. The AI Act's GPAI chapter (published 2024) fills this gap.

**Specific risk categories.** The Guidelines do not establish prohibited practices or high-risk classifications. Later Commission Guidelines on Prohibited AI Practices (July 2025) and the AI Act's Annex III develop this.

**Sectoral application.** The Guidelines acknowledge context-specificity ("AI music recommendation systems do not raise the same ethical concerns as AI systems proposing critical medical treatments") but do not provide sectoral guidance. Sectoral frameworks (Medical Device Regulation, Machinery Regulation, automotive regulation) remain separate.

**Enforcement and redress.** The Guidelines mention redress but do not specify enforcement architecture. No regulator is identified; no notification requirements; no penalties. These are later introduced by the AI Act (Articles 63–85 national competent authorities; 99–101 penalties).

**Systemic risk.** The document mentions "Potential longer-term concerns" only briefly and with skepticism. The AI Act and GPAI Code of Practice later elevate systemic risk to a distinct regulatory category for 10^25 FLOP models.

**Environmental impact.** Acknowledged in Requirement 6 but without metrics, benchmarks, or specific obligations. Recent Commission GPAI Guidelines and GPAI Code of Practice include some documentation obligations for training energy consumption, but these remain limited.

### Feasibility

For implementers, the Guidelines are feasible to adopt as an ethical framework but offer limited action-specific guidance. The assessment list is feasible as a self-reflection tool but requires substantial internal judgment. Organisations with existing ethics or compliance functions can incorporate the list. Smaller organisations without such functions would find the list hard to operationalise without external guidance.

The Guidelines' feasibility depends on:

1. Organisational commitment — the Guidelines repeatedly emphasise management attention at the highest level
2. Technical capability — X-by-design, XAI research, red teaming require specialised expertise
3. Stakeholder engagement — worker consultation, civil society input, user feedback loops
4. Documentation infrastructure — traceability, auditability, logging
5. Governance structures — ethics officers, review boards, escalation mechanisms

Where these prerequisites exist, the Guidelines are usable. Where they don't, the Guidelines effectively require their creation before implementation.

### Internal Consistency

The Guidelines are internally consistent. The four principles map cleanly onto the seven requirements:

- Human autonomy → Requirements 1 (human agency/oversight)
- Prevention of harm → Requirements 2 (robustness/safety), 3 (privacy), 6 (societal/environmental well-being)
- Fairness → Requirements 5 (diversity/non-discrimination/fairness), 7 (accountability)
- Explicability → Requirement 4 (transparency)

Each requirement has sub-dimensions that are internally consistent. The assessment list questions trace back to the requirements.

One tension: the Guidelines emphasise voluntariness and non-binding character yet aspire to shape "Trustworthy AI for Europe" as a horizontal framework. The tension between voluntariness and binding force is resolved — in favour of binding force — by the AI Act five years later.

### Coverage

Broad horizontal coverage across AI lifecycle (development, deployment, use) and across stakeholder roles (developers, deployers, end-users, broader society). Vertical (sectoral) coverage is limited. Application-specific coverage is limited.

The Guidelines cover:
- AI system definition
- Fundamental rights basis
- Ethical principles
- Requirements with concrete sub-dimensions
- Technical and non-technical implementation methods
- Assessment list
- Governance structure
- Opportunities and critical concerns

The Guidelines do not cover:
- Regulatory enforcement
- Legal liability
- Criminal law
- Sectoral specifics (beyond examples)
- Cross-border enforcement
- Third-country operators

### International Alignment

The Guidelines were produced in parallel with and influenced several international frameworks:

- **OECD AI Principles** (May 2019) — five complementary values-based principles; published one month after the HLEG Guidelines; considerable overlap
- **G20 AI Principles** (June 2019) — building on OECD work
- **UNESCO Recommendation on AI Ethics** (2021) — broader global scope but similar principle structure
- **Council of Europe Framework Convention on AI** (2024) — legally binding treaty; overlaps with HLEG's fundamental-rights foundation

For UK firms, the Guidelines are:

- **Aligned conceptually** with the UK's AI White Paper (March 2023) five cross-sectoral principles (safety/security/robustness, transparency/explainability, fairness, accountability/governance, contestability/redress), though the UK approach is lighter-touch and regulator-led
- **Influential on sector regulators** — ICO, FCA, MHRA have all drawn on HLEG concepts in their AI guidance
- **Precursor to EU AI Act obligations** that UK firms operating in the EU must meet

### Historical Significance

The Guidelines are historically important as the intellectual foundation of EU AI regulation. They:

1. Established "Trustworthy AI" as the EU's foundational concept — now central to the AI Act Recitals
2. Identified the seven requirements that became the AI Act's high-risk obligations
3. Identified the critical concerns that became the AI Act's prohibited practices
4. Anchored AI ethics in fundamental rights (EU Charter)
5. Shaped global discourse (OECD, G20, UNESCO)
6. Preceded and informed the Commission's 2021 AI Act proposal
7. Established the multi-stakeholder, consultation-driven process model that later EU AI governance follows (e.g., the Code of Practice for GPAI, the Transparency Code)

The HLEG was subsequently replaced by the AI Office and formal regulatory structures, but the HLEG framework continues to shape policy.

---

## Overall Assessment

The Ethics Guidelines for Trustworthy AI are a **historical and conceptual cornerstone** of EU AI regulation. Read today (2026), they function as a roadmap that subsequent binding instruments have filled in. The four principles, seven requirements, and concern categories are directly embedded in the AI Act. The Guidelines' limitations — voluntariness, lack of enforcement, absence of sectoral specificity, no GPAI treatment — have been addressed by the AI Act, Commission Guidelines, and Codes of Practice.

For UK-based firms approaching EU operations, the Guidelines serve three purposes:

1. **Interpretive guide to the AI Act.** The AI Act's Recitals reference "trustworthy AI" and the HLEG framework. Understanding the Guidelines helps interpret why specific AI Act provisions exist and what they are meant to achieve.

2. **Self-assessment foundation.** The Chapter III assessment list remains useful as an internal governance tool. Organisations that can answer its questions credibly are likely compliant with the AI Act's high-risk requirements. The list predates the AI Act's Article 17 quality management system, Article 14 human oversight, and Article 13 transparency provisions, but aligns with them.

3. **Cross-jurisdictional vocabulary.** The "Trustworthy AI" framing is now international. UK firms, US operations, and cross-border AI governance frameworks use this vocabulary. Familiarity with the HLEG Guidelines is cultural literacy for EU AI compliance.

The Guidelines' greatest strength is **conceptual clarity**: they take abstract ethical philosophy and distil it into seven operationalisable requirements. Their greatest weakness is **lack of enforcement teeth**: they are voluntary guidance, not law. The AI Act has corrected this weakness; but the framework's voluntary origin means many EU firms adopted trustworthy AI principles long before the AI Act made them binding — creating a head-start for firms that took the Guidelines seriously.

For practical compliance work today, the Guidelines are background reading rather than operational instruction. Operational compliance now flows from:

- **EU AI Act** (Regulation 2024/1689) — binding obligations
- **Commission Guidelines** on AI system definition, prohibited practices, GPAI scope — interpretation
- **GPAI Code of Practice** (July 2025) — voluntary but Commission-endorsed compliance route
- **Serious Incident Reporting Guidance** (September 2025) — Article 73 operationalisation
- **Transparency Code** (December 2025 draft) — Article 50 operationalisation

The HLEG Guidelines provide the **why** behind all of these. For UK firms providing AI services to EU users, treating the Guidelines as a compliance companion (not a compliance framework) is the right posture: they explain the purpose and underlying values that the binding instruments enforce.

---

## Sources

- [Ethics Guidelines for Trustworthy AI (PDF)](../../source/Ethics-Guidelines-Trustworthy-AI-2019.pdf)
- [European Commission page on the HLEG Ethics Guidelines](https://digital-strategy.ec.europa.eu/en/library/ethics-guidelines-trustworthy-ai)
- Related reviews:
  - [EU AI Act (review 01)](01-eu-ai-act.md) — the binding instrument that operationalises the HLEG framework
  - [Guidelines on Definition of AI System (review 02)](02-guidelines-definition-ai-system.md) — refines the AI system concept
  - [Guidelines on Prohibited AI Practices (review 03)](03-guidelines-prohibited-ai-practices.md) — addresses the four HLEG "critical concerns"
  - [Commission GPAI Guidelines (review 04)](04-commission-gpai-guidelines.md) — addresses the GPAI gap
  - [GPAI Code of Practice (review 05)](05-gpai-code-of-practice.md) — addresses long-term systemic risk
- Companion document: "A definition of AI: Main capabilities and scientific disciplines" (HLEG, 2019)
- Related external frameworks:
  - OECD AI Principles (May 2019)
  - G20 AI Principles (June 2019)
  - UNESCO Recommendation on the Ethics of AI (2021)
  - Council of Europe Framework Convention on AI (2024)
