# GDPR as an AI Overlay — UK and EU

The reviews in this repository focus on AI-specific instruments: the EU AI Act, the UK pro-innovation framework, the GPAI Code of Practice, sector-regulator updates, OMB memoranda, NIST RMF, and so on. They mention GDPR / UK GDPR repeatedly but do not give it a dedicated treatment as a **horizontal AI overlay** in its own right.

This is a gap. In practice — for almost every organisation deploying AI on the personal data of EU or UK residents — GDPR and UK GDPR are doing more day-to-day governance work than any AI-specific regime. They bite earlier, apply more broadly, and have a mature enforcement record that the AI-specific regimes do not yet have.

This note records the GDPR overlay as it applies to AI, the UK / EU divergence after DUAA 2025, and the interaction with the AI Act and the UK pro-innovation framework.

---

## Why GDPR is the de-facto AI regulator in Europe

GDPR (Regulation 2016/679) and UK GDPR (as retained and amended) are technology-neutral but their substantive rules attach to almost every meaningful step in an AI lifecycle that touches personal data:

- **Training data acquisition** — Article 5 (data minimisation, purpose limitation, lawfulness, fairness, transparency, accuracy), Article 6 (lawful basis), Article 9 (special-category data), Article 14 (information obligations where data is not collected from the data subject — the standard case for web-scraped training data).
- **Model training** — same Article 5/6/9 basis questions; legitimate interests balancing under Article 6(1)(f); Article 35 DPIA where high-risk processing.
- **Deployment / inference** — Article 5 again; Article 6 lawful basis for the inference processing (often different from the training basis); Article 22 (rules on solely automated decisions producing legal or similarly significant effects); Article 13/14 transparency to the data subject about the existence of automated decision-making and meaningful information about the logic.
- **Data subject rights through the lifecycle** — Articles 15–22 (access, rectification, erasure, restriction, portability, objection, automated-decision rights).
- **Sanctions** — up to €20M or 4% of global turnover (GDPR) / £17.5M or 4% of global turnover (UK GDPR).

These are AI-relevant in every jurisdiction where GDPR or UK GDPR applies, **without waiting for an AI-specific regulator to act**.

---

## Territorial scope — GDPR Article 3 / UK GDPR Article 3

Article 3 is the single most important AI-overlay provision because it determines who is in scope.

**EU GDPR Art 3:**

- **Art 3(1) — establishment:** applies to processing in the context of the activities of an establishment of a controller or processor in the Union, regardless of whether the processing itself takes place in the Union.
- **Art 3(2) — targeting:** applies to processing of personal data of data subjects who are in the Union by a controller or processor not established in the Union, where the processing activities are related to **(a)** the offering of goods or services to such data subjects (irrespective of payment), or **(b)** the monitoring of their behaviour as far as their behaviour takes place within the Union.

**UK GDPR Art 3:** mirrors the EU structure, with "the United Kingdom" substituted for "the Union" and the relevant scope captured by reference to UK-established controllers/processors and to data subjects in the UK.

### What this means for AI

- A US-headquartered AI company training a foundation model partly on EU personal data and offering the resulting service to EU users is in scope of GDPR under Art 3(2)(a). The location of the GPU cluster is not the test; the relationship to the data subject and the targeting of the service is.
- A UK-headquartered SaaS company embedding a third-party LLM and providing the service to UK users falls under UK GDPR Art 3(1) on its own processing, and the third-party LLM provider may also fall under UK GDPR Art 3(2) for its processing of UK data subject personal data.
- **For deployers in Europe, GDPR / UK GDPR reach is essentially universal** for any AI service touching personal data of EU/UK individuals — independently of whether the AI Act or the UK framework applies.

### Relationship to AI Act Art 2

The AI Act's extraterritorial reach (Article 2) and GDPR Article 3 reach **overlap but are not coextensive**:

| Aspect | GDPR / UK GDPR Art 3 | EU AI Act Art 2 |
|---|---|---|
| Reach by establishment | Yes, processor or controller established in EU / UK | Yes, providers and deployers established in EU |
| Reach by targeting / output | Yes — offer of goods/services or monitoring of behaviour in EU/UK | Yes — non-EU providers placing systems on EU market; output used in EU |
| Triggers on | Personal data processing | AI system placement / deployment, regardless of whether personal data is involved |
| Time horizon | In force since 2018 (EU) / 2021 (UK) | Phased: prohibitions Feb 2025; GPAI Aug 2025; high-risk Aug 2026 |

A given AI deployment can be in scope of one, the other, or both. The practical implication is that **GDPR is already enforceable today**, on every AI-on-personal-data scenario in the EU and UK, whereas significant parts of the AI Act are not yet binding.

---

## Where the AI overlay is hardest

### 1. Lawful basis for training data

Web-scale training on personal data raises Article 6 and Article 9 questions that the regulators have not collectively settled. Possible bases:

- **Consent (Art 6(1)(a))** — fragile at scale; revocable; rarely available for retrospective scraping.
- **Contract (Art 6(1)(b))** — narrow; needs a direct service relationship with the data subject.
- **Legitimate interests (Art 6(1)(f))** — the de-facto basis many providers rely on, requires balancing against data subject rights and a documented LIA; the ICO and CNIL have published views; the EDPB's December 2024 opinion on AI models (Opinion 28/2024) gave more structure but not closure.
- **Special-category data (Art 9)** — an Article 9 condition is needed in addition; the available conditions are narrow and almost never naturally satisfied by training-data scraping.

The Article 14 information obligation (notice where data is not collected from the data subject) is widely under-discharged in AI training contexts and is the single most exposed compliance gap.

### 2. Article 22 — solely automated decisions

The classic Article 22 prohibition on decisions based solely on automated processing with legal or similarly significant effects is the most direct AI-control provision in GDPR.

- **EU GDPR Art 22 — unchanged.** Prohibition with three narrow exceptions (necessary for a contract, authorised by Union or Member State law, explicit consent), all requiring safeguards including human intervention and the right to contest the decision.
- **UK GDPR Art 22 — materially relaxed by DUAA 2025.** The Data (Use and Access) Act 2025 replaces the prohibition-with-exceptions model with a permit-with-safeguards model: organisations may make solely automated decisions producing legal or similarly significant effects provided safeguards (information about the decision; ability to make representations; ability to obtain human intervention; ability to contest) are in place.

This is now the **clearest substantive divergence between UK and EU data protection law as it applies to AI**. UK-based AI deployers operating EU-targeted services have to comply with EU GDPR Art 22 in its stricter pre-reform form for EU data subjects regardless of DUAA. See [UK review 14](../UK/analysis/review-claude/14-data-use-and-access-act.md) for the full DUAA analysis.

### 3. Transparency about automated decision-making

Article 13(2)(f) / 14(2)(g) require **"meaningful information about the logic involved"** in automated decision-making, and **"the significance and the envisaged consequences"** for the data subject. For complex LLM-based systems this is a non-trivial requirement and is increasingly being read as requiring **model-card-style disclosures**, not just generic notices. The EDPB and ICO have both signalled tightening interpretation. The AI Act Article 13 (transparency for high-risk systems) and Article 50 (transparency obligations on certain AI system providers / deployers) layer on top of the GDPR transparency obligations — they do not replace them.

### 4. DPIA — Article 35

Article 35 requires a Data Protection Impact Assessment where processing is "likely to result in a high risk to the rights and freedoms of natural persons." Supervisory authority lists (ICO, CNIL, others) consistently treat AI / automated decision-making / large-scale profiling as triggering Art 35. DPIAs are therefore the **routine governance artefact** for AI projects in Europe, and they are already required regardless of AI Act timeline.

The AI Act's Fundamental Rights Impact Assessment (FRIA) for high-risk deployers (Article 27) is a parallel artefact with different scope; many organisations are now running them as a combined exercise.

### 5. Cross-border data transfers

GDPR Chapter V (and the UK GDPR equivalent) restricts transfers of personal data to third countries without adequate safeguards (adequacy decisions, SCCs, BCRs, derogations).

For AI this matters because:

- Training and inference often occur in non-EU compute (most frontier-model providers are US-based).
- Calling a US-based LLM API from an EU deployment is a transfer subject to Chapter V.
- The EU–US Data Privacy Framework (adequacy decision, July 2023) currently covers transfers to participating US controllers/processors but is the subject of pending Schrems-style legal challenges. Plan for instability.
- DUAA 2025 simplifies the **UK** approach to cross-border transfers but does not displace the underlying need for an adequacy decision or alternative safeguard.

---

## Interaction with the AI-specific regimes

### EU AI Act

The AI Act is explicit that it operates **without prejudice to GDPR** (see AI Act recitals on the relationship to data protection law). Compliance with the AI Act does not relieve a controller of GDPR obligations and vice versa. In practice this means:

- A high-risk AI system using personal data must comply with both the AI Act's high-risk obligations (Articles 8–17) and the GDPR.
- An Article 50 transparency obligation (under the AI Act) does not discharge Article 13 / 14 transparency obligations under GDPR.
- An Article 27 FRIA does not discharge an Article 35 DPIA; in practice they should be run together.

### UK pro-innovation framework

The UK framework explicitly relies on existing law — and UK GDPR is the largest single element of that existing law as applied to AI. The ICO is the most active UK sector regulator on AI through its [AI and Data Protection guidance](https://ico.org.uk/for-organisations/guidance-on-ai-and-data-protection/) and explanatory work with the Alan Turing Institute. The ICO is therefore effectively **a primary AI regulator** in the UK without being styled as one.

DUAA 2025 (reviewed in [UK/analysis/review-claude/14](../UK/analysis/review-claude/14-data-use-and-access-act.md)) materially changes the UK's data protection law as it applies to AI in three ways relevant here: relaxation of Art 22 automated decisions, introduction of Recognised Legitimate Interests as a new lawful ground, and clarification that scientific research includes commercial research.

### US (briefly, for contrast)

The US has no horizontal data protection statute. AI-relevant data handling sits across state privacy laws (California CPRA / ADMT, Colorado CPA, Virginia VCDPA, etc.) and sectoral federal law (HIPAA, GLBA, FCRA, COPPA). The functional equivalent of GDPR-as-AI-overlay does not exist at federal level. See the comparisons document [USA-EU-comparison.md](USA-EU-comparison.md) and the state-level note [`../USA/analysis/state-legislation.md`](../USA/analysis/state-legislation.md).

---

## Practical implications

1. **GDPR / UK GDPR are doing most of the AI governance work today.** For EU/UK operators, AI compliance is GDPR compliance plus an emerging AI-specific layer. Treating the AI Act as the primary instrument and GDPR as background is the wrong way round at present.

2. **Article 3 territorial scope is wider than most teams assume.** Any AI service offered to EU or UK individuals brings GDPR / UK GDPR scope; the location of the model, the GPUs, or the company is not the test.

3. **Article 22 is now divergent between UK and EU.** DUAA 2025 materially relaxes UK automated-decision rules; EU GDPR Article 22 is unchanged. Cross-border services must comply with the stricter EU rule for EU data subjects.

4. **Training-data lawful basis remains the most exposed point.** Legitimate interests is workable but requires a defensible LIA; Article 14 transparency to non-customer data subjects in training sets is widely under-discharged; Article 9 conditions almost never naturally fit web-scraped data.

5. **DPIAs and FRIAs should be run together for high-risk AI.** Different statutory tests but overlapping evidence base. Doing one without the other is now an audit finding.

6. **Cross-border transfers to US-based AI APIs depend on the Data Privacy Framework holding.** Plan for instability; have an SCC fallback.

---

## Sources and further reading

- Regulation (EU) 2016/679 (GDPR), in particular Articles 3, 5, 6, 9, 13, 14, 22, 35, Chapter V.
- UK GDPR (retained EU law) as amended by the Data Protection Act 2018 and the Data (Use and Access) Act 2025; same article numbering.
- EDPB Opinion 28/2024 on AI models (December 2024) — the EDPB's structured view on lawful basis and data subject rights in foundation models. (Not held in this repository; pointer for further review.)
- ICO, [Guidance on AI and Data Protection](https://ico.org.uk/for-organisations/guidance-on-ai-and-data-protection/) — current operational guidance for the UK.
- DUAA 2025 — see [UK review 14](../UK/analysis/review-claude/14-data-use-and-access-act.md) for the substantive AI-relevant changes.
- EU AI Act recitals on the relationship to GDPR; AI Act Articles 2, 13, 27, 50, 73 for the interaction points discussed above.
- [`USA-EU-comparison.md`](USA-EU-comparison.md) and [`UK-EU-comparison.md`](UK-EU-comparison.md) — for the surrounding AI-specific comparisons.
