# Glossary: AI Governance Terminology Across Jurisdictions

Different jurisdictions use different terms for similar concepts — and sometimes the same term for different concepts. This glossary maps the key terminology across the six jurisdictions analysed in this repo. For the UAE, note that the financial free zones (DIFC, ADGM) legislate independently: several entries below distinguish federal/onshore UAE from the DIFC, whose Regulation 10 borrows EU AI Act vocabulary directly.

---

## AI system / AI

| Jurisdiction | Term | Definition summary |
|-------------|------|-------------------|
| **EU** | AI system (Article 3(1)) | Machine-based system designed to operate with varying levels of autonomy, that may exhibit adaptiveness and that infers, from input, how to generate outputs (predictions, content, recommendations, decisions) that can influence physical or virtual environments |
| **USA** | AI (15 U.S.C. 9401(3)) | Machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations, or decisions influencing real or virtual environments |
| **UK** | No statutory definition | Pro-Innovation White Paper uses a broad working definition; sector regulators apply context-specific interpretations |
| **Singapore** | AI | "A set of technologies that seek to simulate human traits such as knowledge, reasoning, problem solving, perception, learning and planning" (Model Framework 2020) |
| **Switzerland** | No statutory definition | FINMA references the OECD definition approach; no domestic statutory definition |
| **UAE** | No single federal statutory definition | UAE Charter and CBUAE guidance define AI/GenAI/ML descriptively. **DIFC Regulation 10** defines a "System" (machine-based system operating autonomously or semi-autonomously that processes personal data and generates output) as a binding gateway term, adapted from the OECD guidelines and the EU AI Act |

**Key differences**: The EU definition is the most legally precise (it is the gateway to the entire AI Act). The US statutory definition is broader. The UK, Singapore, and Switzerland deliberately avoid binding definitions to maintain flexibility. The UAE is split: no binding federal definition, but the DIFC's "System" is a binding definition modelled on the EU's.

---

## Provider / developer

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | Provider | Natural or legal person that develops an AI system or GPAI model, or has one developed, and places it on the market or puts it into service under its own name or trademark |
| **USA** | Developer | Used loosely; no statutory definition for AI. NIST AI RMF uses "AI actors" across the lifecycle |
| **UK** | Developer | Used in policy documents; no statutory definition |
| **Singapore** | AI Solution Provider | Develops AI solutions or application systems that make use of AI technology (Model Framework 2020) |
| **Switzerland** | No specific term | FINMA uses "supervised institutions" for entities using AI in financial services |
| **UAE** | Provider (DIFC only) | **DIFC Regulation 10** defines "Provider": a person that develops a System, or has one developed, to make it available to Operators or Deployers. Borrowed from the EU AI Act. No federal equivalent |

**Key difference**: The EU's "provider" has specific legal obligations attached. Most other jurisdictions use "developer" or "provider" descriptively without binding consequences; the exception is the UAE's DIFC, where "Provider" is a defined role under binding Regulation 10.

---

## Deployer / user

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | Deployer | Natural or legal person that uses an AI system under its authority, except where the system is used in a personal non-professional activity |
| **USA** | No specific term | NIST AI RMF refers to "AI actors" including those who deploy or operate AI |
| **UK** | No specific term | Policy documents refer to "users" or "organisations using AI" |
| **Singapore** | Organisation | Companies or entities that adopt or deploy AI solutions in their operations (Model Framework 2020) |
| **Switzerland** | Supervised institution (financial sector) | FINMA's term for entities subject to its AI governance guidance |
| **UAE** | Deployer / Operator (DIFC only) | **DIFC Regulation 10** defines "Deployer" (the person under whose authority or for whose benefit a System operates, made accountable like a controller) and "Operator" (runs the System for the Deployer, like a processor). Both borrowed from the EU AI Act. No federal equivalent |

**Key difference**: The EU's "deployer" has specific legal obligations (human oversight, monitoring, log-keeping for high-risk systems, transparency disclosures). Most jurisdictions do not create a distinct legal category for deployers; the exception is the UAE's DIFC, which makes the "Deployer" of an AI system accountable under binding Regulation 10.

---

## GPAI / foundation model

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | General-purpose AI model (GPAI) | AI model trained with a large amount of data using self-supervision at scale, that displays significant generality and is capable of competently performing a wide range of distinct tasks. Classified by compute: 10²³ FLOP (general), 10²⁵ FLOP (systemic risk) |
| **USA** | Foundation model / frontier model | No binding definition. EO 14110 (revoked) used "dual-use foundation model" with compute thresholds. NIST GenAI Profile addresses "generative AI" broadly |
| **UK** | Foundation model | Used by CMA, AISI, and policy documents. No statutory definition. AISI evaluates "frontier models" (most capable) |
| **Singapore** | Foundation model / generative AI | GenAI Framework (2024) uses "generative AI" and references "foundation models" without compute-based classification |
| **Switzerland** | No specific term | Not addressed in Federal Council decision or FINMA guidance |
| **UAE** | GenAI (descriptive) | CBUAE guidance defines "GenAI" (models that understand and generate text, audio and images, including large language models). No compute thresholds or systemic-risk tiers. Sovereign-model ambitions (TII Falcon, MBZUAI) sit in industrial policy, not regulation |

**Key difference**: Only the EU creates binding legal obligations specifically for GPAI model providers, with compute-based thresholds for classification. The UAE, like the others, defines generative AI only descriptively.

---

## Risk classification

| Jurisdiction | Approach | Categories |
|-------------|----------|-----------|
| **EU** | Statutory risk tiers | Prohibited / High-risk / Limited risk / Minimal risk (plus GPAI with or without systemic risk) |
| **USA** | No federal classification | OMB M-25-21 uses "high-impact AI" for federal government use. NIST AI RMF uses organisation-defined risk tolerance. Colorado AI Act uses "high-risk" for state level |
| **UK** | Context-specific | Sector regulators assess risk in context; no predetermined categories. Five principles applied proportionately |
| **Singapore** | Probability-severity matrix | Model Framework 2020 proposes a 2×2 matrix (probability × severity of harm) to determine human oversight level. No binding categories |
| **Switzerland** | Sector-specific | FINMA applies materiality-based risk assessment within financial services. No horizontal classification |
| **UAE** | Two domain-specific concepts | No horizontal classification. **DIFC Regulation 10** uses "high-risk processing" (triggers certification + an Autonomous Systems Officer); **CBUAE** guidance uses "high-impact decision" (a determination materially affecting a customer's access to a financial product, e.g. a loan or insurance claim). Otherwise contextual |

**Key difference**: The EU pre-classifies by category (Annex III); all others assess risk contextually. This is arguably the single biggest philosophical divergence in global AI governance. The UAE has no horizontal tiers but does use binding domain-specific risk triggers (DIFC high-risk processing).

---

## Human oversight models

| Term | EU AI Act | Singapore Model Framework | NIST AI RMF | UAE (CBUAE) |
|------|-----------|--------------------------|-------------|-------------|
| **Human-in-the-loop (HITL)** | Article 14 references; human intervention in every decision cycle | Defined; human retains full control, AI provides recommendations | Referenced in context of human-AI interaction | AI recommends; a human decision-maker retains full authority to approve or reject |
| **Human-on-the-loop (HOTL)** | Article 14 references; human monitoring with ability to intervene | "Human-over-the-loop" — supervisory role with ability to take over | Referenced | AI works autonomously for routine tasks; a human monitors and can intervene |
| **Human-out-of-the-loop (HOOTL)** | Not a compliance option for high-risk systems | Defined; no human oversight, AI has full control (acceptable for low-risk uses) | Not explicitly named but acknowledged in risk discussion | Only for low-risk, non-material processes; fully automated credit/insurance decisions are unlikely to meet supervisory expectations |

**Key difference**: The EU requires human oversight for high-risk systems (HITL or HOTL). Singapore's framework allows HOOTL for low-severity, low-probability applications. The terminology originated in Singapore's 2019/2020 framework and was subsequently adopted by the EU, and now, near-verbatim, by the UAE's CBUAE guidance.

---

## Prohibited practices

| Jurisdiction | Prohibited AI practices |
|-------------|------------------------|
| **EU** | 8 categories under Article 5: subliminal manipulation, vulnerability exploitation, social scoring, predictive policing (profiling-only), untargeted biometric scraping, emotion recognition in workplace/education, biometric categorisation for sensitive attributes, real-time remote biometric identification in public spaces |
| **USA** | None at federal level. State-level varies |
| **UK** | None defined horizontally. Sector regulators enforce under existing law (Equality Act, GDPR, etc.) |
| **Singapore** | None |
| **Switzerland** | None. Council of Europe Convention may require some protections; FDJP bill (due end 2026) may address |
| **UAE** | None defined horizontally. Specific misuses (e.g. deepfakes used for fraud or defamation) are caught by the cybercrime law (Decree-Law 34/2021), not an AI prohibited-practices regime |

---

## Incident reporting

| Jurisdiction | AI-specific incident reporting |
|-------------|-------------------------------|
| **EU** | Article 73: serious incidents reported to market surveillance authorities. Tiered timelines: 2 days (widespread fundamental rights infringement / critical infrastructure disruption), 10 days (death), 15 days (other serious incidents) |
| **USA** | No federal AI-specific regime. OMB M-25-21 requires agencies to discontinue non-compliant high-impact AI. Sector-specific reporting applies (FDA, FTC) |
| **UK** | No AI-specific regime. Sector regulators operate existing incident reporting (FCA, ICO, MHRA) |
| **Singapore** | GenAI Framework recommends incident reporting processes. Draws parallel with CVE vulnerability reporting (90-day patch window). References EU AI Act approach |
| **Switzerland** | No AI-specific regime. FINMA existing supervisory reporting applies for financial services |
| **UAE** | No AI-specific regime. Data-breach reporting under the federal PDPL, DIFC and ADGM data-protection laws; sector reporting via CBUAE/DFSA/FSRA; CBUAE guidance expects LFIs to detect, report and remediate AI performance issues |

---

## Penalties

| Jurisdiction | AI-specific penalties |
|-------------|----------------------|
| **EU** | Up to €35M or 7% global turnover (prohibited practices); €15M / 3% (high-risk); €7.5M / 1.5% (incorrect information) |
| **USA** | No federal AI-specific penalties. Agency-specific enforcement under existing authority. State-level varies |
| **UK** | No AI-specific penalties. ICO under UK GDPR up to £17.5M or 4% turnover. Sector-specific penalties via FCA, Ofcom, CMA |
| **Singapore** | No AI-specific penalties. PDPA penalties (up to S$1M). Sector-specific via MAS |
| **Switzerland** | No AI-specific penalties. FINMA supervisory measures. revFADP penalties (up to CHF 250,000 for individuals) |
| **UAE** | No AI-specific penalties. Data-protection penalties under the federal PDPL and the DIFC / ADGM data-protection regimes (the DIFC Commissioner can impose fines); sector and AML/CFT penalties via the relevant regulators |

---

## Voluntary frameworks

| Jurisdiction | Primary voluntary AI framework |
|-------------|-------------------------------|
| **EU** | GPAI Code of Practice (Jul 2025, 24 signatories); EU AI Pact (Sep 2024, 100+ signatories); Transparency Code (Dec 2025 first draft) |
| **USA** | NIST AI Risk Management Framework (Jan 2023); four functions: Govern, Map, Measure, Manage |
| **UK** | Five cross-sectoral principles (safety, transparency, fairness, accountability, contestability); AI Playbook for government |
| **Singapore** | Model AI Governance Framework stack (2020 → GenAI 2024 → Agentic AI 2026); AI Verify testing toolkit |
| **Switzerland** | Council of Europe AI Convention (signed Feb 2025); FINMA Guidance 08/2024 for financial services |
| **UAE** | UAE Charter for the Development and Use of AI (2024, 12 principles); Dubai AI Ethics Principles and Guidelines (2019); CBUAE AI/ML Guidance Note (2026); joint Enabling Technologies Guidelines (2021) |

---

## Safety institutions

| Jurisdiction | Dedicated AI safety body |
|-------------|-------------------------|
| **EU** | AI Office (within DG CONNECT) — policy and enforcement focus; no dedicated scientific evaluation function |
| **USA** | US AISI (at NIST) — established under Biden; status uncertain under Trump; national security evaluation focus |
| **UK** | AISI — AI Safety Institute. 100+ researchers, £240M. Frontier model evaluations. Chairs International Network of AI Safety Institutes |
| **Singapore** | Digital Trust Centre (S$50M) — R&D for trustworthy AI; AI Verify Foundation — governance testing tools |
| **Switzerland** | None |
| **UAE** | No dedicated frontier-safety evaluation body. Federal AI Office (coordination) and Abu Dhabi's AI and Advanced Technology Council (AIATC); world-first Minister of State for AI (2017); research via MBZUAI and TII |

---

## Extraterritorial reach

| Jurisdiction | Does AI governance apply outside its borders? |
|-------------|----------------------------------------------|
| **EU** | Yes — Article 2 applies to non-EU providers whose systems are placed on EU market or whose outputs are used in EU. Enforceability depends on EU presence (see enforcement realism notes in comparisons) |
| **USA** | No — federal AI governance applies domestically only |
| **UK** | No — DUAA 2025 and sector-regulator frameworks apply to UK-established entities and UK data subjects |
| **Singapore** | No — voluntary frameworks apply to organisations deploying AI in Singapore |
| **Switzerland** | No — domestic frameworks apply within Switzerland; Swiss firms serving EU comply with AI Act directly |
| **UAE** | Largely territorial: the federal PDPL applies to processing in the UAE; DIFC and ADGM rules apply to entities established in those free zones. No EU-style market-reach extraterritoriality |
