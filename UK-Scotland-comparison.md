# UK vs Scotland: AI Governance Comparison

A comparison of the UK's AI governance position (as analysed in 10 document reviews in this repo) with Scotland's AI Strategy 2026-2031 (analysed separately in the [AI_Scotland repository](https://github.com/EdwardAThomson/AI_Scotland)).

Constitutional context matters here: Scotland is a devolved nation of the UK, so these are not independent jurisdictions. Many AI-relevant powers (competition, consumer protection, data protection, financial regulation, immigration, AI safety, international governance) are reserved to Westminster. Scotland operates on devolved competences (health, education, policing, skills, economic development) within a UK-wide regulatory frame.

---

## What each has

| Dimension | UK | Scotland |
|-----------|----|---------| 
| **Number of governance documents** | 10 substantive documents (reviewed here) | 1 strategy document (plus earlier 2021 strategy) |
| **Flagship strategy** | AI Opportunities Action Plan (50 recommendations) + Government Response with timelines + One Year On progress report | AI Strategy 2026-2031 (AI Stack model, 8 layers, 10 actions) |
| **Regulatory framework** | Pro-Innovation White Paper + Feb 2024 Consultation Response | Section 8 of the strategy (regulation as one of 8 AI Stack layers) |
| **Operational guidance** | AI Playbook (118 pages, 10 principles, extensive ethics/security detail) | None |
| **Safety institution** | AI Safety Institute (AISI) — 100+ researchers, 240M GBP, chairs international network | None |
| **Competition analysis** | CMA foundation models report (129 pages) | None |
| **Science strategy** | AI for Science Strategy — 137M GBP, 5 priority areas, drug discovery mission | None (referenced within general strategy) |
| **Scientific consensus process** | UK AISI hosts secretariat for International Scientific Report (30 countries) | None |
| **Named institutions delivering** | AISI, Sovereign AI Unit, AI Growth Zones, AI Opportunities Unit, Future of Work unit, i.AI, RTA | AI Scotland consortium, Expert Advisory Board (6 members), proposed Future Jobs Panel |
| **Infrastructure commitments** | Isambard-AI (Bristol), DAWN (Cambridge), EPCC (Edinburgh), Archer2 extension, AIRR expansion 20x by 2030 | None — grid infrastructure identified as dependency on UK-reserved powers |
| **Specific compute investment** | 750M GBP for next national supercomputer, 250M for AIRR scaling | None named |
| **Major funding commitments** | 240M (AISI), 500M (Sovereign AI Unit), 100M+ (National Data Library), 187M (TechFirst), 600M (Health Data Research Service), 2B+ total for AI 2026-2030 | 1M GBP SME AI Adoption Programme (reaches 0.14% of SME base); no budgets attached to other actions |
| **AI Growth Zones** | 5 designated (2 Wales, 1 Scotland, 2 England); 28.2B GBP investment generated | One Scottish AI Growth Zone exists (via UK Government designation) |

---

## Where the two diverge substantively

### Regulatory philosophy

The most consequential difference: **Scotland advocates EU AI Act alignment; the UK rejects it.**

- UK position: Pro-innovation, non-statutory, context-specific, sector-regulator-led. Five cross-cutting principles without statutory duty. Post-Brexit regulatory sovereignty framed as competitive advantage. January 2025 commitment to establish AISI as statutory body (still undelivered).
- Scotland position: Advocates alignment with EU AI Act on market access grounds; supports putting OECD principles on a statutory footing. The three-LLM review called this the "most politically significant" section of the Scottish strategy.

Scotland cannot deliver this position unilaterally — regulation is largely reserved to the UK. But the divergent stated preference indicates different political philosophies: Scotland's strategy is explicitly EU-oriented, the UK's is explicitly distinctive-from-EU.

### Measurability

Both suffer from this problem but Scotland more severely.

- UK Opportunities Action Plan was criticised in my review for lacking measurable targets. The Government Response added timelines (spring 2025, summer 2025, autumn 2025 etc.), partially addressing the gap. The One Year On report claims 38 of 50 actions met but does not identify the unmet 12.
- Scotland has neither targets nor timelines attached to its 8 outcomes. Phases 2 and 3 of the strategy are completely empty. All three reviewers of the Scottish strategy identified this as the document's central weakness — "the government could claim success on every outcome in 2031 without demonstrating meaningful change."

### Budgets

- UK: specific sums are attached to most initiatives. Scale of total commitment is in the billions.
- Scotland: "not a single action in the strategy includes a cost, funding source, or resource allocation." The only named figure is 1M GBP for an existing SME programme.

The UK has access to fiscal levers (Spending Review) Scotland lacks. Scotland must operate within its devolved block grant and has limited borrowing powers. This explains some of the disparity, but not the absence of budget indications altogether — Scottish policy documents typically do attach funding estimates.

### Operational depth

- UK: 118-page Playbook prescribes DPIA steps, security scenarios with OWASP risk ratings, procurement routes, governance structures. AISI publishes evaluation methodology.
- Scotland: strategy operates at the level of intent. No operational counterpart to the UK Playbook. AI-in-government practice in Scotland operates under UK frameworks (ATRS, Playbook) or Scottish Government internal policy (not analysed here).

### Treatment of workers / Fair Work

- UK: Future of Work unit announced in the January 2026 One Year On report — a cross-government unit with representatives from business and trade unions. This addresses what was (correctly) identified as a major gap in the original Action Plan. Earlier UK documents were light on labour market impact.
- Scotland: Fair Work is rhetorically central to the strategy's framing but, per all three reviewers, "operationally absent." Not in governance structures, delivery mechanisms, or advisory membership. Glossary doesn't define it.

Ironically, the UK — which does not have Fair Work as a formal policy framework — has moved further on operationalising labour market engagement than Scotland, which does.

### Treatment of citizens' rights and ethics

- UK: AI Playbook devotes ~60 pages to ethics, legal considerations, data protection, security, and governance — with specific prescriptive requirements (DPIA mandatory in specified scenarios, Article 22 UK GDPR prohibitions, ATRS for central government).
- Scotland: Scottish strategy is "economy-first, not people-first" per reviewers. No right to challenge AI decisions, no complaints mechanism, no requirement for human alternative. Regulation framed around market access rather than citizen protection.

### Risk registers

- UK: AISI identifies four priority risk domains (misuse, societal impacts, autonomy, safeguards). International Scientific Report covers malicious use, malfunctions, systemic risks with extensive sub-categories.
- Scotland: gender inequality is the only named equality risk. Globally recognised AI risks (misinformation, bias beyond gender, cyber, democratic integrity, concentration of power, children) absent.

### International positioning

- UK: host of Bletchley, Seoul, Paris summits; hosts AISI secretariat for international scientific report; founding member of GPAI; member of OECD AI-GO, Council of Europe CAI, ISO/IEC; bilateral AISI partnerships with US and Singapore.
- Scotland: strategy explicitly pro-EU in regulatory orientation but has no operational international programme. International benchmarking is absent from the strategy (endnotes are "almost entirely domestic").

---

## Where the two converge (substantively and in their weaknesses)

### Both fundamentally economy-first strategies

Despite different political contexts, both the UK AI Opportunities Action Plan and Scotland's AI Strategy treat AI primarily as an economic growth opportunity. Safety, ethics, and citizens' rights are secondary concerns delegated elsewhere (to AISI in the UK case; underdeveloped in the Scottish case).

### Both weak on implementation evidence

Neither document seriously assesses the delivery record of prior strategies:
- UK: does not evaluate the 2021 National AI Strategy before moving on to new frameworks
- Scotland: references the 2021 AI Strategy but does not assess what worked or didn't

### Both treat AI adoption largely through SME lens

The UK's Innovate UK BridgeAI programme and Scotland's SME AI Adoption Programme both focus on SMEs. Large enterprise AI adoption (Scotland observation; applies to UK too) is less developed in both.

### Both rely heavily on creating institutional machinery

The three-LLM review of Scotland observed that actions "create machinery, not results" — panels, boards, pilots. The same critique applies to UK documents: AI Growth Lab, Future of Work unit, Sovereign AI Unit, AI Opportunities Unit, i.AI, Incubator for AI, Responsible Technology Adoption Unit. Both governance systems respond to AI by creating new entities.

### Both acknowledge infrastructure constraints honestly

The UK's CMA report flagged that UK CSP clusters lagged in NVIDIA A100 availability. Scotland's strategy honestly acknowledges grid infrastructure as a UK-reserved constraint. Both are cases of policy documents naming problems they cannot unilaterally solve.

### Both lack policy recommendations for frontier AI governance

The UK's position has evolved from voluntary-only (Pro-Innovation White Paper, 2023) to a case for binding measures on frontier developers (February 2024 Consultation Response) to commitment to statutory AISI (January 2025 Government Response) — but has not delivered legislation. Scotland advocates EU alignment but has no power to implement. Neither has functional binding regulation of frontier model developers.

---

## What Scotland does that the UK (at a comparable scale) does not

**Uses the AI Stack as a structuring device.** Scotland's 8-layer model (users, skills, companies, R&D, data centres, semiconductors, data, regulation) provides analytical organisation that UK documents lack. The UK has documents for each area but does not organise them as a coherent stack. The AI Stack is not radical, but it is effective — and Scotland's choice to make the Semiconductors layer a prominent strategic focus is distinctive.

**Names specific case studies.** Citizens Advice Scotland (35,000 cases), EGG Lighting (£40-60k cost avoidance), Chemify ($50M raise), Quantcore (superconducting fabrication in Glasgow). The UK Playbook includes case studies (GOV.UK Chat, CCS, FCDO, NHS) but at a smaller proportion of total document space. Scotland uses case studies to illustrate what responsible AI adoption looks like, and the three-LLM review noted this is more concrete than what the strategy itself commits to.

**Makes an explicit semiconductor niche argument.** Scotland's focus on photonics, advanced packaging, and superconducting components — rather than trying to be Taiwan — was called the strongest strategic thinking in the document. The UK's compute strategy (mentioned in the AI Opportunities Action Plan and elsewhere) does not include comparable differentiation; UK compute policy is framed around quantity (20x expansion of AIRR) more than specialisation.

---

## What the UK does that Scotland does not

**Has a dedicated AI safety institute with real capacity.** AISI has 100+ researchers, has tested 30 frontier models, produced peer-reviewed research, and chairs international coordination. This is an institutional capacity Scotland does not have and, given reserved powers over frontier AI governance, would not be well-positioned to build.

**Has binding legal frameworks that AI use must comply with.** UK GDPR, Equality Act 2010, Human Rights Act, CRA 2015, CPRs 2008 apply across the UK including Scotland. The UK frameworks are what provide the "floor" for AI accountability — the Scottish strategy cannot and does not claim to create these.

**Has operational guidance for public sector use.** The AI Playbook provides detailed prescriptions that apply to UK central government and in-scope arm's length bodies. Scottish public sector AI use operates under these (or under Scottish Government internal frameworks not analysed here). Scotland has not published an operational counterpart.

**Has detailed competition analysis.** The CMA's 129-page foundation models report provides market-structure analysis that no Scottish document approaches. This reflects reserved powers: competition policy is UK-wide, CMA is UK-wide, and these tools apply to Scotland without any Scottish analytical input.

**Has a much larger budget envelope.** Whether the UK's 2B+ GBP aggregate AI commitment is sufficient is debatable, but it dwarfs the Scottish strategy's named funding.

**Has published progress updates.** The AI Opportunities Action Plan: One Year On (January 2026) provides (selective) progress reporting. Scotland's 2021 strategy was published but no public progress update has been analysed; the 2026 strategy is too new for comparable reporting.

---

## The structural issue: what Scotland can and cannot do

Many UK AI governance areas are reserved from devolution:

- **Competition policy** (CMA) — reserved
- **Consumer protection** (DMCC Act) — reserved
- **Data protection** (UK GDPR, ICO) — reserved
- **Financial services regulation** (FCA) — reserved
- **Immigration** (AI talent routes) — reserved
- **AI safety legislation** (any statutory AISI, binding measures) — reserved
- **Grid and major infrastructure** — largely reserved
- **International AI governance participation** — reserved

Devolved competences relevant to AI:
- **Health** (NHS Scotland AI use, health data, AI diagnostics deployment)
- **Education** (AI in schools, colleges, universities)
- **Policing and justice** (Police Scotland AI use)
- **Economic development** (SME support, skills programmes)
- **Public procurement within Scotland**
- **Scottish Government own AI use**

Scotland's strategy therefore has to rely on advocacy to influence reserved areas (hence the EU alignment position is articulated but not enforceable) and action within devolved areas. The three-LLM review noted that Scotland's regulatory section "has clear policy position but Scotland's ability to deliver on this position is constitutionally constrained."

The result: the UK documents contain much more substantive regulatory and institutional content than the Scottish strategy because the UK has the levers. Scotland's strategy operates largely in the space of aspiration, skills, adoption, and advocacy — which explains why it is a single strategy document rather than a document ecosystem.

---

## Shared critiques that apply to both

From the three-LLM review of Scotland (consensus findings), several apply equally to UK documents:

- **"Actions create structures, not results"** — applies to UK documents too: AI Growth Lab, Future of Work unit, AI Assurance Innovation Fund, etc.
- **"No measurable targets"** — the original UK Action Plan had this problem; partially fixed by Government Response with timelines, still no outcome metrics
- **"No budgets"** — the original Action Plan had this problem; partially fixed by Government Response and Spending Review commitments
- **"Risk register is incomplete"** — UK risk analysis is stronger (AISI, International Scientific Report) but UK strategy documents themselves do not integrate risk analysis deeply
- **"Economy-first, not people-first"** — both the UK Action Plan and the Scottish Strategy fit this critique
- **"Consultation narrow relative to scope"** — the UK Action Plan was authored by a single individual (Matt Clifford) with industry input; broader consultation came through the 2023 pro-innovation process but tech industry voices dominated

---

## The bottom line

The UK has a substantively larger, more operationally developed, and more institutionally grounded AI governance position than Scotland — because it has the powers, the budget, and the institutional infrastructure that Scotland does not.

Scotland's strategy is, in consequence, mostly about things Scotland can do within devolution (skills, adoption, public sector data, economic development) while advocating for different UK-level choices on reserved matters (EU alignment, statutory regulation). It is not a weak strategy because Scotland wants less — it is constrained to a narrower footprint because of devolved/reserved boundaries.

That said, where the two approaches overlap, Scotland's strategy has distinct weaknesses that the UK has addressed (however incompletely): measurable targets (UK Govt Response added timelines; Scotland has none), budgets (UK has named sums; Scotland has none), Fair Work operationalisation (UK created Future of Work unit; Scotland left Fair Work rhetorical), citizens' rights framework (UK Playbook has detailed ethics; Scotland has weaker treatment).

Where the UK has weaknesses, some are shared: both are economy-first, both create institutional machinery, both respond to frontier AI risks with voluntary or advocacy approaches rather than enforcement. The UK's advantage is scale and institutional capacity, not fundamentally different policy philosophy.

The most interesting divergence is the regulatory posture. Scotland's explicit advocacy for EU AI Act alignment and OECD principles on a statutory footing is a political position Scotland has articulated clearly even though it cannot implement. Whether this creates ongoing friction with UK Government AI policy — and whether post-election politics change the UK position — will determine whether this divergence grows or narrows over time.

---

## Sources for this comparison

- UK: the 10 review documents in [`UK/analysis/review-claude/`](UK/analysis/review-claude/)
- Scotland: [`AI_Scotland` repository](https://github.com/EdwardAThomson/AI_Scotland) — particularly [`review-reconciliation/summary.md`](https://github.com/EdwardAThomson/AI_Scotland/blob/main/review-reconciliation/summary.md) and [`review-reconciliation/01-consensus-findings.md`](https://github.com/EdwardAThomson/AI_Scotland/blob/main/review-reconciliation/01-consensus-findings.md)
