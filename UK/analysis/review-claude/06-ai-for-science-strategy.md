# AI for Science Strategy — Review

**Document:** AI for Science Strategy
**Published:** November 2025
**Issuing body:** Department for Science, Innovation and Technology (DSIT)
**Forewords by:** Kanishka Narayan MP, Minister for AI and Online Safety; Lord Vallance, Minister for Science, Innovation, Research and Nuclear
**Classification:** OFFICIAL
**Budget:** Up to 137 million pounds (from a broader 2 billion pound AI investment for 2026-2030)

---

## Summary

This is the UK's strategy for applying AI to accelerate scientific research. It sits alongside the AI Opportunities Action Plan as a sector-specific complement, focused on the research ecosystem rather than the broader economy. The strategy has two objectives: develop frontier capability in AI-driven science, and ensure the UK retains global scientific leadership as AI transforms research. It is organised around three pillars — data, compute, and people/culture — plus a section on AI-driven science (autonomous labs and AI science agents) and a mission-based approach. The first mission targets drug discovery: "develop trial-ready drugs within 100 days by 2030." The strategy identifies five scientific priority areas aligned with the Modern Industrial Strategy: engineering biology, fusion energy, materials science, medical research, and quantum technologies. It contains 15 numbered actions with delivery commitments.

---

## Key Points

### AI-Driven Science (Actions 1-2)

- **Action 1:** Accelerate development of AI-driven science in the UK. Sovereign AI Unit to launch an open call on autonomous labs. Work with teams building end-to-end AI scientist systems (including ARIA's exploratory "AI scientist" proposals). Explore access models for general-purpose AI science tools. Considers biological security implications of autonomous labs
- **Action 2:** Fund research into the methodological implications of AI in science, building on the UK Metascience Unit. UKRI/DSIT joint unit has funded 18 early career fellows studying how AI changes scientific practice (peer review, evidence synthesis, synthetic data generation, researcher wellbeing). Will conduct a "National AI in Research Survey"

### Pillar 1: Data (Actions 3-6)

- **Action 3:** UKRI mandate to scale up data storage at all UKRI facilities, labs, and institutes — aim to store, curate, and make FAIR-compliant all relevant experimental data by 2030. STFC to uplift infrastructure at Harwell's Diamond Light Source as a first step. UKRI revised data policy due 2026 with "AI-first" approach
- **Action 4:** Identify and develop high-value datasets in priority areas. DSIT collaborating with Renaissance Philanthropy on a call to source datasets. Henry Royce Institute scaling up AI-ready materials data with standardised metadata and APIs. Community-led discovery processes through open calls, workshops, hackathons
- **Action 5:** Pilot programmes for collecting "dark data" — unpublished results, negative data, non-machine-readable institutional data. UKRI to launch 3-5 pilots. DSIT/UKRI to engage industry partners for access to privately held negative data (e.g. in pharmaceuticals)
- **Action 6:** Build large-scale data infrastructure co-located with sovereign compute. New data repository at Isambard-AI (Bristol) and additional storage at Edinburgh Parallel Computing Centre. Federated access via AIRR "AIRRport" platform. Explore secure agent-to-agent data access. AIRR data capability to explore secure access to health datasets using FRIDGE programme and UK Biobank's governance model for trusted research environments

Key insight: the strategy explicitly prioritises *generating new data* over making existing data AI-ready — a deliberate choice justified by the argument that new data can be precisely tailored to research challenges, while legacy data often cannot.

### Pillar 2: Compute (Actions 7-8)

- **Action 7:** Launch AI for Science AIRR calls for compute access at all scales:
  - "Gateway" route: up to 10,000 GPU hours over 3 months (already operational)
  - Broad research call: 200,000 to 1,000,000 GPU hours over 6 months
  - "System takeover" call: up to 1,400,000 GPU hours (~80% capacity) over 2 weeks for mission-focused projects, starting with drug discovery
  - Progress reviewed every 12 months
- **Action 8:** Develop a federated network of compute clusters across research-intensive universities. DSIT/UKRI to work with Jisc (JANET network) to explore feasibility of harnessing underutilised tier 3 compute (university CPUs/GPUs) for generating simulation datasets. Could position the UK as a home for high-value simulation data

Case study: Open Molecules 2025 dataset (Meta + Lawrence Berkeley National Laboratory) — 100 million density functional theory calculations representing 83 million unique molecular systems, trained on using CPU downtime. The UK could replicate this approach using its distributed university compute.

### Pillar 3: People and Culture (Actions 9-14)

- **Action 9:** Expand AI for science doctoral training — aim to initiate training of at least 1,000 researchers fluent in both AI and domain science over the next 5 years. Emphasis on interdisciplinarity and industry engagement
- **Action 10:** Interdisciplinary fellowship programmes (Encode AI for Science Fellowships via Pillar VC and ARIA; AI Pioneer Interdisciplinary Fellowship for domain scientists wanting to build AI capability)
- **Action 11:** Diverse training programmes across all disciplines and career stages. Sparck AI scholarships (9 university partners), 38 universities in government-funded AI conversion courses, KCL first dedicated AI for science master's programme
- **Action 12:** Build interdisciplinary research teams in priority areas. Up to 137 million pounds to fund leading researchers with a focus on novel organisational structures. Modelled on Google DeepMind and Nvidia's large interdisciplinary teams. Pooling government, private sector, and philanthropic funding
- **Action 13:** Invest in research technical professionals (RTPs) — software engineers, HPC engineers, data wranglers, data stewards, AI ethics specialists. UKRI working with ITSS on career pathways. 27 universities coordinating through ITSS working group
- **Action 14:** Support community-driven benchmarking and evaluation — "CASP-style" benchmarks for AI in science beyond structural biology. DSIT/UKRI to convene communities, evaluate methodologies, and fund development of robust benchmarks

### Missions

- **Mission One:** "Accelerate drug discovery to develop trial-ready drugs within 100 days by 2030 and contribute to deploying new treatments faster"
  - Focus on the preclinical pipeline (target discovery, binding prediction, ADMET optimisation, lead optimisation, preclinical testing)
  - AI science agents for target discovery; foundation models for drug-like chemical spaces; in silico clinical trials
  - 8 million pounds for OpenBind consortium (protein-ligand structural data via Diamond Light Source)
  - 30 million pounds for preclinical translational research hub
  - Working through RIO, MHRA, Academy of Medical Sciences, CERSIs on regulatory readiness for AI-enabled ADMET models and in silico clinical trials
  - Health Data Research Service (up to 600 million pounds from HMG and Wellcome Trust) as a single access point to health data
  - Pandemic preparedness dimension: capabilities built "in peacetime" will be available for rapid response to future pandemics, complementing the "100 Days Mission"
- **Action 15:** Select further AI for science missions to be launched in 2026. DSIT/UKRI to lead selection using Government Office for Science's horizon scanning, expert engagement, and technology analysis

---

## Observations

### Clarity

This is one of the most technically literate UK government strategy documents in the AI governance landscape. It is written for a scientific audience — comfortable discussing FAIR data principles, density functional theory calculations, CASP benchmarks, and closed-loop experimental systems. The five priority areas are clearly defined and justified against the Modern Industrial Strategy. The numbered actions follow a consistent structure (why it matters, delivery commitments), making it straightforward to track what is proposed.

The Protein Data Bank case study (pp. 13-14) is particularly well-deployed — it illustrates why data generation matters by showing that AlphaFold's breakthrough depended on 50 years of curated structural data, and that replicating this in other fields requires deliberate investment in data infrastructure, not just algorithms.

The strategy is notably honest about its own limitations: "Whilst the UK is genuinely world leading in many areas, we must accept that cannot be true in every domain." This candour about selectivity and focus is unusual in UK government strategy documents, which typically claim leadership across the board.

### Measurability

Stronger than most UK AI governance documents, though uneven:

**Measurable commitments:**
- 1,000 researchers trained in AI for science over 5 years (Action 9)
- FAIR-compliant data at all UKRI facilities by 2030 (Action 3)
- 137 million pounds budget envelope
- Compute allocations specified in GPU hours (10,000 / 200,000-1,000,000 / 1,400,000)
- Trial-ready drugs within 100 days by 2030 (Mission One)
- 3-5 dark data pilots (Action 5)
- Progress reviewed every 12 months (Action 7)

**Unmeasured:**
- The 137 million is described as "up to" — not a confirmed allocation
- No breakdown of how the 137 million is distributed across the 15 actions
- "At least 1,000 researchers" is a floor with no ceiling or quality measure
- The 100-day drug discovery target is audacious but the document acknowledges the programme of work "will be built out" — it is a mission statement, not a delivery plan
- No metrics for success of the federated compute network, dark data pilots, or benchmark development

### Gaps

**Responsible AI in science.** The strategy mentions research integrity briefly (guided by the national framework on research integrity) and ARIA's consideration of biological security implications, but provides no detailed treatment of responsible AI use in science. Questions like: How should AI-generated hypotheses be validated? What are the implications of AI hallucination for scientific claims? How should authorship and credit work when AI agents contribute to discoveries? These are mentioned as topics for the Metascience Unit but not addressed.

**Social sciences and humanities.** The five priority areas are all physical/biological sciences. The strategy does not address AI in social science, economics, or humanities research, despite these fields being equally transformed by AI methods.

**International competition and collaboration.** The foreword notes "we must follow the US, the EU, and others in setting an ambitious national strategy" — an unusual acknowledgement that the UK is following rather than leading. But the strategy provides limited detail on international collaboration beyond the UK-US Tech Prosperity Deal and compute partnerships. How the UK positions against much larger US (NAIRR) and EU (EuroHPC) research compute investments is not addressed.

**Industry-academia tension.** The strategy acknowledges that "the richest AI opportunities" in drug discovery are in the preclinical pipeline, which is primarily an industry domain. But it does not address the tension between open science principles (FAIR data, open benchmarks) and pharmaceutical companies' commercial interests in keeping drug discovery data proprietary. The proposal to "engage with industry partners to seek agreements around researcher access to privately held negative data" (Action 5) is important but entirely unspecified.

**Devolution.** Edinburgh Parallel Computing Centre features prominently for infrastructure, but there is no engagement with devolved science policy. Scottish, Welsh, and Northern Irish research institutions and funding bodies are not mentioned.

### Feasibility

**Infrastructure commitments are credible.** Isambard-AI is operational, Dawn exists, EPCC is a real facility with real capacity. The co-location of data and compute is a practical, achievable step. The AIRR allocation model with tiered compute access (gateway, research, system takeover) is well-designed.

**The FAIR data mandate is ambitious but realistic** if properly resourced. UKRI controls its own facilities and can mandate data standards. The 2030 timeline for full FAIR compliance across all UKRI facilities is tight but within reach for well-funded, well-managed institutions. The Diamond Light Source uplift as a first step is a sensible sequencing.

**The dark data initiative is high-risk, high-reward.** Capturing unpublished experimental results and negative data is genuinely important for AI model training (to reduce positive bias), but the incentive structures in academia work against it. Researchers have no career incentive to publish negative results. The 3-5 pilots will test whether this can work, but scaling it will require cultural change that cannot be achieved by funding alone.

**Mission One is aspirational.** "Trial-ready drugs within 100 days by 2030" is modelled on the 100 Days Mission for pandemic preparedness. The document is honest that the programme "will be built out" and focuses on "the preclinical phase of the drug discovery pipeline, where we believe the richest AI opportunities are concentrated." This framing is realistic — 100 days from target identification to a trial-ready candidate in the preclinical phase is ambitious but conceivable with AI acceleration. However, the broader claim about "deploying new treatments faster" depends on clinical trials and regulatory approval, which are outside this strategy's scope.

**The federated compute network (Action 8) is speculative.** Harnessing underutilised university compute downtime is an attractive idea inspired by Open Molecules 2025, but implementing it requires solving non-trivial coordination, security, and incentive problems. The document correctly frames this as "explore the feasibility" rather than a commitment.

### Internal Consistency

The strategy is internally consistent and well-integrated with the broader UK AI governance landscape. It explicitly references and builds on the AI Opportunities Action Plan, the Modern Industrial Strategy, the Sovereign AI Unit, the Health Data Research Service, and the UK Compute Roadmap. The five priority areas are drawn from the Industrial Strategy's eight sectors. The compute allocations are delivered through the AIRR infrastructure announced in the Action Plan.

One tension: the strategy simultaneously advocates for open science (FAIR data, community benchmarks, open access) and for strategic data assets that give the UK competitive advantage. "The development of scientific datasets in areas of mutual priority is a stated objective of the recently signed UK-US Tech Prosperity Deal" — framing data as a geopolitical asset sits uneasily with the FAIR principles that emphasise accessibility and interoperability. The strategy does not resolve this tension.

### Coverage

For a science-focused strategy, the coverage is thorough across its chosen domains. Data, compute, people, and missions are all addressed with specific actions. The five priority areas are well-justified. The treatment of AI-driven science (autonomous labs, AI science agents) is unusually forward-looking for a government document.

Coverage gaps: responsible AI in science, social sciences/humanities, international positioning, industry-academia IP tensions, devolution, and the broader question of how AI changes the nature of scientific employment (a workforce impact question this document shares with the Action Plan's blind spot on labour markets).

---

## Overall Assessment

This is the strongest document in the UK's AI governance landscape in terms of technical substance and strategic clarity. It identifies a genuine opportunity (AI is transforming scientific research), makes honest assessments of the UK's position (strong but not universally leading), focuses resources on specific priority areas rather than spreading thinly, and provides actionable commitments with measurable targets.

Its greatest strength is the data pillar. The argument that the UK needs to prioritise *generating* new AI-ready scientific data rather than just cleaning up existing data is a genuinely original strategic insight. The Protein Data Bank case study illustrates why this matters — AlphaFold succeeded because the PDB existed, and replicating that success in materials science, chemistry, or medicine requires comparable data investments now. The dark data initiative and the federated compute-for-data-generation network are creative proposals that could give the UK distinctive capabilities.

Its greatest weakness is that it is a strategy without a confirmed budget. "Up to 137 million pounds" from a 2 billion pound envelope is significant but not guaranteed, and the document does not specify how the money would be allocated across 15 actions. The drug discovery mission is announced without a delivery plan. The people and culture actions are largely extensions of existing programmes rather than step changes in capability.

The document reads as a strategy written by people who understand the science — the references to Materials Innovation Factory, CASP, Open Molecules, and closed-loop experimental systems demonstrate genuine domain knowledge. This technical credibility gives the strategy a seriousness that is sometimes absent from higher-level UK AI policy documents.

---

## Sources

- [AI for Science Strategy (GOV.UK)](https://www.gov.uk/government/publications/ai-for-science-strategy)
- [AI Opportunities Action Plan (January 2025)](https://www.gov.uk/government/publications/ai-opportunities-action-plan)
- [UK Modern Industrial Strategy](https://www.gov.uk/government/publications/invest-2035-the-uks-modern-industrial-strategy)
