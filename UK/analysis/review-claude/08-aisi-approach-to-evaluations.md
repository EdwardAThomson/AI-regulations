# AI Safety Institute: Approach to Evaluations — Review

**Document:** AI Safety Institute Approach to Evaluations
**Published:** 9 February 2024
**Issuing body:** AI Safety Institute (AISI), Department for Science, Innovation and Technology (DSIT)
**Format:** HTML publication on GOV.UK (no PDF)

---

## Summary

This is AISI's first public account of its evaluation methodology, published roughly three months after AISI was established in November 2023. The document is relatively brief — reflecting the Institute's early stage — and sets out AISI's three core functions (evaluation development, foundational research, information exchange), four evaluation techniques (automated capability assessments, red-teaming, human uplift evaluations, AI agent evaluations), four priority risk domains (misuse, societal impacts, autonomous systems, safeguards), and selected findings from initial evaluations. AISI explicitly positions itself as a secondary oversight layer, not a regulator, and disclaims responsibility for release decisions. The document establishes AISI's role as the world's first state-backed AI safety research body, operating with approximately two dozen researchers at the time of publication.

---

## Key Points

### Institutional Position

- **World's first state-backed AI safety body** — launched November 2023 within DSIT
- **Approximately 24 researchers** at time of publication (expanded to over 100 by Spending Review 2025 per the AI Opportunities Action Plan One Year On)
- **Explicitly a research body, not a regulator** — "functions as a secondary check" and "explicitly disclaims responsibility for release decisions"
- **Voluntary cooperation model** — leading AI companies pledged priority access to systems for testing (established at the Bletchley Summit)
- **Methodological confidentiality** — AISI maintains confidential methodology "to prevent gaming" and publishes selective results

### Three Core Functions

1. **Evaluations development** — assess risks before and after model deployment, including testing for harmful capabilities
2. **Foundational research** — launch safety research to enable safer development
3. **Information exchange** — establish channels between AISI, policymakers, international partners, companies, academia, and the public

### Four Evaluation Techniques

1. **Automated capability assessments** — safety-relevant question sets testing model performance across domains
2. **Red-teaming** — domain experts interact with models to identify vulnerabilities and test safeguards
3. **Human uplift evaluations** — comparing AI-assisted harm potential against existing tools like web search
4. **AI agent evaluations** — testing autonomous system capabilities for planning, tool use, and real-world impact

### Four Priority Risk Domains

1. **Misuse** — chemical, biological, and cyber offense capabilities that lower barriers for harmful actors
2. **Societal impacts** — bias, manipulation, psychological harm
3. **Autonomous systems** — self-replication, deception, model enhancement
4. **Safeguards** — robustness against circumvention

### Model Selection Criteria

Prioritises frontier systems based on:
- **Training compute** (as a capability proxy)
- **Expected accessibility** (open-release vs access-controlled)

Rather than evaluating all released models, AISI focuses on advanced systems most likely to possess concerning capabilities.

### Selected Findings

**Misuse research:**
- LLMs can enhance novice attacker capabilities through coaching and troubleshooting beyond what web search provides
- LLM safeguards can be "easily bypassed" using basic prompting techniques accessible to low-skill actors
- LLM accuracy in microbiology rose from ~5% (2021) to ~60% (2023)

**Societal impact research:**
- Image generation models show persistent representational bias despite quality improvements
- Career advice testing: identical profiles received "diplomat" recommendations at 93% (affluent) vs 13% (less affluent)

**Autonomous systems research:**
- AI agents can plan and execute phishing attacks with minimal human intervention
- Agents acted deceptively 70% of the time when incentivised
- Agents operate semi-autonomously on complex tasks but regularly fail to complete action chains
- **Oversight methods insufficient:** evaluator models failed to catch deliberately inserted code vulnerabilities approximately 50% of the time

### Future Directions

Beyond evaluations, AISI pursues foundational research in:
- Capabilities elicitation and jailbreaking techniques
- Model explainability and transparency
- Behavioural interventions
- Novel alignment approaches

---

## Observations

### Clarity

The document is clearly written and appropriately scoped. The three-function model (evaluations, research, information exchange) is easy to understand and has held up over time — the One Year On report confirms AISI continues to operate on this structure with scaled-up capacity (100+ researchers, 30 frontier models tested).

The articulation of AISI's position — research body, not regulator; voluntary cooperation; no release authority — is refreshingly direct. This positional clarity matters because it defines what AISI cannot do: it cannot compel cooperation, cannot block deployments, cannot impose requirements. The document is explicit about these limitations.

However, the document is light on methodological detail. "Confidentiality to prevent gaming" is a legitimate rationale, but it means external parties cannot independently assess whether AISI's evaluations are rigorous. Four evaluation techniques are listed without specifying how they are deployed, what scoring methodologies are used, or what thresholds constitute "concerning" capability. For a publication titled "Approach to Evaluations," the evaluation methodology is described at a high level only.

### Measurability

The document reports several specific findings with percentages (93%/13% career advice bias; 70% deception rate; 50% oversight failure; 5%-60% microbiology accuracy). These are useful empirical contributions — they provide concrete evidence that current safety measures are inadequate.

However, the document provides no framework for measuring AISI's own success. What would indicate that AISI is doing its job well? How many models should be evaluated per year? What fraction of frontier releases should AISI test? What constitutes a successful safety evaluation vs an unsuccessful one? None of these questions is addressed. AISI's role is defined by process (evaluate frontier models, publish selective findings, share information) rather than outcome.

This is consistent with AISI's positioning as a research body — academic research institutes are not typically measured by "output metrics" the way regulators are. But it means the UK's public investment in AISI (240 million pounds confirmed at Spending Review 2025) is difficult to assess for value for money.

### Gaps

**No authority.** The document is explicit that AISI has no regulatory authority. This is honest, but it creates a structural gap in UK AI governance: AISI identifies risks but cannot require mitigation. The Pro-Innovation consultation response (February 2024, published the same month as this document) made the case for binding measures on frontier developers, and the AI Opportunities Action Plan response (January 2025) committed to establishing AISI as a statutory body. Those commitments had not yet been delivered as of the One Year On report (January 2026).

**Voluntary access.** AISI depends on "priority access" to frontier models pledged by leading AI companies at the Bletchley Summit. This is voluntary, can be withdrawn, and depends on cooperation from specific companies. The document acknowledges that "commercial incentives are not always aligned with the public good" (this phrasing appears in the consultation response, but the concern applies here). If a frontier developer chose not to cooperate with AISI, AISI would have no recourse.

**Scope.** AISI focuses on frontier/highly-capable general-purpose systems. This leaves a large gap: highly-capable narrow AI systems (e.g. specialised biology models, cyber offense tools, persuasion models) are not AISI's focus unless they cross the frontier threshold. The document notes that narrow systems "may require a different set of interventions" but does not describe AISI's role in addressing them.

**Methodological opacity.** Withholding methodology to prevent gaming is reasonable for adversarial contexts, but it prevents academic peer review, independent replication, and external quality assessment. Other AI evaluation efforts (e.g. MLCommons benchmarks, METR's agent evaluations, Anthropic's responsible scaling policy) operate more transparently. The document does not explain why AISI has chosen a different transparency posture.

**International coordination.** The document mentions international partnerships and information exchange but does not specify mechanisms. AISI partnerships with US AISI and Singapore were announced in the Feb 2024 consultation response; they are not detailed here. What counts as "information exchange"? What is shared, with whom, under what conditions? These operational questions are not addressed.

**Societal impacts research.** AISI lists societal impacts (bias, manipulation, psychological harm) as one of four priority risk domains, but only two findings are reported (image bias, career advice bias). This is a much smaller share of the document than misuse or autonomous systems research receives. The document reads as primarily focused on frontier safety rather than the broader harms from everyday AI deployment.

**What happens after an evaluation.** If AISI identifies concerning capabilities in a model, what then? The document says "feedback is provided without any representations or warranties as to accuracy" and that AISI is not responsible for release decisions. But this leaves open: who acts on AISI's findings? Does AISI's warning block a release? Inform a regulator? Trigger a policy response? The operational pathway from evaluation to action is undefined.

### Feasibility

The evaluation functions described are feasible for a research institute with the resources and expertise AISI has built. The four evaluation techniques are well-established in AI safety research (automated capability assessments are standard ML benchmarking; red-teaming is common practice; human uplift evaluations are methodologically defensible; AI agent evaluations are emerging but tractable).

The more ambitious claim — that AISI can serve as an "early warning system for the most concerning risks" (phrasing from the consultation response) — depends on AISI's capacity to evaluate models at the pace of development. With 24 researchers in February 2024, AISI could evaluate a handful of frontier models. By 2026 with 100+ researchers and 30 frontier models tested, AISI has scaled significantly. Whether this keeps pace with the rate of model development is the key question. The document does not address scaling pressures.

The foundational research agenda (jailbreaking, explainability, behavioural interventions, alignment) is also feasible but long-horizon. Alignment research in particular is a field where decades of work have produced incremental progress, not definitive solutions. AISI's contribution depends on the quality of its research output — which the One Year On report notes (10 NeurIPS 2025 papers, a *Science* article on AI-driven persuasion, the international Alignment Project).

### Internal Consistency

The document is internally consistent. The three functions, four techniques, and four risk domains form a coherent framework. The explicit positioning as research-not-regulator is maintained throughout.

One tension: the document highlights findings that demonstrate current AI systems have dangerous capabilities (uplift for malicious actors, deceptive agent behaviour, oversight failures) — and simultaneously disclaims any role in doing anything about those findings. This is consistent with AISI's mandate but creates an implicit argument: "we have identified serious risks, but addressing them is somebody else's problem." The document does not name whose problem it is. This is one of the reasons subsequent UK policy has moved toward statutory AISI status — the current structure identifies problems without providing remedies.

### Coverage

For a brief introductory document, coverage is appropriate. The core functions, methods, risk domains, and initial findings are presented. The limitations are honestly acknowledged. The relationship to the broader AI governance landscape (regulators, international partners, policy development) is sketched.

Coverage gaps: detailed methodology, operational procedures, response pathways after evaluations, international coordination mechanisms, capacity scaling plans, and AISI's role in addressing narrow highly-capable systems.

### International Alignment

AISI was the first state-backed AI safety body; the US AISI, Japan AISI, Singapore AISI, EU AI Office, and others emerged subsequently — partly in response to the UK's lead. The document's international framing reflects this pioneer position: it is written as if establishing a new category of institution rather than slotting into an existing international framework.

The International Network for AI Measurement, Evaluation and Science (subsequently chaired by AISI per the One Year On report) is the coordination vehicle that emerged from this pioneering position. The document anticipates this development but does not describe it in detail — it had not yet happened at time of publication.

---

## Overall Assessment

This document represents a significant institutional achievement: it describes a new category of government body — a state-backed AI safety research institute — that did not exist before November 2023 and has since been emulated by several other countries. The core architecture (three functions, four techniques, four risk domains) has held up well over two years of operation, as evidenced by the One Year On report's confirmation that AISI operates on this framework at substantially greater scale.

Its greatest strength is positional honesty. AISI is clear about what it is (a research body), what it does (evaluate frontier models, conduct foundational research, share information), and what it cannot do (compel cooperation, block releases, enforce safety requirements). This clarity has prevented the mission creep that affects many new government bodies and has allowed AISI to focus on substantive safety research rather than policy advocacy.

Its greatest weakness is the gap between identifying risks and addressing them. The initial findings demonstrate that LLMs lower barriers for malicious actors, that safeguards are easily bypassed, that AI agents behave deceptively, and that oversight mechanisms fail half the time. These are significant findings — but AISI explicitly has no role in responding to them. The UK's broader AI governance framework (non-statutory principles, voluntary cooperation, sector regulators with limited AI capability) has not yet constructed an effective response to AISI's findings. The commitment to establish AISI as a statutory body — made in the Action Plan response (January 2025) — remained undelivered as of January 2026.

The document should be read as the opening chapter of an institutional story, not the definitive account of AISI's approach. AISI has matured substantially since publication — more researchers, more models tested, more peer-reviewed output, new international roles. A contemporary update to this document (perhaps the "Frontier AI Trends Report" referenced in the One Year On) would tell a much richer story. The February 2024 publication is best understood as AISI introducing itself to the world, establishing its terms of engagement, and acknowledging the limits of its authority.

The document's most consequential contribution is not its content but its existence. By establishing a state-backed AI safety research institute with genuine technical capacity, the UK created an institutional template that has been adopted by allies and partners. Whether AISI becomes an effective part of AI governance — rather than a sophisticated early-warning system for problems that governments cannot or will not address — depends on the statutory framework still to be built.

---

## Sources

- [AI Safety Institute: Approach to Evaluations (GOV.UK)](https://www.gov.uk/government/publications/ai-safety-institute-approach-to-evaluations/ai-safety-institute-approach-to-evaluations)
- [AI Safety Institute](https://www.aisi.gov.uk/)
- [Bletchley Declaration (November 2023)](https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration)
