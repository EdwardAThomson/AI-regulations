# Commission Guidelines on Prohibited AI Practices — Review

**Document:** Commission Guidelines on prohibited artificial intelligence practices established by Regulation (EU) 2024/1689 (AI Act)
**Published:** Brussels, 29 July 2025
**Reference:** C(2025) 5052 final — Communication from the Commission
**Issuing body:** European Commission
**Length:** 134 pages
**Legal basis:** Article 96(1)(b) of the AI Act
**Legal status:** Non-binding — authoritative interpretation ultimately rests with the CJEU

---

## Summary

These Guidelines are the Commission's detailed interpretation of Article 5 of the AI Act — the eight categories of prohibited AI practices, applicable since 2 February 2025. The document is four times longer than its companion guidelines on the AI system definition because Article 5 is far more contested in practice. The Guidelines set out cumulative conditions for each prohibition, worked examples of what is and is not prohibited, relationships with GDPR/LED and other EU law, and the procedural machinery for the real-time remote biometric identification (RBI) exception (which occupies nearly half the document). The Commission takes several consequential interpretive positions, including: narrow construction of the prohibitions; broad interpretation of "use" (covering all lifecycle phases including misuse); no requirement of intent (effect alone suffices); provider responsibility for general-purpose AI even where prohibited behaviour is not purposefully designed; non-applicability of accessibility failures as "exploitation of disability"; and the primacy of the prohibitions even where other Union law (GDPR, LED) would separately apply. For UK-based firms serving EU clients, these Guidelines are the primary reference for whether specific AI deployments fall into the prohibition zone, which carries fines of up to 35 million EUR or 7% of global turnover.

---

## Key Points

### Structural Framework (Section 2)

- **Applied from 2 February 2025** — six months after entry into force
- **Penalties:** up to 35M EUR or 7% of global turnover (Article 99)
- **Narrow construction principle** (paragraph 57): "Since violations of the prohibitions in Article 5 AI Act interfere the most with the freedoms of others and give rise to the highest fines, their scope should be interpreted narrowly"
- **Broad use definition** (paragraph 14): "use" includes "any misuse of an AI system ('reasonably foreseeable' or not) that may amount to a prohibited practice"
- **Direct effect** between 2 Feb 2025 and 2 Aug 2025 (before market surveillance authorities are operational): affected parties can enforce in national courts and seek interim injunctions
- **National security / defence exclusion** turns on purpose (CJEU La Quadrature du Net definition), not entity type. Dual-use systems fall in scope. Europol and Frontex are within scope
- **Free and open source carve-out** does NOT apply to prohibited practices — even open-source systems must comply

### Article 5(1)(a) — Subliminal / Manipulative / Deceptive Techniques

**Four cumulative conditions:** AI system + deploys one of the three techniques + materially distorts behaviour (appreciable impairment of informed decision-making) + causes or is reasonably likely to cause significant harm, with a plausible causal link.

**Techniques covered:**
- **Subliminal** — visual/auditory/tactile below conscious awareness; includes temporal manipulation and embedded images; neurotech/brain-computer interfaces fall in scope only where significantly harmful
- **Purposefully manipulative** — designed to influence/alter/control behaviour undermining autonomy; exploit cognitive biases or psychological vulnerabilities. **Intent not required**. System-generated manipulation (training/reward-gaming) covered unless provider took "appropriate preventive and mitigating measures" and manipulation is incidental
- **Deceptive** — presenting false/misleading info with objective or effect of deceiving. Distinguished from Article 50 transparency obligations (which require labelling). Evaluation-gaming AI that temporarily suppresses undesired behaviour during evaluation is "particularly dangerous"

**Hallucinations typically outside the prohibition** — if the provider (i) discloses limitations, (ii) integrates safeguards, (iii) the system isn't deployed in sensitive contexts (health, education, elections)

**Key interpretive position:** Commission imports the UCPD "average consumer" test (Canal Digital Danmark, Trento Sviluppo, Compass Banca). Capability to distort (not realised distortion) suffices. Compass Banca (C-646/22) recognises that cognitive biases can impair autonomy.

**Significant harm factors** (paragraph 91): severity, context/cumulative effects, scale/intensity, vulnerability of affected persons, duration/reversibility. "Long-lasting or irreversible harm typically meets the threshold."

### Article 5(1)(b) — Exploitation of Vulnerabilities

**Cumulative conditions:** AI system + exploits vulnerabilities of age/disability/social-economic situation + materially distorts behaviour (no "appreciable impairment" requirement — vulnerability itself reduces decision capacity) + causes or is reasonably likely to cause significant harm.

**Only three vulnerability sources qualify:**
- **Age** — both children (<18, developmental stage) and older persons (reduced cognitive capacity)
- **Disability** — per Directive 2019/882 (physical, mental, intellectual, sensory impairments)
- **Specific social or economic situation** — extreme poverty, ethnic/religious minorities, temporary unemployment, over-indebtedness, migration status. Not "grievances or loneliness" (not socio-economically specific)

**Key carve-outs:**
- **Accessibility failures ≠ exploitation of disability** (paragraph 108): inaccessible AI does not "specifically target" vulnerabilities of persons with disabilities
- **Indirect discrimination via biased training data alone ≠ exploitation** — unless providers/deployers are aware and fail to correct (paragraphs 110-111)
- **Broad consumer targeting ≠ exploitation** if variables don't correlate with vulnerable groups (phone brand, city size, travel patterns)

**Prohibited examples:**
- AI-powered toy encouraging risky challenges for digital rewards
- Addictive game using personalised reinforcement schedules on children
- Therapeutic mental-health chatbot pushing expensive products to persons with intellectual disabilities
- Predictive algorithm targeting predatory lending ads to low-income postcodes
- Chatbot identifying migrant vulnerabilities and pushing extremist views

### Article 5(1)(c) — Social Scoring

Prohibits AI evaluating or classifying natural persons based on social behaviour or personal/personality characteristics over a period of time, where the resulting social score leads to:
- Detrimental or unfavourable treatment **in social contexts unrelated** to the original data collection context, OR
- Detrimental or unfavourable treatment that is **unjustified or disproportionate** to the social behaviour

Applies to **both public and private actors** — not limited to state-run social credit systems.

Interplay: Annex III benefits-determination AI is typically high-risk, but becomes prohibited if 5(1)(c) conditions are met. Traders' social scoring may separately be "unfair" under Directive 2005/29/EC (UCPD).

### Article 5(1)(d) — Predictive Policing Based Solely on Profiling

**Three cumulative conditions:** AI system + risk assessment/prediction of a natural person committing a criminal offence + based **solely** on profiling (Art. 4(4) GDPR) OR personality trait assessment.

**Key interpretive positions:**
- **"Solely"** applies to both profiling and personality-trait assessment. Other factors may be considered but must be "real, substantial and meaningful" — trivial additions cannot circumvent
- **"Criminal offence"** has autonomous EU meaning (Engel criteria from ECtHR/CJEU); excludes administrative offences (petty traffic, procurement/tax irregularities)
- **Forward-looking** — covers future offences, attempts, preparatory activities; applies at all stages including pre-trial detention and re-integration
- **Group profiling to individual application** falls within scope
- **Not limited to law enforcement authorities** — applies to private actors acting on behalf of LEAs (e.g., analytics company asked to cross-analyse data to predict offenders)

**Worked examples:**
- Prohibited: AI predicting terrorism solely from age, nationality, address, car type, marital status
- Prohibited: tax AI reviewing returns using opaque variables like double nationality, place of birth
- Not prohibited: location/geospatial/place-based predictions (crime hotspot maps, customs narcotics routes, gunshot triangulation)
- Not prohibited: AI supporting human assessment based on objective verifiable facts (past criminal history + rehabilitation evidence)
- Not prohibited: AML screening under Regulation 2024/1624 using only objective verifiable data, subject to human assessment
- Not prohibited: legal entity profiling (companies, NGOs for tax/customs fraud) — unless natural person operates through as sole trader

**If exception applies, system is high-risk** under Annex III point 6(d) with full Article 14 human oversight and Article 26 obligations.

### Article 5(1)(e) — Untargeted Scraping of Facial Images

**Four cumulative conditions:** AI system + for creating/expanding facial recognition databases + through untargeted scraping (AI tools, "vacuum cleaner" approach) + from internet or CCTV footage.

**Key interpretive positions:**
- **"Untargeted"** — like a vacuum cleaner, not aimed at specific individuals. **Respect for robot.txt does not cure the untargeted nature**
- **Consent does not cure** — the prohibition applies even if individuals consented to their images being included
- **Step-by-step targeted scraping that is functionally equivalent to untargeted is also prohibited** — anti-circumvention rule
- **Reverse image search** — targeted scraping, outside scope (and questionable whether results appear in a "database")
- **Limits of scope:** Non-facial biometric data (voice samples) is not covered. Databases used for AI training but NOT for recognition are not covered. Synthetic face generators are not covered (no recognition of real persons — may still trigger Article 50 transparency). Pre-existing databases can continue in use but cannot be expanded via AI untargeted scraping

**Classic Clearview-AI-style prohibited scenario:** automated image scraper across Facebook, YouTube, Twitter, Venmo collecting faces with URL/geo-localisation and hashed feature vectors.

**Interplay with GDPR:** "The untargeted scraping of the internet or CCTV material to build up or expand face recognition databases... would be unlawful and no legal basis under the GDPR, EUDPR and the LED could be relied upon."

### Article 5(1)(f) — Emotion Recognition in Workplace and Education

**Four cumulative conditions:** AI system + infers emotions + from biometric data + in workplace or education/training institution + not for medical or safety reasons.

**Key interpretive positions:**
- **"Emotions" broad** — happiness, sadness, anger, surprise, disgust, embarrassment, excitement, shame, contempt, satisfaction, amusement, plus "attitudes" (to prevent circumvention by relabelling)
- **Excluded from "emotions":** physical states (pain, fatigue) and detection of "readily apparent expressions" (smiles, frowns, gestures) **unless** used to infer emotions
- **Must be based on biometric data** — text-only sentiment analysis outside scope; keystroke/facial expression/body posture/voice in scope
- **"Workplace" broad** — physical/virtual spaces; employees, contractors, trainees, volunteers; covers candidates during recruitment and probation
- **"Education institutions" broad** — public/private, all ages, online/in-person/blended; covers candidates during admissibility

**Medical/safety exception narrowly construed:**
- Therapeutic use = CE-marked medical devices
- "Safety" = life and health only, NOT property against theft or fraud
- Monitoring stress, burnout, depression at work does NOT qualify
- Must be strictly necessary and proportionate with time/scale limits

**Worked examples:**
- Prohibited: call centre webcams/voice tracking employees' emotions; hybrid team emotional tone monitoring; emotion recognition during recruitment or probation; supermarket cameras tracking employee happiness
- Prohibited: eye-tracking in education that also detects emotional arousal; inferring student interest/attention (unless role-play training not affecting evaluation)
- Not prohibited: call centre tracking **customers'** emotions to help employees cope; AI capturing students talking during online lectures without emotion inference; supermarket cameras detecting suspicious customers preparing robbery
- Within safety exception: emotion recognition assisting autistic employees/students; detecting stress on workers operating dangerous machinery (but data not used for performance assessment)

**Non-workplace / non-education emotion recognition** is not prohibited but is high-risk under Annex III 1(c) and subject to Article 50(3) transparency. May be caught by 5(1)(a)/(b) if manipulative/exploitative.

### Article 5(1)(g) — Biometric Categorisation on Sensitive Attributes

**Five cumulative conditions:** AI system + biometric categorisation + individual persons (not group-level) + based on biometric data + to deduce/infer **race, political opinions, trade union membership, religious or philosophical beliefs, sex life, sexual orientation** (exhaustive list).

**"Ancillary" carve-out** (Article 3(40)): AI categorisation is not covered if (a) ancillary to another commercial service AND (b) strictly necessary for objective technical reasons. Examples allowed: marketplace try-on filters; social network face/body modification filters. Not allowed: categorisation by inferred political orientation for targeted political ads (not "strictly necessary").

**Labelling and filtering of lawfully acquired datasets NOT prohibited** (paragraph 284):
- Labelling to counteract biased training data (e.g., balancing ethnic representation for fair hiring AI)
- Categorising patients by skin/eye colour for medical diagnosis
- Law enforcement labelling CSAM-suspected datasets to filter by age, gender, scars, tattoos to aid suspect identification

**Sensitive list is exhaustive** — categorisation by age, gender, height, hair colour is not in the 5(1)(g) list (though Annex III 1(b) makes sensitive biometric categorisation high-risk unless prohibited).

**Prohibited examples:**
- "Deducing race from voice"
- Deducing religious orientation from tattoos or faces

### Article 5(1)(h) — Real-Time Remote Biometric Identification in Publicly Accessible Spaces for Law Enforcement

Nearly half the Guidelines (paragraphs 289-428) treat this prohibition in detail because the narrow exception triggers the most intricate procedural requirements.

**Cumulative conditions:** RBI system + use (not placing on market or putting into service) + real-time + publicly accessible space + law enforcement purpose.

**Three narrow permitted purposes** (Art. 5(1)(h)(i)-(iii)):

1. **Targeted search for specific victims** of abduction, human trafficking, sexual exploitation, OR missing persons (distinction between missing children and adults — adults have "right to disappear")
2. **Prevention of specific, substantial and imminent threat to life/physical safety** OR genuine and present (or genuine and foreseeable) terrorist attack threat. Covers critical infrastructure threats where disruption would result in imminent life/safety threats
3. **Localisation/identification of suspects of Annex II offences** punishable by 4+ years custodial sentence (euro crimes + serious cooperation priorities). Covers suspects, perpetrators, and by extension accomplices. No European Arrest Warrant required. Broad/untargeted deployment "in the hope of finding wanted criminals" not allowed; targeted search for specific wanted suspect at a specific location allowed

**Defining concepts:**
- **RBI** — identification (1:many) not verification (1:1); must be remote (no active involvement; merely informing about cameras insufficient)
- **Real-time** — instantaneous or short delay that would not let the person leave the location (post-RBI is not prohibited but subject to Article 26(10) safeguards from August 2026)
- **Publicly accessible space** — physical only; public or private ownership; concerts, shops, banks, airports, public roads, parks. **Not** publicly accessible: factories with entry control, prisons, border control areas (but streets leading to border crossings are). Online spaces excluded
- **Law enforcement purpose** — prevention, investigation, detection, prosecution, execution of penalties. Includes "on behalf of" LEAs (public transport companies, sports federations, banks when specifically requested)

**Procedural requirements (Article 5(2)-(7)):**

1. **Targeted identity confirmation only** — must confirm a "specifically targeted individual" (not general identification)
2. **Double necessity/proportionality assessment** — deployer FRIA + authorising authority review
3. **Temporal, geographic, personal limitations** — geographic area "clearly delineated," "should not normally comprise an entire city or country"; specific categories of persons
4. **Fundamental Rights Impact Assessment** (Article 27) before deployment — complements (not replaces) GDPR Article 35 / LED Article 27 DPIA. Must cover: private/family life including "reasonable expectation of anonymity in public spaces"; data protection; freedom of thought/conscience/religion/expression/assembly; effective remedy; non-discrimination; human dignity; presumption of innocence; rights of the child
5. **EU database registration** (Article 49) — in a secure **non-public** section. Emergency exception allows deployment before registration, "without undue delay" (24 hours reasonable in live-shooter scenario)
6. **Prior authorisation by judicial or independent administrative authority** — authority must be independent from police, investigative judges, prosecutors using the RBI. Urgency exception: deployment begins without authorisation but must be requested within **24 hours**. If rejected: immediate cessation and deletion of all data, results, outputs
7. **No solely automated adverse decisions** (Article 5(3)) — verification by at least two natural persons with competence, training, authority (Article 14(5)) unless disproportionate
8. **Notification** (Article 5(4)) to national market surveillance and data protection authorities
9. **National law is a pre-requisite** (Article 5(5)) — Member States must authorise use by national law. Rules must regulate competent authorities, procedural safeguards, accuracy thresholds, audit mechanisms, reference databases, data retention, rights of persons searched and bystanders. Commission publishes Member States' laws. Notification to Commission within 30 days of adoption
10. **Annual reporting** (Article 5(6)-(7)) — MS authorities to Commission; Commission publishes aggregated reports excluding sensitive operational data

**Out-of-scope (but may be high-risk under Annex III 1(a)):**
- Biometric verification (1:1)
- Retrospective RBI for law enforcement
- Real-time RBI in private spaces (homes) or online spaces
- Real-time RBI by private actors acting on their own behalf (supermarket shoplifters, sports arena banned-person checks)
- School attendance FRT, hotel VIP recognition

### Interplay with Other Union Law

**Complementary, not substitutive** (paragraph 42): the AI Act applies "without prejudice to other Union legislation, in particular on the protection of fundamental rights, consumer protection, employment, the protection of workers, and product safety."

**AI Act compliance ≠ other compliance** (paragraph 43): "The respect of the prohibitions in the AI Act are therefore not a sufficient condition for compliance with other Union legislation."

**GDPR/LED** continue to apply alongside. For biometric categorisation (5(1)(g)) and RBI for law enforcement (5(1)(h)), the AI Act is **lex specialis to Article 10 LED**. Crucially: "the AI Act is not intended to provide the legal basis for the processing of personal data under Article 8 of Directive (EU) 2016/680" — personal data processing still requires its own legal basis.

**Non-circumvention** (paragraph 50): Article 5 prohibitions and exceptions "may not be used to circumvent or as a justification to infringe obligations under other Union legislation."

**Ne bis in idem** (paragraph 56): same conduct may breach multiple provisions (e.g., unlabelled deepfake is both Article 50 transparency breach and Article 5(1)(a) deception); ne bis in idem must be respected in cumulative enforcement.

### General-Purpose AI Systems

**Provider responsibility for general-purpose AI** (paragraphs 40-41): providers must not place on market GPAI systems "reasonably likely to behave or be directly used in a manner prohibited by Article 5." Providers must:
- Implement safeguards
- Exclude prohibited uses contractually (terms of use)
- Provide appropriate instructions
- Conduct monitoring proportionate to supply method

But monitoring "must not amount to a general monitoring of the activities of the deployers" (echoing e-Commerce Directive / DSA principles).

### Interim Enforcement

Between 2 February 2025 and 2 August 2025, market surveillance authorities were not yet operational, but the prohibitions have **direct effect** and can be enforced via national courts with interim injunctions. Penalties apply from 2 August 2025.

---

## Observations

### Clarity

These Guidelines are the most substantial interpretive document the Commission has issued under the AI Act and a significant contribution to legal certainty. The structure (purpose, general principles, prohibition-by-prohibition analysis with elements, scope, exceptions, examples) is logical and usable.

The worked examples are a particular strength. For each prohibition, the Commission provides:
- Prohibited examples (specific scenarios that fall within scope)
- Non-prohibited examples (specific scenarios that do not, with explanations)
- Boundary/contested examples where scope depends on facts

The "Not prohibited" examples are arguably more useful than the "Prohibited" examples for practitioners, as they demarcate the safe space. For instance, the paragraph 280 examples on ancillary biometric categorisation (try-on filters permitted; political-orientation ad targeting prohibited) map a clear operational boundary.

The Guidelines are weaker at:
- **Resolving ambiguities in threshold concepts**. "Significant harm," "material distortion," "appreciable impairment," "specific social or economic situation," "strictly necessary" — all are explained but not quantified. Each remains a judgement call in marginal cases
- **Handling generative AI beyond the hallucination carveout**. The document was written for systems with defined intended purposes; generative AI deployments that users adapt in unexpected ways generate compliance questions not directly addressed
- **Cross-referencing with other guidance**. The Guidelines reference but do not integrate with the GPAI Guidelines, GPAI Code of Practice, serious incident reporting guidance, and transparency code — practitioners must consult multiple sources

### Measurability

Highly detailed where detail is possible. Specific procedural timelines for RBI (24-hour urgency authorisation; 24-hour emergency registration; 30-day Member State notification to Commission) are operationally actionable.

But the substantive thresholds remain qualitative. "Significant harm" is illustrated (severity, context, scale, vulnerability, duration/reversibility) but not defined. A firm seeking to assess whether its deployment meets the threshold must exercise judgement and document reasoning.

For RBI procedural compliance, the Guidelines provide essentially an implementation manual. For manipulation, social scoring, and predictive policing, the Guidelines provide interpretive principles that still leave substantial room for case-specific analysis.

### Gaps

**Workplace AI beyond emotion recognition.** The Guidelines cover Article 5(1)(f) emotion recognition extensively. But many workplace AI systems (performance management, automated scheduling, productivity monitoring, promotion algorithms) face Annex III 4(b) high-risk classification rather than prohibition. The Guidelines do not address the threshold between permitted-but-high-risk workplace AI and prohibited workplace practices under 5(1)(a) manipulation or 5(1)(b) exploitation.

**Dark patterns / UX manipulation.** Article 5(1)(a) could catch many commercial UX practices (infinite scroll, loss aversion framing, default selection nudges). The UCPD-inspired interpretation brings consumer protection concepts into Article 5, but the document does not specifically address commonplace web/mobile UX patterns. Industry will press for clarity; the Commission has not provided it.

**Recommender system borderlines.** Social media recommenders, news algorithms, and advertising targeting can plausibly manipulate, exploit vulnerabilities, or socially score. The Guidelines do not explicitly address when these widespread systems cross into prohibition territory. The DSA addresses some concerns (especially for VLOPs), but the boundary with Article 5 is not drawn.

**Children's AI products beyond obvious exploitation.** Educational AI for children, AI tutors, AI-powered toys without explicit reinforcement schedules sit in a grey zone. Not all AI serving children is prohibited; the Guidelines give examples of obvious violations but do not provide a framework for legitimate child-facing AI design.

**Research exception boundaries.** The R&D exemption (paragraphs 30-33) excludes pre-market research but not real-world testing. Academic research using real-world data to study AI manipulation effects sits in a contested zone. The Guidelines note research into cognitive responses to subliminal stimuli is permitted, but the line between permitted study and real-world-testing-by-another-name is thin.

**Retrospective application to prior deployments.** Article 5 applies from 2 February 2025 regardless of when the system was placed on market. The Guidelines confirm direct application but do not address how firms with existing AI deployments should conduct retrospective compliance assessment or document remediation.

**Private-actor RBI.** The Guidelines clarify that Article 5(1)(h) does not apply to private actors (supermarkets, sports arenas) using real-time RBI on their own behalf. But they also note such uses may violate GDPR Article 9 and cite national cases prohibiting shopping mall FRT (Netherlands DPA, Spain, France CNIL). The AI Act thus leaves a gap that national data protection law fills, creating jurisdictional complexity.

### Feasibility

For most of the prohibitions (5(1)(a)-(g)), compliance is about scoping — determining whether an AI system falls within the prohibition. This is feasible with the Guidelines' help, though marginal cases will remain contested.

For Article 5(1)(h) real-time RBI by law enforcement, compliance is a major procedural undertaking:
- Member State enabling legislation required
- Judicial/administrative authorisation for each use
- FRIA before deployment
- EU database registration
- Two-person verification human oversight
- Annual reporting

This is deliberately onerous — the Act treats real-time RBI as near-prohibited, with the exception structured to deter rather than enable use. The practical effect is that real-time RBI by law enforcement in publicly accessible spaces becomes rare and heavily scrutinised.

For provider liability on general-purpose AI, feasibility is more uncertain. The obligation to implement safeguards against all "reasonably likely" prohibited uses of a GPAI system, while not being required to generally monitor deployer activity, will require significant engineering and contractual effort. How providers demonstrate compliance without over-enforcing will evolve through practice.

### Internal Consistency

The Guidelines are internally consistent. Some interpretive choices deserve note:

**Broad "use" definition** (paragraph 14) is consistent with the Act's risk-based approach but creates uncertainty for providers — "reasonably foreseeable misuse" is inherently elastic.

**Narrow construction principle** (paragraph 57) and broad use definition sit in tension. The Commission resolves this by construing the **substantive conditions** narrowly while interpreting the **scope triggers** (use, placing on market) broadly. This may make conceptual sense but leaves interpretive ambiguity.

**Intent-not-required** position for both 5(1)(a) and 5(1)(b) is consistent within the Guidelines but creates provider liability for emergent behaviour. The mitigation that "incidental" manipulative behaviour from a properly safeguarded GPAI is not "purposeful" reduces but does not eliminate exposure.

### Coverage

Coverage within the Guidelines' scope is comprehensive. All eight Article 5 prohibitions are addressed; RBI gets proportionate treatment; interplay with other Union law is clearly mapped.

What is deliberately outside scope: high-risk AI classification and obligations (covered by Article 6+), GPAI model obligations (Chapter V and the GPAI Guidelines), Article 50 transparency obligations, serious incident reporting, and national implementation law.

### International Alignment

The Guidelines are heavily Europe-specific. The UCPD-derived "average consumer" test, the LED/GDPR lex specialis analysis, the Charter-conforming interpretation, and the references to Member State opt-outs (Protocols 21 and 22 for Ireland and Denmark) all reflect EU legal architecture.

For UK firms, the most important cross-jurisdictional points are:
- **UK's post-Brexit divergence widens.** DUAA 2025 relaxes Article 22 UK GDPR restrictions on automated decisions; the EU Guidelines reaffirm the strict GDPR/LED framework alongside Article 5
- **Social scoring concepts converge with consumer protection.** UCPD parallels to Article 5(1)(c) social scoring suggest traders' AI credit/behaviour scoring may face dual enforcement (consumer law + AI Act)
- **Predictive policing 5(1)(d) carries fewer implications for UK firms** since it targets law enforcement uses; private analytics firms asked by EU LEAs to conduct such analysis are caught
- **Emotion recognition 5(1)(f)** is directly relevant for HR tech firms. UK firms selling HR emotion-recognition products to EU employers face prohibition; even if the UK permits the product, EU deployment is prohibited

---

## Overall Assessment

These Guidelines are the most important interpretive document for UK firms needing to assess whether their AI deployments fall into the EU's prohibited practices zone. The 134-page length reflects the operational complexity of Article 5 — the prohibitions are the most consequential provisions of the Act (penalties up to 7% of global turnover) and the most contested in practice.

The document's greatest strength is the systematic treatment of each prohibition with worked examples of what is and is not prohibited. For practitioners asked "is our product prohibited?" the Guidelines provide substantial traction. The boundary cases (ancillary biometric categorisation, labelling datasets for law enforcement, emotion recognition exceptions, RBI procedural requirements) are drawn with precision.

The document's limitations are inherent to the task: Article 5 uses open-textured language ("significant harm," "material distortion," "specifically vulnerable," "strictly necessary") that resists full operational specification. The Guidelines structure the analysis but cannot eliminate judgement. Commission enforcement practice, market surveillance authority decisions, and eventual CJEU rulings will continue to refine the prohibitions' scope.

For UK-based firms serving EU clients, several practical implications follow:

1. **Product-level scope assessment is essential.** Before placing any AI system on the EU market (or letting its output be used in the EU), assess whether any of the eight prohibitions could apply. Document the analysis for each prohibition that could plausibly be in play. This includes checking: subliminal/manipulative/deceptive techniques, vulnerability exploitation, social scoring, predictive policing elements, facial image scraping, workplace/education emotion recognition, sensitive-attribute biometric categorisation, real-time RBI (mostly irrelevant to private providers but relevant if commissioned by LEAs).

2. **The "output-used-in-EU" extraterritorial hook applies.** UK-based providers whose AI output is used in the EU are subject to Article 5 even without EU establishment. Firms providing APIs, SaaS products, or consultancy services to EU customers must comply.

3. **GPAI system providers face specific responsibilities.** The Commission's position on GPAI safeguards (paragraphs 40-41) — contractual exclusions, safeguards against reasonably-likely-prohibited uses, proportionate monitoring — imposes meaningful engineering and legal requirements on anyone supplying general-purpose AI to EU users.

4. **HR tech and workplace AI face sharp prohibition risk.** Emotion recognition during recruitment, probation, or in-role monitoring is now explicitly prohibited. UK-established HR tech firms serving EU employers must assess their product features against Article 5(1)(f) immediately — prohibitions have been in force since February 2025.

5. **Biometric product lines require review.** Any product that categorises persons by biometric data and risks inferring sensitive attributes (race from voice, religion from imagery, political views) is prohibited. UK firms developing biometrics should ensure the seven-element test for biometric categorisation (Article 3(40)) is not met, or can rely on the narrow "ancillary" carve-out.

6. **The prohibitions are not limits on innovation — they are limits on deployment.** Most AI products are not prohibited; most sit in the "minimal risk" category or, if classified, as "high-risk" under Article 6. The Guidelines reinforce that classification under Article 5 is the exception, not the rule. But where it applies, it applies absolutely — there is no way to bring a prohibited AI system into compliance except by redesigning out of the prohibition.

7. **Enforcement is active from February 2025.** Even without market surveillance authorities, direct effect allows national court enforcement. Article 5 prohibitions should not be treated as deferred obligations.

For firms close to the boundary, legal advice is essential. The Guidelines help practitioners assess scope but cannot substitute for jurisdiction-specific analysis of specific products. The penalty structure — 35M EUR or 7% of global turnover for Article 5 violations — makes accurate scoping consequential.

---

## Sources

- [Commission Guidelines on prohibited AI practices (C(2025) 5052)](https://digital-strategy.ec.europa.eu/en/library/commission-guidelines-prohibited-artificial-intelligence-practices-established-regulation-eu)
- [EU AI Act (Regulation 2024/1689)](../../source/EU-AI-Act-Regulation-2024-1689.pdf)
- Related reviews in this repo:
  - [EU AI Act (review 01)](01-eu-ai-act.md) — overarching Act review
  - [Guidelines on Definition of AI System (review 02)](02-guidelines-definition-ai-system.md) — scope companion
- CJEU case law referenced: La Quadrature du Net (C-623/17); Commission v Poland (C-623/17); Canal Digital Danmark (C-611/14); Trento Sviluppo (C-281/12); Compass Banca (C-646/22); Ligue des droits humains (C-817/19); SpaceNet (C-793/19); HK v Prokuratuur (C-746/18); Commission v Poland (C-530/16); Airbnb Ireland (C-390/18)
