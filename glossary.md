# Glossary: AI Governance Terminology Across Jurisdictions

Different jurisdictions use different terms for similar concepts — and sometimes the same term for different concepts. This glossary maps the key terminology across the five jurisdictions analysed in this repo.

---

## AI system / AI

| Jurisdiction | Term | Definition summary |
|-------------|------|-------------------|
| **EU** | AI system (Article 3(1)) | Machine-based system designed to operate with varying levels of autonomy, that may exhibit adaptiveness and that infers, from input, how to generate outputs (predictions, content, recommendations, decisions) that can influence physical or virtual environments |
| **USA** | AI (15 U.S.C. 9401(3)) | Machine-based system that can, for a given set of human-defined objectives, make predictions, recommendations, or decisions influencing real or virtual environments |
| **UK** | No statutory definition | Pro-Innovation White Paper uses a broad working definition; sector regulators apply context-specific interpretations |
| **Singapore** | AI | "A set of technologies that seek to simulate human traits such as knowledge, reasoning, problem solving, perception, learning and planning" (Model Framework 2020) |
| **Switzerland** | No statutory definition | FINMA references the OECD definition approach; no domestic statutory definition |

**Key differences**: The EU definition is the most legally precise (it is the gateway to the entire AI Act). The US statutory definition is broader. The UK, Singapore, and Switzerland deliberately avoid binding definitions to maintain flexibility.

---

## Provider / developer

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | Provider | Natural or legal person that develops an AI system or GPAI model, or has one developed, and places it on the market or puts it into service under its own name or trademark |
| **USA** | Developer | Used loosely; no statutory definition for AI. NIST AI RMF uses "AI actors" across the lifecycle |
| **UK** | Developer | Used in policy documents; no statutory definition |
| **Singapore** | AI Solution Provider | Develops AI solutions or application systems that make use of AI technology (Model Framework 2020) |
| **Switzerland** | No specific term | FINMA uses "supervised institutions" for entities using AI in financial services |

**Key difference**: The EU's "provider" has specific legal obligations attached. Other jurisdictions use "developer" or "provider" descriptively without binding consequences.

---

## Deployer / user

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | Deployer | Natural or legal person that uses an AI system under its authority, except where the system is used in a personal non-professional activity |
| **USA** | No specific term | NIST AI RMF refers to "AI actors" including those who deploy or operate AI |
| **UK** | No specific term | Policy documents refer to "users" or "organisations using AI" |
| **Singapore** | Organisation | Companies or entities that adopt or deploy AI solutions in their operations (Model Framework 2020) |
| **Switzerland** | Supervised institution (financial sector) | FINMA's term for entities subject to its AI governance guidance |

**Key difference**: The EU's "deployer" has specific legal obligations (human oversight, monitoring, log-keeping for high-risk systems, transparency disclosures). Other jurisdictions do not create a distinct legal category for deployers.

---

## GPAI / foundation model

| Jurisdiction | Term | Meaning |
|-------------|------|---------|
| **EU** | General-purpose AI model (GPAI) | AI model trained with a large amount of data using self-supervision at scale, that displays significant generality and is capable of competently performing a wide range of distinct tasks. Classified by compute: 10²³ FLOP (general), 10²⁵ FLOP (systemic risk) |
| **USA** | Foundation model / frontier model | No binding definition. EO 14110 (revoked) used "dual-use foundation model" with compute thresholds. NIST GenAI Profile addresses "generative AI" broadly |
| **UK** | Foundation model | Used by CMA, AISI, and policy documents. No statutory definition. AISI evaluates "frontier models" (most capable) |
| **Singapore** | Foundation model / generative AI | GenAI Framework (2024) uses "generative AI" and references "foundation models" without compute-based classification |
| **Switzerland** | No specific term | Not addressed in Federal Council decision or FINMA guidance |

**Key difference**: Only the EU creates binding legal obligations specifically for GPAI model providers, with compute-based thresholds for classification.

---

## Risk classification

| Jurisdiction | Approach | Categories |
|-------------|----------|-----------|
| **EU** | Statutory risk tiers | Prohibited / High-risk / Limited risk / Minimal risk (plus GPAI with or without systemic risk) |
| **USA** | No federal classification | OMB M-25-21 uses "high-impact AI" for federal government use. NIST AI RMF uses organisation-defined risk tolerance. Colorado AI Act uses "high-risk" for state level |
| **UK** | Context-specific | Sector regulators assess risk in context; no predetermined categories. Five principles applied proportionately |
| **Singapore** | Probability-severity matrix | Model Framework 2020 proposes a 2×2 matrix (probability × severity of harm) to determine human oversight level. No binding categories |
| **Switzerland** | Sector-specific | FINMA applies materiality-based risk assessment within financial services. No horizontal classification |

**Key difference**: The EU pre-classifies by category (Annex III); all others assess risk contextually. This is arguably the single biggest philosophical divergence in global AI governance.

---

## Human oversight models

| Term | EU AI Act | Singapore Model Framework | NIST AI RMF |
|------|-----------|--------------------------|-------------|
| **Human-in-the-loop (HITL)** | Article 14 references; human intervention in every decision cycle | Defined; human retains full control, AI provides recommendations | Referenced in context of human-AI interaction |
| **Human-on-the-loop (HOTL)** | Article 14 references; human monitoring with ability to intervene | "Human-over-the-loop" — supervisory role with ability to take over | Referenced |
| **Human-out-of-the-loop (HOOTL)** | Not a compliance option for high-risk systems | Defined; no human oversight, AI has full control (acceptable for low-risk uses) | Not explicitly named but acknowledged in risk discussion |

**Key difference**: The EU requires human oversight for high-risk systems (HITL or HOTL). Singapore's framework allows HOOTL for low-severity, low-probability applications. The terminology originated in Singapore's 2019/2020 framework and was subsequently adopted by the EU.

---

## Prohibited practices

| Jurisdiction | Prohibited AI practices |
|-------------|------------------------|
| **EU** | 8 categories under Article 5: subliminal manipulation, vulnerability exploitation, social scoring, predictive policing (profiling-only), untargeted biometric scraping, emotion recognition in workplace/education, biometric categorisation for sensitive attributes, real-time remote biometric identification in public spaces |
| **USA** | None at federal level. State-level varies |
| **UK** | None defined horizontally. Sector regulators enforce under existing law (Equality Act, GDPR, etc.) |
| **Singapore** | None |
| **Switzerland** | None. Council of Europe Convention may require some protections; FDJP bill (due end 2026) may address |

---

## Incident reporting

| Jurisdiction | AI-specific incident reporting |
|-------------|-------------------------------|
| **EU** | Article 73: serious incidents reported to market surveillance authorities. Tiered timelines: 2 days (widespread fundamental rights infringement / critical infrastructure disruption), 10 days (death), 15 days (other serious incidents) |
| **USA** | No federal AI-specific regime. OMB M-25-21 requires agencies to discontinue non-compliant high-impact AI. Sector-specific reporting applies (FDA, FTC) |
| **UK** | No AI-specific regime. Sector regulators operate existing incident reporting (FCA, ICO, MHRA) |
| **Singapore** | GenAI Framework recommends incident reporting processes. Draws parallel with CVE vulnerability reporting (90-day patch window). References EU AI Act approach |
| **Switzerland** | No AI-specific regime. FINMA existing supervisory reporting applies for financial services |

---

## Penalties

| Jurisdiction | AI-specific penalties |
|-------------|----------------------|
| **EU** | Up to €35M or 7% global turnover (prohibited practices); €15M / 3% (high-risk); €7.5M / 1.5% (incorrect information) |
| **USA** | No federal AI-specific penalties. Agency-specific enforcement under existing authority. State-level varies |
| **UK** | No AI-specific penalties. ICO under UK GDPR up to £17.5M or 4% turnover. Sector-specific penalties via FCA, Ofcom, CMA |
| **Singapore** | No AI-specific penalties. PDPA penalties (up to S$1M). Sector-specific via MAS |
| **Switzerland** | No AI-specific penalties. FINMA supervisory measures. revFADP penalties (up to CHF 250,000 for individuals) |

---

## Voluntary frameworks

| Jurisdiction | Primary voluntary AI framework |
|-------------|-------------------------------|
| **EU** | GPAI Code of Practice (Jul 2025, 24 signatories); EU AI Pact (Sep 2024, 100+ signatories); Transparency Code (Dec 2025 first draft) |
| **USA** | NIST AI Risk Management Framework (Jan 2023); four functions: Govern, Map, Measure, Manage |
| **UK** | Five cross-sectoral principles (safety, transparency, fairness, accountability, contestability); AI Playbook for government |
| **Singapore** | Model AI Governance Framework stack (2020 → GenAI 2024 → Agentic AI 2026); AI Verify testing toolkit |
| **Switzerland** | Council of Europe AI Convention (signed Feb 2025); FINMA Guidance 08/2024 for financial services |

---

## Safety institutions

| Jurisdiction | Dedicated AI safety body |
|-------------|-------------------------|
| **EU** | AI Office (within DG CONNECT) — policy and enforcement focus; no dedicated scientific evaluation function |
| **USA** | US AISI (at NIST) — established under Biden; status uncertain under Trump; national security evaluation focus |
| **UK** | AISI — AI Safety Institute. 100+ researchers, £240M. Frontier model evaluations. Chairs International Network of AI Safety Institutes |
| **Singapore** | Digital Trust Centre (S$50M) — R&D for trustworthy AI; AI Verify Foundation — governance testing tools |
| **Switzerland** | None |

---

## Extraterritorial reach

| Jurisdiction | Does AI governance apply outside its borders? |
|-------------|----------------------------------------------|
| **EU** | Yes — Article 2 applies to non-EU providers whose systems are placed on EU market or whose outputs are used in EU. Enforceability depends on EU presence (see enforcement realism notes in comparisons) |
| **USA** | No — federal AI governance applies domestically only |
| **UK** | No — DUAA 2025 and sector-regulator frameworks apply to UK-established entities and UK data subjects |
| **Singapore** | No — voluntary frameworks apply to organisations deploying AI in Singapore |
| **Switzerland** | No — domestic frameworks apply within Switzerland; Swiss firms serving EU comply with AI Act directly |
