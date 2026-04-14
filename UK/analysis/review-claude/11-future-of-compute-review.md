# Independent Review of The Future of Compute — Review

**Document:** Independent Review of The Future of Compute: Final report and recommendations
**Published:** 6 March 2023
**Chair:** Professor Zoubin Ghahramani FRS (Vice President of Research, Google; Professor of Information Engineering, University of Cambridge)
**Panel members:** Sue Daley (techUK), Shaheen Sayed (Accenture), Dr Graham Spittle CBE (Edinburgh), Professor Anne Trefethen FREng (Oxford)
**Commissioning body:** Department for Science, Innovation and Technology (DSIT)
**Addressed to:** Chancellor Jeremy Hunt and Secretary of State Michelle Donelan

---

## Summary

The Ghahramani-led review is the UK's foundational independent assessment of its compute position. Commissioned by DSIT and published alongside the Science and Technology Framework launch, it diagnoses a UK that has "just 1.3% of the performance worldwide" and "most powerful system ranks 28th globally" — 56 times less powerful than the US Frontier system. It makes 10 recommendations organised under three objectives: unlocking high-growth potential, building world-class sustainable capabilities, and empowering the compute community. The two most consequential recommendations are establishing an AI Research Resource (AIRR) by summer 2023 with at least 3,000 top-spec AI accelerators, and delivering full exascale capability by 2026 through a phased approach. The review also proposes a 10-year strategic vision, a national coordinating body, cloud interoperability, sustainability measures, skills programmes, security guidance, and international collaboration. Much of the subsequent UK compute policy — AIRR, Isambard-AI, the AI Opportunities Action Plan's 20x AIRR expansion, the Culham AI Growth Zone — can be traced back to this document.

---

## Key Points

### The Diagnosis

- **UK had 1.3% of global compute capacity** (November 2022)
- **No UK system in TOP500 top 25**; ARCHER2 ranked 28th globally, dropped 6 places in 2022
- ARCHER2 is "56 times less powerful" than US Frontier
- **UK fell from 3rd (2005) to 10th (2022)** in total compute performance
- All UK public systems at or over capacity: ARCHER2 88% utilisation; DiRAC 120% oversubscribed; Baskerville 82% avg (96% peak); CSD3 allocated 6 months ahead
- **Fewer than 1,000 NVIDIA A100 GPUs available to UK researchers** (vs 14,000 at Leonardo, 6,000 at Perlmutter)
- Compute demand by largest ML models grew "10 billion times over the last 10 years"; "computational demand to train AI currently doubling every 3-4 months"

### The 10 Recommendations

**Objective A — Unlocking high-growth potential:**
1. **Inaugurate a strategic vision and roadmap for compute** — 10-year vision in 2023, roadmap by spring 2024
2. **Increase leadership and national coordination** — establish a national coordinating body
3. **Enable increased and broader use of compute** — SME support, demand stimulation, integrated ecosystem

**Objective B — Building sustainable capabilities:**
4. **Immediate investments in the pathway to public exascale** — Phase 1: 250+ petaflops exascale-ready capability immediately; Phase 2: full exascale (≥1 exaflop) by 2026
5. **Improve access to public compute via the cloud** — interoperability lighthouse project, OCRE engagement, cloud accounting awareness
6. **Immediately and significantly increase compute capacity for AI research** — establish UK AIRR by summer 2023 with at least 3,000 top-spec AI accelerators
7. **Manage sustainability** — planning guidance, procurement for innovative sustainable computing, training

**Objective C — Empowering the community:**
8. **Invest in attracting and retaining talent** — domestic and international skills programmes
9. **Provide guidance and support for secure compute** — partner with NCSC on "secure by design"
10. **Collaborate with international partners** — PRACE, INCITE continuity; joint procurement exploration; global initiative leadership

### Specific Policy Positions

- **AIRR architecture:** Based on Canada's Digital Research Alliance model — any UK AI researcher should be able to access individual accelerators for exploratory research; large-scale projects via resource allocation calls. Must include skilled staff and access to key datasets
- **Exascale build-time:** ~18 months from contract award; Frontier cost ~$600M, Jupiter €500M
- **Energy for exascale:** US Frontier uses 21.1 MW (~42,000 UK homes); UK exascale ≈ 0.05% of national electricity supply; DARPA 20 MW/exaflop aspirational target
- **Cloud can be interim measure:** "Commercial cloud could be used to rapidly meet existing demand and act as a pilot to inform the business case for long-term AI compute provision"
- **Sovereignty framing:** "In an increasingly competitive geopolitical landscape, inadequate compute resources mean the UK lacks the agency to steer the development of frontier AI in a manner aligned with UK's values and objectives"
- **Turing Foundation Model** concept referenced — "to lead ambitious foundational research of building large language models, bringing UK public sector research to the frontier of AI"
- **Three-domain convergence:** compute for AI, compute for modelling/simulation, cloud compute — all converging

### Economic Case

- EPSRC HPC investment of 466 million yields 3-9.1 billion in benefits (BCR 6.5-19.5); spillover 5.8 billion
- Met Office supercomputer: 1.2 billion investment; 13.74 billion social value (BCR 9)
- NVIDIA Cambridge-1: 100M USD investment; 825M USD potential (BCR 12.1)
- UK HPC market CAGR up to 11% over next five years
- "Compute-intensive AI-augmented R&D has the potential to increase productivity growth significantly — by a factor of 2 compared to average rates in the last 75 years or a factor of 3 since 2000"

---

## Observations

### Clarity

This is a well-structured, clearly-written review that demonstrates substantial technical command. The three-objective architecture (A, B, C) maps cleanly to ten recommendations. Each recommendation includes sub-actions with specific targets where appropriate, supported by international reference cases (Gauss Centre for Germany, Digital Research Alliance for Canada, CEA-RIKEN for France-Japan).

The Chair's cover letter is refreshingly direct: "public investment in AI compute is seriously lagging," the infrastructure is "fragmented," there is "no long-term plan." The review combines diagnostic honesty with forward-looking prescription in a way that subsequent UK AI strategy documents have sometimes struggled to match.

The user taxonomy (pioneers, established, emerging, AI users) is a useful analytical construct. The benchmark presentation (growth in total compute performance, most powerful systems, AI accelerator comparisons) is clear and actionable.

### Measurability

Much stronger than most UK AI governance documents. The review provides specific numerical targets:

- AIRR: at least 3,000 top-spec accelerators
- Exascale Phase 1: at least 250 petaflops (10x ARCHER2)
- Exascale Phase 2: ≥1 exaflop by 2026
- Strategic vision: 10-year horizon; roadmap by spring 2024
- National coordinating body: by 2024

Quantitative baseline comparisons are extensive: UK 1.3% share, ARCHER2 at 20 petaflops vs Frontier at 1,102 petaflops, TOP500 rankings tracked over time, AI accelerator counts benchmarked against international peers.

What is less measured is the outcome horizon beyond compute capacity. The economic impact projections (BCRs from EPSRC, Met Office, Cambridge-1) are cited from external studies rather than derived from the review's own analysis. No framework is proposed for ongoing evaluation of whether UK compute policy is succeeding relative to ambitions.

### Gaps

**Frontier AI policy is largely absent.** The review correctly identifies that AI compute demand doubles every 3-4 months and that frontier model training uses "many exaflops." But its AIRR target (3,000 accelerators, later 20x expansion) is scaled to support UK academic research, not to compete with frontier developers (Meta's 21,400 A100s; Anthropic's estimate that the US public sector needs "100,000 top-spec GPUs to be truly competitive"). The review acknowledges this gap but does not close it. The subsequent UK Sovereign AI Unit and AI Growth Zones partially address it.

**Industrial strategy coupling.** The review treats compute as infrastructure; it does not integrate with industrial strategy, procurement, or export. The UK's later Sovereign AI Unit and Industrial Strategy (both launched 2025) try to link compute to commercial outcomes; this review's framing treats commercial uses as downstream beneficiaries rather than policy targets.

**Data and compute pairing.** The review explicitly notes that data is "out of scope" while acknowledging that "compute is only possible with access to quality and secure datasets." This is a defensible scope decision but means the review cannot address the interaction between compute and the National Data Library (later launched). The AI for Science Strategy (November 2025) subsequently treats data generation as a primary priority, partially filling this gap.

**Environmental impact quantified but not constrained.** The sustainability section is thoughtful but does not propose emissions targets, efficiency thresholds, or whole-system accounting for what an exascale UK would cost environmentally. "75% of UK data centre energy is renewable" is cited; it is not integrated into policy targets. Later UK documents (AI Opportunities Action Plan, One Year On) reference SMRs and micro-grids but do not quantify footprint either.

**Private cloud compute as competitor.** The review treats the three major CSPs (AWS, Azure, GCP) as partners and service providers. It does not address how public compute investment interacts with private cloud investment the CSPs are making in the UK (which by 2024 reached 25 billion GBP per the government's AIRR announcement). The CMA's subsequent investigation into cloud infrastructure services (referenced tangentially) is more germane to competition concerns than this review addresses.

**Skills pipeline timing.** The skills recommendations (Recommendation 8) are sound but predicated on long pipelines — visa reform, RSE career development, international exchanges. The exascale build-out (2026) will require trained operators and users before those pipelines produce graduates. The review does not propose bridging arrangements.

**Devolution.** Scotland figures prominently in compute infrastructure (EPCC Edinburgh hosts Tier 1 systems; DiRAC at Edinburgh) but devolved government coordination is not addressed. This matches the UK-wide pattern we have identified in multiple reviews — compute strategy treats Scotland as a venue, not a partner.

### Feasibility

The review's core proposals have largely been delivered in some form:

- **AIRR established** — launched 2023; Isambard-AI (Bristol) and DAWN (Cambridge) came online 2024-2025
- **Exascale Phase 1** — partial (Isambard-AI is a significant step; full Phase 1 target of 250+ petaflops partially met)
- **Full exascale by 2026** — delayed; the "full exascale" has slipped past the review's target date, with the Edinburgh supercomputer announced for Spring 2026 cycle
- **Strategic vision / Compute Roadmap** — published in subsequent government documents (UK Compute Roadmap referenced in the AI Opportunities Action Plan One Year On)
- **AI Growth Zones** — far exceeds what the review proposed; enabled by follow-on policy
- **National coordinating body** — not clearly established as a distinct entity, though DSIT and UKRI have increased coordination

The feasibility of the 10-year strategic vision has been tested by a change of government. The Labour government (from July 2024) largely accepted the review's compute recommendations via the AI Opportunities Action Plan, which is a positive signal for the review's political durability.

### Internal Consistency

Internally consistent. The three objectives, ten recommendations, and supporting analysis map cleanly to each other. One tension: the review simultaneously argues for government intervention (because "private investment is limited by cost, risk and technological change") and for integration with commercial cloud (because "commercial cloud could be used to rapidly meet existing demand"). These can coexist but the review does not resolve where the line should fall.

A second tension: the review emphasises UK sovereignty over compute while proposing deeper international collaboration. This is standard science policy positioning but the review does not address what happens when sovereignty and international collaboration conflict (e.g., if the US or EU restricts export of AI accelerators to the UK).

### Coverage

Coverage within scope is comprehensive. Infrastructure tiers, user types, international comparators, skills, security, sustainability, cloud, exascale, AI — all addressed. Out-of-scope items (data, narrow industrial strategy) are acknowledged as such.

Coverage gaps (discussed above): frontier AI competition, environmental targets, private sector compute interaction, devolution, long-term geopolitical risk to compute supply chains.

### International Alignment

The international benchmarking is the review's analytical backbone. Case studies of Australia's research infrastructure planning, Germany's Gauss Centre, Canada's Digital Research Alliance, CEA-RIKEN bilateral, EuroHPC, DOE INCITE — all are deployed to justify UK policy proposals.

The review notes UK indirect access to Frontier via INCITE (UCL leads a project) and UK involvement in 20% of PRACE projects since 2010, while flagging that post-Brexit UK researchers will not have direct access to EuroHPC's Jupiter. The review does not address whether the UK should seek to rejoin EuroHPC or negotiate alternative arrangements.

The Gordon Bell Prize benchmark — no UK winner since 2011, while US, China, Japan, Switzerland, France, Germany have won — is a telling data point on UK research competitiveness at the compute frontier.

---

## Overall Assessment

This is a genuinely excellent review. It is technically literate, analytically honest, and strategically coherent. The diagnosis of UK compute weakness is unflinching (1.3% global share, 28th place, 56x behind Frontier, fewer than 1,000 A100s). The prescription is specific (3,000 accelerators, 250 petaflops, 1 exaflop by 2026). The framework — 10-year vision, national coordination, phased exascale, AIRR, sustainability, skills — has substantially shaped subsequent UK compute policy.

Its greatest strength is that it thought clearly about compute as a national strategic capability, not just a research input. The framing of compute as having economic, scientific, and sovereignty dimensions; the demand forecast arguments; the international benchmarking; and the specific policy proposals all raise the quality of the conversation above the promotional register that characterises many UK government documents.

Its greatest weakness is that it pre-dates the generative AI explosion. Published 3 months after ChatGPT's release, before GPT-4, before the Bletchley Summit, before the EU AI Act, and before the broader public conversation about frontier AI safety, the review reflects a pre-generative-AI understanding of AI compute needs. Its AIRR target (3,000 top-spec accelerators) would have been audacious for UK academic needs in 2022; by 2025, with Meta using 21,400 A100s for a single training run and Anthropic suggesting 100,000 GPUs for public sector parity, it looks modest. The AI Opportunities Action Plan's commitment to 20x AIRR expansion (suggesting ~60,000 accelerators by 2030) reflects the scale update that was necessary.

The review's legacy is substantial: the AI Research Resource exists, Isambard-AI exists, DAWN exists, Archer2 was extended, the Edinburgh supercomputer is funded, the strategic vision was published. The compute roadmap and the AI Opportunities Action Plan both build on this foundation. For a review commissioned to inform government policy, this is a high standard of delivery.

What the review did not and could not do — address frontier AI safety, industrial strategy integration, environmental targets, and sovereign AI development at commercial scale — has been partially addressed by later documents. The review's place in the UK AI governance landscape is as the foundational compute document that makes subsequent strategy documents possible.

---

## Sources

- [Future of Compute Review (Parliament Deposited Papers)](https://data.parliament.uk/DepositedPapers/Files/DEP2023-0212/Independent_Review_of_The_Future_of_Compute.pdf)
- [GOV.UK Future of Compute Review collection](https://www.gov.uk/government/publications/future-of-compute-review)
- [AI Opportunities Action Plan (January 2025)](https://www.gov.uk/government/publications/ai-opportunities-action-plan)
