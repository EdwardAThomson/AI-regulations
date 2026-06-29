# UAE — AI Governance in Financial Services

A practical map of how AI is governed for financial institutions in the UAE. This is the most
developed corner of the UAE's AI landscape, and it is unusual in one respect: which rules
apply depends entirely on **where the firm is licensed**. The UAE runs three parallel financial
jurisdictions, each with its own regulator, its own data-protection law, and its own posture on AI.

> Not legal advice. Working analysis assisted by AI; verify against primary sources before
> relying on it. Some items below (notably the CBUAE Feb 2026 guidance) are very recent and
> should be checked against the issued text.

---

## The single most important question

**Which regulator licenses the client?** The answer determines the entire AI compliance stack.

| Where the firm is licensed | Prudential / conduct regulator | Data-protection regime | AI-specific instrument |
|----------------------------|-------------------------------|------------------------|------------------------|
| **Onshore UAE** (mainland) | Central Bank of the UAE (CBUAE) for banks/insurers/finance companies; Securities and Commodities Authority (SCA) for capital markets | Federal PDPL (Decree-Law 45/2021) | CBUAE Guidance Note on AI/ML (Feb 2026) + joint Enabling Technologies Guidelines (2021) |
| **DIFC** (Dubai free zone) | Dubai Financial Services Authority (DFSA) | DIFC Data Protection Law 5/2020 + **Regulation 10** | No AI-specific binding rules from DFSA (technology-neutral); but **DIFC Regulation 10 binds** + joint 2021 Guidelines (DFSA is a signatory) |
| **ADGM** (Abu Dhabi free zone) | Financial Services Regulatory Authority (FSRA) | ADGM Data Protection Regulations 2021 | No AI-specific binding rules from FSRA (technology-neutral); joint 2021 Guidelines (FSRA is a signatory) |

DIFC and ADGM are independent common-law jurisdictions. A firm "in Dubai" could be onshore
(CBUAE/SCA) or in the DIFC (DFSA): the regimes are different and do not substitute for each other.

---

## Track 1 — Onshore: the CBUAE

### CBUAE Guidance Note on Responsible Use of AI and ML (23 February 2026)

The Central Bank's flagship AI instrument. Full title: *Guidance Note on the Consumer
Protection and Responsible Adoption and Use of Artificial Intelligence and Machine Learning by
Licensed Financial Institutions in the U.A.E.*

- **Status:** Non-binding guidance, but it "clearly signals the direction of supervisory
  expectations" and is expected to form part of supervisory dialogue and regulatory assessment.
  Treat it as de-facto mandatory for a CBUAE-supervised firm.
- **Scope:** All CBUAE-licensed financial institutions (LFIs): banks, insurers, finance
  companies, exchange houses. Broad AI definition covering machine learning and generative AI
  (including large language models).
- **Reads with:** the UAE Charter for the Development and Use of AI (2024), the National Strategy
  for AI, the joint Enabling Technologies Guidelines (2021), and the CBUAE Model Management
  Standards (MMS); governance, usage and validation of AI "should follow the principles of the MMS".

**Organising concept: the "high-impact decision."** Defined in the Note as any determination by an
LFI using AI that materially affects a customer's access to financial products or services (the
examples given are a loan application and an insurance claim). The higher the impact, the more
governance and transparency is expected.

**Ten sections** (grounded in the issued text, `CBUAE-Guidance-Responsible-AI-ML-Feb-2026.pdf`):

1. **Definitions** — AI, GenAI, ML, high-impact decision, MMS.
2. **Governance and accountability** — documented framework proportionate to size/nature/
   complexity; Board and senior management accountable; "LFIs should not employ AI models that
   they have no control over"; AI risk built into the risk-management framework; control
   functions must understand and be able to challenge AI.
3. **Fairness / non-discrimination and ethics** — no discriminatory or manipulative outcomes;
   representative training data; bias testing at least annually and on material change/upgrade.
4. **Transparency and explainability** — disclose AI use (especially high-impact decisions and
   when a customer interacts with an AI); plain-language disclosures **in Arabic and English**,
   phone support in major UAE languages; consider **opt-out rights** from AI for high-impact decisions.
5. **Data quality, privacy and security** — accurate data with provenance/audit trails; PDPL and
   Information Assurance Regulation compliance; **data-residency** ("retained in the country");
   privacy-by-design and security-by-design; stress testing; operational resilience; use AI to
   help detect fraud/AML issues and report as required.
6. **Continuous monitoring and review** — ongoing monitoring; periodic independent challenge of AI
   (including third-party providers); test automatic updates before deployment; ability to detect,
   report and remediate issues; **retain the immediate ability, with human intervention, to cease
   use** of any AI; responsibility for outsourced AI is retained.
7. **Human oversight and consumer protection** — meaningful human oversight, especially for
   decisions with significant consumer implications; human-in-the-loop / human-on-the-loop /
   human-out-of-the-loop models.
8. **Integration with existing frameworks** — sits on top of existing CBUAE regulation/standards.
9. **Outsourcing and third-party risk** — contractual audit and information rights, notice of
   material developments, termination rights, data protection, cyber security, performance.
10. **Ethical collaboration and innovation.**

**Status of the principles:** these are expressed as "should" expectations (guidance, not a
binding rulebook), but they set the supervisory benchmark a CBUAE-supervised LFI will be measured
against. Note the document is framed around **consumer protection**, so its weight is greatest for
LFIs making customer-facing decisions.

### SCA (capital markets)

The SCA regulates onshore securities and commodities activity and is a co-signatory of the 2021
joint Guidelines (below). It has not issued a standalone binding AI rulebook; expect
technology-neutral application of existing conduct and systems requirements.

---

## Track 2 — The cross-cutting instrument: joint Enabling Technologies Guidelines (Nov 2021)

The one document that reaches across all four financial regulators. Full title: *Guidelines for
Financial Institutions Adopting Enabling Technologies*, jointly issued 15 November 2021 by the
**CBUAE, SCA, DFSA and FSRA**.

- **Scope:** Any firm licensed and supervised by any of the four regulators that uses the
  covered technologies, regardless of activity.
- **Covered technologies:** APIs, **Big Data Analytics and AI**, biometrics, cloud computing,
  and distributed ledger technology.
- **Nature:** Cross-sectoral principles and best practice (governance, risk management, data
  management, consumer protection, technology governance) rather than prescriptive rules.

This is the common baseline. The CBUAE Feb 2026 Guidance Note then deepens the AI-specific
expectations for onshore CBUAE firms; DIFC's Regulation 10 does the equivalent for data
processing inside the DIFC.

---

## Track 3 — The free zones

### DIFC (regulator: DFSA; plus Commissioner of Data Protection)

**DFSA posture:** technology-neutral, focused on risk management rather than the technology. No
AI-specific binding rulebook to date; active on thought-leadership (co-led the GFIN
consumer-facing-AI report with the UK FCA in Jan 2025; published a Cyber and AI Risk report Jun
2025; runs an annual AI survey). The 2025 DFSA AI survey found 52% of DIFC firms using AI
(up from 33% in 2024), with generative-AI adoption up ~166%.

**DIFC Regulation 10 (binding).** This is the part that bites. Regulation 10 of the DIFC Data
Protection Regulations (in force 1 September 2023, full enforcement from January 2026) governs
processing of personal data through "autonomous and semi-autonomous systems" (i.e. AI). It is
the first instrument in the MEASA region to regulate AI directly, and a DIFC-based financial
firm using AI on personal data is squarely in scope. Key features:

- **New roles, borrowed from the EU AI Act:** Deployer (accountable like a controller),
  Operator (like a processor), Provider (developer). The definitions are adapted from the OECD
  guidelines and the EU AI Act; purely deterministic automation is excluded.
- **Transparency notices** at first use, describing human-defined vs system-defined processing
  purposes, the output and how it is used, design safeguards, and the codes/certifications the
  system follows (the text explicitly lists OECD, UNESCO, NIST AI RMF, and the **joint
  Enabling Technologies Guidelines** as acceptable reference frameworks).
- **Human-intervention algorithms:** evidence, on request, of mechanisms that route to a human
  where processing may be unfair/discriminatory, where law-enforcement access arises, or where
  processing risks breaching the digital-communications rules; plus risk and impact assessments.
- **AI register** of use cases, necessity/proportionality, data-subject access routes, whether
  the system makes solely automated decisions, and third-party sharing.
- **High-risk processing:** prohibited commercially unless the Commissioner's audit/certification
  requirements are met, the system processes only human-defined/approved purposes, and an
  **Autonomous Systems Officer (ASO)** has been appointed.

### ADGM (regulator: FSRA; plus Office of Data Protection)

**FSRA posture:** technology-neutral, like the DFSA; no AI-specific binding rulebook, with AI
risk managed through existing systems-and-controls and the ADGM Digital Sandbox for controlled
experimentation. **ADGM Data Protection Regulations 2021** (amended 2024 and 2025) govern
automated decision-making, algorithmic transparency and human oversight, but ADGM has not
enacted a Regulation-10-style AI-specific data rule. FSRA is a co-signatory of the 2021 joint
Guidelines.

---

## What a financial institution actually has to do

Common to all three tracks (the practical floor):

1. **Inventory your AI.** Maintain a register of AI/ML systems with risk classification and use
   cases. (CBUAE inventory; DIFC Regulation 10 register.)
2. **Put a named human in charge.** Board/senior-management accountability (CBUAE); an
   Autonomous Systems Officer for high-risk processing (DIFC).
3. **Be able to explain decisions** and give customers a route to human review, especially for
   credit, pricing and insurance ("high-impact decisions").
4. **Test for bias** (CBUAE: at least annually and after material change) and document it.
5. **Manage your vendors.** Contractual audit/information rights, third-party model inventory,
   the ability to suspend or exit. Responsibility cannot be outsourced.
6. **Keep a human in or on the loop** for material decisions; fully automated credit/insurance
   decisions are unlikely to pass supervisory muster onshore.
7. **Data protection underpins everything.** PDPL onshore; DIFC DP Law + Regulation 10 in the
   DIFC; ADGM DP Regulations in the ADGM. Privacy- and security-by-design throughout.

Track-specific additions:
- **Onshore (CBUAE):** align to the five principles and the "high-impact decision" framing; map
  AI governance onto the existing Model Management Standards and Consumer Protection Regulation.
- **DIFC:** transparency notices, the AI register, human-intervention algorithms, and (for
  high-risk processing) certification + an ASO under Regulation 10, ahead of full enforcement
  from January 2026.
- **ADGM:** automated-decision-making and transparency duties under the ADGM DP Regulations;
  use the sandbox for novel deployments.

---

## How the UAE compares (within this repo)

The UAE's financial-sector approach is recognisably the same "principles + supervisory
expectation, anchored in existing frameworks" DNA seen in the
[cross-jurisdictional financial-services overview](../../drafts/financial-services-ai-governance-cross-jurisdictional.md):

- **Like Singapore (MAS FEAT) and the UK (FCA):** principle-based, proportionate, technology-
  neutral, no binding AI-specific financial rulebook onshore. The CBUAE's five principles map
  closely to FEAT's fairness/ethics/accountability/transparency.
- **Like Switzerland (FINMA):** non-binding guidance that nonetheless carries supervisory weight.
- **Unlike all of them in one respect:** the DIFC's Regulation 10 is a genuinely **binding**
  AI-specific obligation (in a data-protection frame) that a DIFC-based financial firm cannot
  treat as merely advisory. It borrows EU AI Act concepts (deployer/operator, risk/impact
  assessment, human oversight) without the EU's product-conformity machinery. This makes the
  UAE a hybrid: soft-law onshore, with a hard-edged free-zone overlay.
- **The fragmentation is the headline risk** for a cross-border group: three financial
  jurisdictions, three data-protection laws, three AI postures, inside one country.

---

## Open questions to resolve with the client

1. **Where is the client licensed** (onshore CBUAE/SCA, DIFC, or ADGM), and does it operate
   across more than one? This sets the whole compliance stack.
2. **What is the client?** Bank, insurer, finance company, capital-markets firm, payments/VASP?
   This changes which CBUAE/SCA standards layer on top.
3. **What AI is in use,** and does any of it drive "high-impact decisions" (credit, pricing,
   underwriting, claims) or "high-risk processing" of personal data?
4. **Does it use third-party / vendor or generative-AI models?** This triggers the outsourcing
   and black-box-documentation expectations.
5. **DIFC firms:** is there a plan for Regulation 10 full enforcement (Jan 2026), including
   appointing an Autonomous Systems Officer and certification for any high-risk processing?

---

## Sources

Primary documents collected in [`../source/`](../source/): the CBUAE AI/ML Guidance Note (Feb
2026, full official text), the joint Enabling Technologies Guidelines (2021), DFSA AI Survey 2025,
DIFC consolidated Data Protection Regulations (incl. Regulation 10), and the ADGM Data Protection
Regulations 2021. See [`../source/inventory.md`](../source/inventory.md) for the full list and links.
