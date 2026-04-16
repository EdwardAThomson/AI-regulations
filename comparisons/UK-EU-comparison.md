# UK vs EU: AI Governance Comparison

A comparison of the UK's AI governance position (as analysed in 14 document reviews in [`../UK/analysis/review-claude/`](../UK/analysis/review-claude/)) with the EU's (10 document reviews in [`../EU/analysis/review-claude/`](../EU/analysis/review-claude/)).

The UK and EU represent the two most mature AI governance approaches in the world, and they are substantively different on nearly every design choice: regulatory philosophy, legal form, scope, GPAI/foundation-model treatment, transparency, enforcement, and international positioning. For UK-based firms serving EU clients, understanding both is not optional — the AI Act's extraterritorial reach means the EU framework applies to UK providers whose systems are placed on the EU market or whose outputs are used in the EU, regardless of UK establishment.

---

## What each has

| Dimension | UK | EU |
|-----------|----|----|
| **Primary instrument** | Pro-Innovation White Paper (Mar 2023) + Consultation Response (Feb 2024). Non-statutory. Five cross-sectoral principles. | EU AI Act (Regulation 2024/1689, Jul 2024). Binding. Risk-based: prohibited / high-risk / limited / minimal + GPAI. |
| **Legal form** | Policy framework, not statute. Sector-regulator-led. Government committed to statutory AISI; not delivered. | Regulation (directly applicable in Member States). Enforced by national competent authorities + AI Office. |
| **Entry into force / application** | White Paper 2023; operational through sector regulators continuously; no phased application because no new statutory obligations. | In force 1 Aug 2024. Phased: prohibitions + AI literacy 2 Feb 2025; GPAI rules 2 Aug 2025; high-risk + transparency 2 Aug 2026; embedded products 2 Aug 2027. |
| **Extraterritorial reach** | No. DUAA 2025 applies only to UK-established processing or UK data subjects under existing UK GDPR scope. | Yes. AI Act Art 2 applies to (a) providers placing AI systems on the EU market regardless of establishment, (b) deployers established in EU, (c) providers/deployers in third countries where output is used in EU. |
| **Number of reviewed documents** | 14 reviews | 10 reviews |
| **Flagship strategy** | AI Opportunities Action Plan (Jan 2025) + Government Response + One Year On progress report (Jan 2026) | Coordinated Plan on AI 2021 Review (Apr 2021); partially superseded by AI Factories (2024) and Apply AI Strategy (2025) |
| **GPAI / foundation models** | No statutory obligations. AISI conducts voluntary safety evaluations of frontier models with developer cooperation. International Scientific Report (Bengio, May 2024) and International Network of AISIs. | Chapter V of AI Act: binding obligations on GPAI providers (10^23 FLOP indicative threshold) and GPAI-with-systemic-risk (10^25 FLOP). Voluntary GPAI Code of Practice (Jul 2025) provides structured compliance route. 24 signatories including Anthropic, Google, OpenAI, Microsoft, Mistral. |
| **Prohibited practices** | None defined. Sector regulators have discretion under existing law. | Article 5: 8 categories of prohibitions (subliminal manipulation; exploiting vulnerabilities; social scoring; predictive policing based solely on profiling; untargeted biometric scraping; emotion recognition in workplace/education; biometric categorisation; real-time remote biometric identification in public spaces — with narrow LEA exceptions). 134-page Commission Guidelines (Jul 2025) interpret each prohibition. |
| **High-risk classification** | Not defined horizontally. Sector regulators make context-specific assessments. | Article 6 + Annex III: 8 high-risk categories (biometrics, critical infrastructure, education, employment, essential services, law enforcement, migration, administration of justice). Plus Annex I safety components. |
| **Transparency / deepfake labelling** | No statutory requirement. CMA and Ofcom monitor. | Article 50 + Transparency Code (first draft Dec 2025, final Jun 2026). Two-track: provider machine-readable marking + deployer human-readable labelling. Two-level taxonomy: fully AI-generated vs AI-assisted. |
| **Serious incident reporting** | No AI-specific regime. Sector regulators operate existing incident-reporting regimes (FCA, ICO, MHRA, etc.). | Article 73 + Draft Guidance (Sep 2025). Tiered timelines: 2 days (widespread infringement / critical infrastructure), 10 days (death), 15 days (other serious incidents). |
| **Automated decision-making (ADM)** | **DUAA 2025 relaxes Article 22 UK GDPR** — replaces prohibition-with-exceptions with permit-with-safeguards model. Allows broader ADM use including sensitive categories in defined circumstances. | AI Act maintains GDPR Article 22 fully; adds high-risk obligations on top (Art 14 human oversight, Art 13 transparency). Divergence from UK. |
| **Safety institution** | **AISI** — AI Safety Institute. 100+ researchers, 240M GBP, chairs International Network of AI Safety Institutes (Bletchley → Seoul → Paris summit series). Pre-deployment evaluations of frontier models. | **AI Office** — policy and enforcement focus within DG CONNECT. Supports GPAI Code of Practice working groups, issues Commission Guidelines. No dedicated scientific evaluation function comparable to AISI. |
| **Dedicated scientific consensus process** | International Scientific Report on the Safety of Advanced AI — interim May 2024, final Jan 2025. Chaired by Yoshua Bengio. Expert Advisory Panel nominated by 30 countries + EU + UN. Secretariat at UK AISI. | No direct equivalent. Commission commissioned academic studies feed into Guidelines and Codes. |
| **Competition analysis** | CMA AI Foundation Models Initial Report (Sep 2023, 129 pages) + 7 principles. | Not centralised in AI framework; handled by DG COMP under general competition law plus DMA. |
| **Sector-regulator outputs** | FCA AI Update (Apr 2024); ICO AI & Data Protection guidance; Ofcom online safety work; MHRA AI as medical device. Each maps existing framework to 5 principles. | National Competent Authorities designated by Member States. Sectoral regulators (EBA, ESMA, EMA) coordinate with AI Office but AI-specific rule-making is horizontal via the Act. |
| **Operational guidance for public-sector AI** | AI Playbook for UK Government (Feb 2025, 118 pages, 10 principles, prescriptive ethics/security/procurement detail). | No single equivalent. AI Act applies to public-sector AI use where it meets risk thresholds. Member States produce their own public-sector guidance. |
| **Ethical framework** | 5 cross-sectoral principles (safety/security/robustness; transparency/explainability; fairness; accountability/governance; contestability/redress). | 7 HLEG requirements (human agency/oversight; technical robustness/safety; privacy/data governance; transparency; diversity/non-discrimination/fairness; societal/environmental wellbeing; accountability). Codified into AI Act high-risk obligations. |
| **Penalties** | No AI-specific penalties. Sector-specific fines via FCA, ICO (up to 17.5M GBP or 4% turnover under UK GDPR), Ofcom, CMA. | AI Act: up to €35M or 7% of global turnover for prohibited practices; up to €15M or 3% for high-risk non-compliance; up to €7.5M or 1.5% for incorrect information. |
| **Compute infrastructure investment** | Isambard-AI (Bristol), DAWN (Cambridge), EPCC (Edinburgh). 750M GBP for next national supercomputer. AIRR 20x expansion target by 2030. | EuroHPC-JU supercomputers (LUMI, Leonardo, MareNostrum5). AI Factories initiative (Sep 2024) — one-stop shops combining data, talent, compute. AI Gigafactories — 20B EUR InvestAI package (Feb 2025). |
| **Compute trajectory** | 2 ExaFLOPs (2024) → 21 ExaFLOPs (2025); 20x AIRR expansion targeting ~420 ExaFLOPs by 2030. | Multiple pre-exascale and exascale systems; exact roadmap varies by country; total investment through DEP + HE + RRF amounts to billions. |
| **AI Growth Zones / Factories** | 5 AI Growth Zones designated (2 Wales, 1 Scotland, 2 England). *Delivering AI Growth Zones* policy (CP 1440, Nov 2025) + 28.2B GBP investment. AIGZ Delivery Unit launching Jan 2026. | AI Factories initiative (10 Sep 2024) — parallel concept, EU-wide. Focus areas: healthcare, energy, automotive, transport, defence/aerospace, robotics, manufacturing, clean tech, agritech. |
| **Voluntary engagement mechanism** | AI industry safety commitments at Bletchley (2023) / Seoul (2024). Frontier AI Safety Commitments. | EU AI Pact (Sep 2024) — voluntary pledges bridging AI Act entry into force and full application. 100+ first signatories. |
| **International positioning** | Safety-convener: Bletchley (Nov 2023), Seoul (May 2024), Paris (Feb 2025) AI Summit series. International Network of AISIs (UK chairs). | Regulatory setter: AI Act is global benchmark. Brussels effect — third-country firms adopt EU standards to maintain single compliance framework. Council of Europe Framework Convention on AI (2024) reinforces EU approach. |

---

## Where the two diverge substantively

### Regulatory philosophy — the fundamental choice

The most consequential difference: **the UK is explicitly pro-innovation / non-statutory / sector-led; the EU is explicitly risk-based / statutory / horizontal.**

- **UK**: Five principles to be operationalised by sector regulators using existing legal frameworks. Post-Brexit regulatory sovereignty is framed as a competitive advantage. Statute is rejected on the grounds that it would entrench today's technical assumptions into law that cannot keep up.
- **EU**: Horizontal binding regulation classifying AI systems by risk. Different obligations for different risk tiers. GPAI treated as a distinct regulatory object with compute-based thresholds.

The UK's January 2025 Government Response committed to establish AISI as a statutory body. As of the January 2026 progress report, this remained undelivered — meaning AISI continues as a non-statutory government directorate, able to conduct voluntary evaluations but unable to compel access or impose obligations.

### ADM and DUAA 2025 — the UK-EU regulatory gap is now enacted in law

Until June 2025, the UK and EU broadly shared a common data protection framework (UK GDPR mirrors EU GDPR). The **Data (Use and Access) Act 2025** (Royal Assent June 2025) materially relaxes UK restrictions on solely automated decision-making:

- Replaces the Article 22 UK GDPR prohibition-with-exceptions with a **permit-with-safeguards model**
- Allows broader ADM including in sensitive categories under defined circumstances
- Introduces "Recognised Legitimate Interests"
- Clarifies scientific research scope

The EU AI Act is moving in the opposite direction — **strengthening** oversight for high-risk AI systems through Article 14 (human oversight), Article 13 (transparency), Article 9 (risk management system). Article 22 GDPR remains intact in the EU.

**Consequence**: a UK firm processing UK residents' data can now use automated decisions in ways that would remain prohibited under EU law. A UK firm serving EU users must still comply with Article 22 + AI Act. This creates compliance asymmetry — UK firms may find the EU regime more restrictive than the UK regime for the same underlying technology.

### GPAI / foundation models — where the approaches diverge most clearly

**UK approach**: Voluntary engagement. AISI conducts pre-deployment evaluations of frontier models with developer cooperation. The International Scientific Report synthesises cross-country scientific consensus. No statutory obligations on model providers.

**EU approach**: Binding obligations (AI Act Chapter V). Two tiers:
- **GPAI** (10^23 FLOP indicative threshold): technical documentation, copyright compliance, downstream information provision, training summary publication
- **GPAI with systemic risk** (10^25 FLOP): adversarial testing, incident reporting, cybersecurity, risk mitigation for four specified systemic risks (CBRN, Loss of Control, Cyber Offence, Harmful Manipulation)

The Commission GPAI Guidelines (Jul 2025) and GPAI Code of Practice (Jul 2025) operationalise these obligations. The Code has 24 signatories as of October 2025 including most major model providers.

**Consequence for UK-based model providers**: If the model is placed on the EU market, Chapter V applies regardless of where the model was developed. UK AISI evaluation participation does not discharge AI Act obligations.

### Prohibited practices — EU has 8, UK has none

The EU AI Act (Article 5) prohibits 8 categories of AI practices. The 134-page Commission Guidelines (Jul 2025) interpret each prohibition in detail with worked examples. These prohibitions apply from 2 February 2025 and carry penalties of up to €35M or 7% of global turnover.

The UK has no equivalent. Prohibitions operate through existing law (Equality Act for discrimination; GDPR for privacy; DPA for law enforcement; PECR for marketing). Sector regulators decide case-by-case.

**Specific cases where UK vs EU diverges**:
- **Social scoring by public authorities**: EU prohibits; UK has no direct prohibition (sector-specific rules apply)
- **Real-time biometric identification in public spaces**: EU prohibits with narrow LEA exceptions; UK practice governed by DPA 2018 + sector-specific rules (policing, retail)
- **Emotion recognition in workplace/education**: EU prohibits; UK has no direct prohibition (ICO guidance + Equality Act apply)
- **Untargeted biometric scraping**: EU prohibits; UK ICO has enforcement action against Clearview AI but no statutory prohibition

### Transparency and deepfake labelling — EU has Article 50 + Code; UK has principles

EU: Article 50 imposes binding transparency obligations. The Transparency Code (Dec 2025 first draft) specifies:
- Provider machine-readable marking (metadata, watermarks, fingerprinting)
- Deployer human-readable labelling (two-level taxonomy: fully AI-generated vs AI-assisted)
- Modality-specific rules (real-time video, non-real-time video, multimodal, image, audio with <30s/longer thresholds)
- Editorial review exception for AI-generated text on matters of public interest

UK: No statutory AI-generated content labelling requirement. Ofcom's Online Safety Act work addresses some overlapping concerns for illegal content. CMA monitors under competition law.

### Serious incident reporting — EU has Article 73; UK has sectoral regimes

EU: Article 73 + Sep 2025 Draft Guidance establish tiered timelines:
- 2 days — widespread infringement of fundamental rights or disruption of critical infrastructure
- 10 days — death
- 15 days — other serious incidents (serious harm to property/environment or serious/irreversible disruption of critical infrastructure)

UK: No AI-specific incident reporting regime. Sectoral reporting applies (FCA — for financial services; ICO — for personal data breaches; MHRA — for medical devices; CPR — for products generally).

### Penalties — EU is harmonised and significant

EU: Up to €35M or 7% of global turnover (prohibited practices); €15M or 3% (high-risk); €7.5M or 1.5% (incorrect information). Harmonised across Member States.

UK: Sector-specific. ICO under UK GDPR up to 17.5M GBP or 4% turnover. FCA penalties can be substantial but depend on specific breach. No AI-specific penalty regime.

**Consequence**: For the same AI compliance failure, EU penalties may significantly exceed UK penalties. This asymmetry reinforces the compliance floor effect — firms serving both markets tend to adopt EU standards globally.

### International positioning — complementary rather than competitive

The UK has deliberately positioned itself as the **safety convener** — Bletchley (2023), Seoul (2024), Paris (2025) summits; International Network of AISIs (UK chairs); International Scientific Report.

The EU has positioned itself as the **regulatory setter** — AI Act as global benchmark; Brussels effect induces third-country adoption; Council of Europe Framework Convention reinforces the approach.

These positions are not strictly competitive — the UK participates in EU regulatory consultations through industry stakeholders; the EU participates in international summits through Commission representation. But the division of labour is clear: UK on scientific evaluation and international coordination; EU on legal architecture and binding standards.

---

## Where they converge

Despite the philosophical difference, the UK and EU agree on:

1. **Risk-based framing**. Both acknowledge that AI risks vary by context; both privilege responses proportionate to risk magnitude. The disagreement is on how to enforce proportionality (statute vs sector-regulator discretion).

2. **Human oversight.** UK Playbook and AI Act Art 14 both require human oversight for consequential decisions, though specification differs. UK Playbook has prescriptive DPIA requirements; AI Act has high-risk obligations.

3. **Fundamental rights as anchor.** Both frameworks ground AI governance in fundamental rights. EU via EU Charter; UK via Human Rights Act 1998 and common-law protections.

4. **Transparency.** Both require AI systems to be transparent to users and affected persons; EU operationalises via Article 50 + Codes; UK via principles + sector-regulator enforcement.

5. **GPAI concern.** Both recognise foundation models as a distinct regulatory challenge. UK via AISI evaluations; EU via Chapter V.

6. **Skills and literacy.** Both target AI literacy. UK via Digital Education Action Plan equivalents; EU via Art 4 (applicable Feb 2025) and the AI Pact.

7. **Investment in compute and research.** Both prioritise sovereign compute capacity and AI research ecosystems. UK via AIRR + AIGZ; EU via EuroHPC + AI Factories.

8. **International coordination.** UK-EU dialogue continues on frontier AI safety; both participate in GPAI, OECD AI Governance, G7 Hiroshima Process, Council of Europe Framework Convention (the EU is a signatory; the UK is a signatory).

---

## Strategic implications for UK-based firms serving EU clients

1. **Compliance floor is the EU floor.** UK firms placing AI systems on the EU market or whose outputs are used in EU must comply with the AI Act regardless of UK establishment. The EU floor is higher than the UK floor for most obligations; building to the EU floor satisfies UK requirements but not vice versa.

2. **GPAI providers face binding EU obligations regardless of UK position.** UK-based frontier model providers who place models on the EU market must comply with Chapter V. The GPAI Code of Practice provides the structured compliance route.

3. **AI Pact signing is low-cost symbolic value.** The three core pledges align with AI Act preparation regardless of whether the firm is UK or EU-based. Signing provides EU stakeholder credibility.

4. **Watch the transparency gap.** UK firms producing AI-generated content for EU users must comply with Article 50 + Transparency Code from August 2026. No equivalent UK obligation exists. This is a compliance area where UK-EU divergence is material.

5. **ADM divergence creates jurisdictional choice architecture.** UK firms processing UK residents' data can use the DUAA flexibilities; same firms processing EU residents' data cannot. This may drive data localisation decisions.

6. **Monitor enforcement trajectory.** EU AI Act enforcement ramps from August 2026. Early cases will establish interpretive precedent. UK firms should monitor EU enforcement as a leading indicator of their own compliance risk.

7. **Brussels effect in practice.** Large UK firms (Google DeepMind, ARM, etc.) will typically adopt EU standards globally because maintaining divergent compliance frameworks is costly. This creates a de facto EU-alignment among tier-1 UK AI firms even though the UK government rejects EU alignment at policy level.

8. **UK-EU regulatory alignment risk management.** The DUAA 2025 is the first substantive UK-EU AI regulatory divergence. Future divergence (e.g., UK frontier AI legislation, EU secondary instruments) will increase compliance complexity. Firms should build regulatory tracking into their governance processes.

---

## Summary

The UK and EU have chosen fundamentally different architectures for AI governance. Neither is strictly superior; both have recognisable trade-offs.

- **UK trades legal clarity for flexibility.** Sector regulators can respond to specific contexts but firms operate without horizontal certainty. The absence of statutory obligations may be attractive for innovation but creates enforcement uncertainty.

- **EU trades flexibility for legal clarity.** Binding obligations create compliance certainty but risk misfit with emerging technologies (the AI Act was drafted before GPAI became prominent and has needed extensive secondary interpretation).

For firms operating across both jurisdictions, the practical reality is that **EU obligations set the compliance floor**. UK firms serving EU clients must meet the EU standard; the UK standard is typically less demanding. The reverse is not true — EU firms serving UK clients generally find UK compliance easier than EU compliance.

For **policy analysts and clients asking which approach is "better"**, the honest answer is that the question is not well-formed. The UK's approach fits an economy seeking to differentiate from its largest trading bloc through regulatory arbitrage; the EU's approach fits a single market seeking to create a uniform regulatory environment across 27 Member States. Neither model transplants cleanly to the other context.

For **UK-based firms and their advisors**, the practical guidance is:

1. Treat the EU AI Act as the primary compliance framework if you serve EU users.
2. Use UK regulatory flexibility where it applies and creates competitive advantage — but track the compliance cost of maintaining divergent postures.
3. Build regulatory change tracking for both UK and EU developments, because divergence will increase over the coming years.
4. Engage with both AISI (voluntarily) and EU AI Office (through Pact, Codes, consultations) to shape how secondary instruments develop.

---

## Source reviews

**UK reviews** (14 documents): see [`../UK/analysis/review-claude/`](../UK/analysis/review-claude/)

Key documents referenced in this comparison:
- [Pro-Innovation White Paper (Mar 2023)](../UK/analysis/review-claude/03-pro-innovation-white-paper.md)
- [Pro-Innovation Regulation Consultation Response (Feb 2024)](../UK/analysis/review-claude/02-pro-innovation-regulation-consultation-response.md)
- [AISI Approach to Evaluations (Feb 2024)](../UK/analysis/review-claude/08-aisi-approach-to-evaluations.md)
- [International Scientific Report on Safety of Advanced AI (May 2024)](../UK/analysis/review-claude/10-international-scientific-report-safety-advanced-ai.md)
- [AI Opportunities Action Plan (Jan 2025)](../UK/analysis/review-claude/01-ai-opportunities-action-plan.md)
- [AI Playbook for UK Government (Feb 2025)](../UK/analysis/review-claude/07-ai-playbook-uk-government.md)
- [Data (Use and Access) Act 2025 (Jun 2025)](../UK/analysis/review-claude/14-data-use-and-access-act.md)
- [FCA AI Update (Apr 2024)](../UK/analysis/review-claude/12-fca-ai-update.md)
- [CMA AI Foundation Models Initial Report (Sep 2023)](../UK/analysis/review-claude/09-cma-ai-foundation-models-initial-report.md)

**EU reviews** (10 documents): see [`../EU/analysis/review-claude/`](../EU/analysis/review-claude/)

All documents referenced:
- [Ethics Guidelines for Trustworthy AI (Apr 2019)](../EU/analysis/review-claude/08-ethics-guidelines-trustworthy-ai-2019.md)
- [Coordinated Plan on AI 2021 Review (Apr 2021)](../EU/analysis/review-claude/09-coordinated-plan-on-ai-2021-review.md)
- [EU AI Act (Jul 2024)](../EU/analysis/review-claude/01-eu-ai-act.md)
- [EU AI Pact (Sep 2024)](../EU/analysis/review-claude/10-eu-ai-pact.md)
- [Guidelines on Definition of AI System (Jul 2025)](../EU/analysis/review-claude/02-guidelines-definition-ai-system.md)
- [Guidelines on Prohibited AI Practices (Jul 2025)](../EU/analysis/review-claude/03-guidelines-prohibited-ai-practices.md)
- [Commission GPAI Guidelines (Jul 2025)](../EU/analysis/review-claude/04-commission-gpai-guidelines.md)
- [GPAI Code of Practice (Jul 2025)](../EU/analysis/review-claude/05-gpai-code-of-practice.md)
- [Serious Incident Reporting Guidance (Sep 2025)](../EU/analysis/review-claude/06-serious-incident-reporting-guidance-and-template.md)
- [Transparency Code for AI-Generated Content (Dec 2025)](../EU/analysis/review-claude/07-transparency-code-ai-generated-content.md)

**Related comparison**: [UK vs Scotland AI Governance Comparison](../UK/analysis/UK-Scotland-comparison.md)
