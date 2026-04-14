# AI Playbook for the UK Government — Review

**Document:** Artificial Intelligence Playbook for the UK Government
**Published:** February 2025
**Issuing body:** Government Digital Service (GDS) / Department for Science, Innovation and Technology (DSIT)
**Forewords by:** Feryal Clark MP, Parliamentary Under-Secretary of State for AI and Digital Government; David Knott, Government Chief Technology Officer

---

## Summary

This is a 118-page operational guidance document for civil servants building, buying, and using AI in UK government. It updates and expands the Generative AI Framework for HMG (January 2024), broadening scope to cover all forms of AI. The playbook is organised around 10 principles — which build on and extend the 5 cross-sectoral principles from the March 2023 pro-innovation white paper — and provides detailed practical guidance across four domains: understanding AI, building AI solutions, using AI safely and responsibly, and governance. An appendix documents six real public sector AI case studies (GOV.UK Chat, CCS commercial agreement recommendation system, Digital Sensitivity Review at FCDO Services, NHS user research finder, NHS.UK reviews moderator). The document is developed collaboratively with 20+ central government departments, arm's length bodies, industry (Amazon, Google, IBM, Microsoft), and academic institutions (Alan Turing Institute, Oxford Internet Institute, BCS, Manchester Metropolitan University, University of Surrey).

---

## Key Points

### The 10 Principles

Building on the white paper's five principles, the playbook's 10 principles are:

1. **You know what AI is and what its limitations are** — understand capabilities and risks
2. **You use AI lawfully, ethically and responsibly** — engage legal, compliance, DPO early; consider bias; engage users including underrepresented groups
3. **You know how to use AI securely** — comply with Secure by Design and Cyber Security Strategy
4. **You have meaningful human control at the right stages** — validate high-risk decisions; fully test before deployment
5. **You understand how to manage the full AI life cycle** — selection, maintenance, updates, secure closedown
6. **You use the right tool for the job** — be open to AI and to concluding AI is not the right solution
7. **You are open and collaborative** — use ATRS (required for central gov departments and in-scope ALBs)
8. **You work with commercial colleagues from the start** — AI is a rapidly developing market
9. **You have the skills and expertise needed** — multidisciplinary teams; upskilling
10. **You use these principles alongside organisation policies and have the right assurance in place** — AI review board or programme-level board

### Building AI Solutions

- **Team composition:** Minimum viable AI team must identify user needs, manage stakeholders, design/build/test using agile, ensure ethical/lawful/secure development, manage data responsibly, support live running
- **User research:** Dedicated section on AI-specific UR activities — understanding if AI is the right tool, defining performance metrics, data preparation, synthesizing data, evaluating outputs, measuring usability, understanding trust and attitudes, accessibility, monitoring over time. Model metrics vs service metrics distinction — a high-accuracy algorithm whose outputs users misinterpret or ignore
- **Use cases to avoid:** Fully automated decision making for significant (health/safety) decisions; high-risk applications affecting health, safety, fundamental rights, or environment
- **Business case thresholds:** Any investment approaching 10 million pounds requires Green Book five-part business case. Mandatory to assure non-BAU spend above 100,000 pounds for digital / 1 million pounds for technology
- **Procurement routes:** Frameworks (Big Data and Analytics, Technology Services 3, Cloud Compute 2) vs Dynamic Purchasing Systems (AI DPS, Automation Marketplace, SPARK). DPS preferred for AI because open to new suppliers any time
- **AI Management Essentials** — DSIT scheme being developed; after testing plans to embed in procurement frameworks

### Ethics (six themes)

1. **Safety, security and robustness** — resilient, sustainable, reliable even under adversarial attack; group privacy beyond GDPR
2. **Transparency and explainability** — five types: technical, process, outcome-based, internal, public. ATRS mandatory for in-scope bodies. Clear signposting when AI used in content creation, public interaction, or decision-making
3. **Fairness, bias and discrimination** — Equality Act 2010, Public Sector Equality Duty, EHRC guidance. Continuous evaluation across intersectional groups
4. **Accountability and responsibility** — answerability, auditability, liability. **"Responsibility for any output or decision made or supported by an AI system always rests with the public organisation."** Nominate a senior responsible owner (SRO) for each project
5. **Contestability and redress** — public awareness, appeal mechanisms, change processes. SRO responsible for monitoring reports and implementing changes. Contingency plans to maintain essential services if AI must be stopped
6. **Societal wellbeing and public good** — net positive impact; harm minimisation; misinformation/disinformation risks; environmental sustainability. **"If the potential negative consequences are too high, you must consider terminating the project."**

### Legal and Data Protection

- **DPIA mandatory** before implementing AI where Article 35(3)(a) UK GDPR applies (automated processing with legal/significant effects, large-scale special category data, systematic monitoring) or where ICO requires (innovative technologies). 10-step DPIA structure specified
- **Article 22 UK GDPR** — currently prohibits decisions based solely on automated processing that have legal or similarly significant consequences. "Services using AI that affect a person's legal status or their legal rights must only use AI to support decisions that must be made by a human decision maker"
- **Human rights** — public authorities must act compatibly with ECHR. Article 8 (private/family life) and Article 10 (freedom of expression) most likely impacted
- **Treat AI outputs as "statistically informed guesses" not facts.** Factor possibility of incorrectness into decisions

### Security

- **Compliance with Secure by Design before deployment required**
- **Cross-government AI security group** for GOV.UK email addresses
- **Deployment patterns ranked by risk:** public AI web apps (don't enter official info) -> embedded AI -> public APIs -> privately hosted -> managed ML platforms (e.g. Azure OpenAI with zero-day retention)
- **Security risks inventoried:** data and model poisoning, data leakage, insecure AI tool chain, over-privileged access, perturbation attacks, prompt injection (direct and indirect), hallucinations
- **Five detailed security scenarios** with OWASP risk rating methodology:
  1. Deepfake bypassing identity verification (MEDIUM/HIGH)
  2. MLOps tools with default configuration (MEDIUM/HIGH)
  3. Chatbot direct prompt injection (HIGH/LOW-HIGH)
  4. Enterprise AI search tool data exfiltration via indirect prompt injection (LOW/HIGH)
  5. Developer using LLM-generated code with hallucinated package (LOW/HIGH)
- **Specific operational prohibitions:** Never enter official information into public AI unless cleared; never use private data requiring different access permissions to train/fine-tune; human must review before generative AI takes destructive/irreversible actions; treat all LLM-generated code as inherently insecure; avoid LLM chatbots on public-facing government websites unless prompt injection risk is acceptable; virtual meetings — verify identities and prohibit third-party AI transcription tools
- **AI-generated content detection** — when building services that receive/process images, video, or correspondence, must implement detection of AI-manipulated content

### Governance

- **AI governance board or AI representation on existing board** to oversee risk, compliance, strategic alignment
- **Ethics committee** where appropriate (small/low-risk programmes may not need one; governance board advises)
- **AI/ML systems inventory** — additional to ATRS; live document with each system's purpose, risks, data elements, ownership, development dates
- **The Orange Book** (Portfolio Risk Management Guidance) for risk management
- **ISO compliance required** — "products and services comply with the required standards as defined by standards development organisations (SDOs), such as the International Standards Organisation (ISO)"
- **Release management** — changes documented; releases can be withdrawn and systems reverted. Model drift monitoring essential

---

## Observations

### Clarity

The playbook is the most operationally detailed AI governance document in the UK landscape. Where the pro-innovation white paper stated principles and the Action Plan set ambitions, the playbook tells civil servants exactly what to do: specific procurement routes, specific DPIA steps, specific security scenarios, specific governance structures. The inclusion of six real case studies (GOV.UK Chat, CCS, FCDO, NHS) grounds abstract guidance in concrete practice.

The 10 principles are well-organised and each is explained with practical recommendations. The structure — principles followed by understanding, building, using, and governance — moves logically from abstract to operational. The appendix of case studies is a significant strength that other UK AI documents lack.

However, the document has a persistent clarity problem: the inconsistent use of "must" and "should." Some "musts" are statutory obligations (UK GDPR, Equality Act, Human Rights Act). Others are departmental expectations without legal backing (Secure by Design compliance, nominating an SRO, using ATRS for non-mandated bodies). The reader is often left uncertain whether a requirement is legally binding, a government-wide policy, departmental best practice, or the playbook's own recommendation. A legend or markup distinguishing legal obligations from recommended practice would improve usability substantially.

### Measurability

The playbook does better than most UK AI governance documents on measurability, but the measurements are mostly procedural rather than outcome-based:

**Measurable requirements:**
- Green Book business case threshold: 10 million pounds
- Assurance thresholds: 100,000 pounds (digital) / 1 million pounds (technology)
- Civil Service learning entitlement: 5 days per year
- DPIA 10-step process
- OWASP risk rating in security scenarios

**Unmeasured outcomes:**
- No metrics for whether AI systems are actually deployed safely
- No mechanism to verify ATRS compliance rates
- No requirement for departments to report governance board activity
- No outcome measures for the six ethical themes — "fairness" is prescribed but not defined with specific thresholds
- No formal certification or audit mechanism — "Introduction to AI assurance" identifies assurance techniques but adoption is voluntary

The playbook is guidance; it creates no enforcement mechanism and proposes no metrics by which departmental compliance could be assessed.

### Gaps

**Enforcement.** The playbook is non-statutory guidance. "Must" statements that are not already legally binding create no new legal obligation. There is no auditor, inspector, or enforcement body. A department that ignores the playbook faces no specific consequence. This is consistent with the UK's broader non-statutory AI regulatory approach, but it means the playbook's prescriptions depend entirely on voluntary adoption.

**Local government and wider public sector.** The playbook focuses on central government departments and arm's length bodies. The case studies are all central government. The ATRS requirement applies only to central gov and in-scope ALBs. Local authorities, NHS trusts, schools, and other public bodies are only lightly covered, despite being major users of AI systems. The One Year On report mentions Local AI programmes (Minute, Extract) — those deployment contexts are not addressed in detail here.

**Intellectual property and copyright.** The legal section mentions IP considerations in procurement (who owns generated IP, balance of risk/liability for third-party infringement), but this is a three-line treatment. The major UK copyright impasse (flagged in the Feb 2024 consultation response, still unresolved in the One Year On report) is not addressed. Government departments using foundation models face real questions about whether models were trained on copyrighted material, and the playbook provides no guidance.

**Environmental sustainability.** Referenced under societal wellbeing — "less environmentally sound to train your own model when pre-trained models are available." But the guidance is light. There is no requirement to measure or report energy consumption, no threshold for when environmental impact should block a project, no methodology for evaluating model providers' sustainability credentials beyond vague criteria ("renewable energy, energy-efficient infrastructure").

**Devolution.** The Scottish Government is in the acknowledgements. Wales and Northern Ireland are not mentioned. The playbook does not address how devolved administrations should use it, whether devolved AI policies align or diverge, or how UK-wide ATRS and central governance interact with devolved public services.

**Workers.** AI's impact on civil service jobs and working practices is not addressed. The playbook assumes civil servants will use AI tools; it does not address displacement, retraining needs for staff whose jobs are automated, or union engagement on AI deployment decisions.

**AI developer obligations.** The playbook addresses government as a buyer and user of AI, not as a builder of frontier systems. The Sovereign AI Unit (announced in the Action Plan) will invest in frontier AI companies, but the playbook does not address how a government-backed AI developer should be governed.

**Scope of "public good."** The societal wellbeing section states AI systems "must generate a net positive impact on stakeholders and civil society at large." But who judges this, against what baseline, and with what evidence? The guidance provides no methodology. The test is aspirational but unenforceable.

### Feasibility

The playbook is feasible in the sense that its recommendations are achievable for well-resourced central government departments with existing digital capability (DSIT, Cabinet Office, HMRC, DWP). For these departments, much of the guidance is codifying practice that already exists.

Feasibility is more questionable for:

- **Smaller departments and ALBs** — many do not have data protection officers with AI expertise, security teams with ML knowledge, or commercial teams experienced in AI procurement. The playbook recommends consulting internal experts that may not exist
- **Local government** — even less likely to have the specialised expertise described. The Local AI programme provides some shared capability, but it is nascent
- **User research at scale** — the UR section is detailed and ambitious, requiring dedicated researchers with AI literacy. The UK civil service has a strong UR community, but scaling this to every AI project is resource-intensive
- **Sandbox provision** — the playbook recommends "sandboxes and safe spaces to experiment with AI securely" for data, analytics, and digital professionals. These are not universally available across government

The AI Capability Fund (3.6 million) and Regulators' Pioneer Fund (8.9 million) mentioned in the One Year On report exist, but they are modest relative to the scale of implementation the playbook prescribes.

### Internal Consistency

The playbook is largely internally consistent. The 10 principles map cleanly to the four operational domains. The ethics themes (6) extend the cross-sectoral principles (5) in sensible ways — adding societal wellbeing/public good as a sixth theme that addresses a gap in the white paper's framework.

Three consistency issues:

- **Principle 1 vs Principle 6.** Principle 1 says civil servants must know what AI can and cannot do, including that AI "currently lacks reasoning and contextual awareness." Principle 6 encourages openness to AI as enabling "new/faster public service delivery." These can coexist, but the playbook rarely names the tension — that AI's capabilities are being oversold in some of its own framing while its limitations are emphasized in others
- **Ethics vs Security.** The ethics section argues for transparency and explainability. The security section notes that open-source models expose weights and training data to attackers. These trade-offs are acknowledged in the abstract but not resolved with specific guidance on when to prioritise which
- **Principle 2 vs operational requirements.** Principle 2 requires "diverse and inclusive participation" in projects. The operational sections describe AI governance boards, ethics committees, and AI systems inventories — but do not require diverse representation on these bodies or prescribe how inclusivity should be measured

### Coverage

For an operational playbook, coverage is reasonably comprehensive. It addresses principles, technical understanding, team formation, user research, use case identification, procurement, ethics, legal issues, data protection, security, governance, and provides case studies.

Notable coverage strengths:
- Security section is substantially more developed than in any other UK AI governance document — five scenarios with OWASP risk ratings, specific mitigations, clear prohibitions
- Data protection section is detailed and specifically tied to UK GDPR articles and ICO guidance
- The case studies are genuinely useful — GOV.UK Chat in particular has become a reference example

Coverage gaps (discussed above): enforcement, local government, IP, environmental impact, devolution, workers, AI developer obligations.

### International Alignment

The playbook references the OECD definition of AI and adopts it. The 10 principles align broadly with OECD AI Principles. ISO compliance is made an operational requirement. NCSC principles (aligned with international cyber security standards) are cited extensively.

However, the playbook is almost entirely domestic in orientation. There is no discussion of how UK government AI use aligns with international frameworks the UK has signed (Bletchley Declaration, Seoul Declaration, Council of Europe AI Convention). International interoperability — cited as a goal in the white paper — is addressed only via standards references, not policy alignment.

For UK government departments whose AI use may affect citizens of other countries (FCDO, Home Office, HMRC), this is a gap. The playbook does not address extraterritorial reach or the interaction with GDPR (where data flows internationally) beyond Article 46 data transfer agreements.

---

## Overall Assessment

The AI Playbook is the UK's most practical and operationally substantive AI governance document. Where the white paper sets principles and the Action Plan sets ambitions, the playbook tells civil servants how to actually build, buy, and use AI systems in compliance with those principles. The six real case studies are a particular strength. The security section is by some distance the most developed treatment of AI security in UK government publications, with specific scenarios, OWASP risk ratings, and clear operational prohibitions.

Its greatest strength is concrete guidance. Civil servants who read the playbook and follow its recommendations will build AI systems that are substantially safer, more transparent, and better-governed than they would otherwise be. The 10 principles are well-constructed, the DPIA 10-step structure is practical, and the procurement guidance is genuinely useful.

Its greatest weakness is enforcement. The playbook is non-statutory guidance that depends on voluntary adoption. Many of its "must" statements are departmental expectations without legal backing. There is no audit, no certification, no compliance reporting. A department that ignores the playbook faces no specific consequence. The Algorithmic Transparency Recording Standard — the one element with formal compliance monitoring — applies only to central government and in-scope ALBs, with limited public reporting of non-compliance.

The playbook is the operational counterpart to a regulatory framework that explicitly rejects statutory enforcement. This is internally consistent with the UK's pro-innovation approach — but it means the UK's public sector AI governance depends almost entirely on the goodwill and capability of individual departments. Well-resourced departments with existing digital capability will implement the playbook thoroughly. Smaller, less-resourced public bodies may implement it partially or not at all. The playbook itself has no mechanism to detect or address this divergence.

The playbook's framing as a "launchpad that we will continuously revise and improve" is accurate and appropriate. As AI capabilities evolve, the playbook will need frequent updates. The update log (p. 6) shows the document has already been expanded beyond generative AI. This iterative approach is sensible, but it also means the playbook cannot serve as a stable baseline against which compliance is measured.

---

## Sources

- [AI Playbook for the UK Government (GOV.UK)](https://www.gov.uk/government/publications/ai-playbook-for-the-uk-government)
- [Generative AI Framework for HMG (January 2024)](https://www.gov.uk/government/publications/generative-ai-framework-for-hmg)
- [Algorithmic Transparency Recording Standard](https://www.gov.uk/government/collections/algorithmic-transparency-recording-standard-hub)
- [Portfolio of AI Assurance Techniques (RTAU)](https://www.gov.uk/government/publications/cdei-portfolio-of-ai-assurance-techniques)
- [The Orange Book: Management of Risk](https://www.gov.uk/government/publications/orange-book)
