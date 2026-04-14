# International Scientific Report on the Safety of Advanced AI (Interim) — Review

**Document:** International Scientific Report on the Safety of Advanced AI — Interim Report
**Published:** May 2024 (for the AI Seoul Summit, 21-22 May 2024)
**Commissioned at:** AI Safety Summit, Bletchley Park, November 2023
**Chair:** Prof. Yoshua Bengio (Université de Montréal / Mila)
**Scientific Lead:** Sören Mindermann (Mila)
**Secretariat:** UK AI Safety Institute (with co-secretariat from Mila)
**Reference:** DSIT 2024/009
**Length:** 132 pages
**Contributors:** 75 AI experts; 30 countries plus EU and UN nominated Expert Advisory Panel members

**Note:** This is a cross-national scientific consensus document, not a UK-only publication. It is housed in the UK source inventory because the UK AI Safety Institute serves as secretariat and the UK was the commissioning summit host. The document is positioned to be iterated — this interim report was prepared for the Seoul Summit with a final version intended for the France AI Action Summit.

---

## Summary

The report is the first systematic attempt to produce an internationally authored scientific assessment of general-purpose AI (GPAI) safety, modelled on the Intergovernmental Panel on Climate Change process. It synthesises existing research rather than producing original contributions. The scope is explicitly general-purpose AI (models that can be adapted to a wide variety of tasks) — not AGI, not narrow AI, and not lethal autonomous weapons systems. The report is organised around three risk categories — malicious use, malfunctions, and systemic risks — plus cross-cutting technical and societal risk factors. It does not make policy recommendations. It reports on the current state of scientific knowledge, flagging areas of consensus, areas of active disagreement, and areas where evidence is insufficient. The report concludes with technical approaches to safety mitigation and a conclusion emphasising that "the future trajectory of general-purpose AI is remarkably uncertain" and "no consensus among experts about how likely these risks are and when they might occur."

---

## Key Points

### Process and Governance

- **Commissioned at Bletchley (November 2023)** with UK Government agreement that scientists should have "complete independence"
- **Expert Advisory Panel nominated by 30 countries** (Australia, Brazil, Canada, Chile, China, France, Germany, India, Indonesia, Ireland, Israel, Italy, Japan, Kenya, Mexico, Netherlands, New Zealand, Nigeria, Philippines, Republic of Korea, Turkey, Rwanda, Saudi Arabia, Singapore, Spain, Switzerland, Ukraine, UAE, USA, UK) plus the European Union and United Nations
- **Writing group of 15 researchers** led by Daniel Privitera (KIRA Center)
- **Senior advisers** include Paul Christiano, Stuart Russell, Arvind Narayanan, Percy Liang, Dawn Song, Andrew Yao, Ya-Qin Zhang, Helen Margetts, Marietje Schaake, Alondra Nelson
- **Private sector representatives intentionally excluded** from input "to avoid conflicts of interest" — Chair notes this as a limitation and calls for company input in the next version
- **Only one formally recorded dissent** from Expert Advisory Panel: Ciarán Seoighe (Ireland) on tone being "excessively negative" and on omission of human/fundamental rights framework

### Scope and Framing

- **Focuses on general-purpose AI** — models that can perform or be adapted to a wide variety of tasks
- **Explicitly excludes:** narrow AI, LAWS (lethal autonomous weapon systems), chemical/radiological/nuclear misuse risks (insufficient scientific work)
- **Does not recommend policy options** — "policymakers must balance opportunities and risks"
- **Emphasises intellectual honesty** — airs disagreements explicitly rather than forcing false consensus

### Capabilities Growth

- ~4x compute for training per year
- 2.5x training dataset size per year
- 1.5x-3x algorithmic efficiency per year
- 3x energy for training chips per year
- Compute 2010-2023: ~10 billion-fold increase (1e15 FLOP to 1e25 FLOP)
- **Forward projection:** "By end of 2026 some general-purpose AI models will be trained using 40x to 100x more compute than the most compute-intensive models published in 2023, combined with training methods that use this compute 3x to 20x more efficiently"
- ChatGPT reached 100 million users within two months of launch — fastest-growing consumer app in history
- AI electricity requirement projected: at least 70 TWh in 2026 globally (roughly Austria or Finland consumption)
- Water consumption by AI systems could reach billions of cubic metres by 2027

### Risk Categories

**Malicious use:**
- Harm via fake content (phishing, spear-phishing, voice cloning, non-consensual deepfake pornography, CSAM)
- 135% increase in novel social engineering attacks Jan-Feb 2023 attributed to widespread ChatGPT adoption
- Disinformation and election manipulation — but "not much scientific evidence about the impact of such campaigns"
- Cyber offence — current GPAI can do basic cybersecurity tasks but cannot yet do multi-step sophisticated attacks
- **Biological risk:** evidence on "uplift" is mixed. Report notes malicious actors need information, hands-on expertise, and access to materials/tools. Current GPAI provides growing capability but limited evidence it uplifts beyond internet search
- Integration with narrow biological design tools (AlphaFold 3, protein design tools) is an emerging area

**Malfunctions:**
- Product functionality issues — misleading claims about model capabilities (GPT-4 bar exam vs actual legal practice failures)
- Bias and underrepresentation — racial, gender, age, disability, linguistic. "Despite considerable attention, mitigating bias remains an unsolved challenge"
- **Loss of control** — scenarios where society can no longer meaningfully constrain advanced GPAI. "Broad agreement among AI experts that currently known GPAI systems pose no significant loss of control risk." Expert disagreement on likelihood, timing, and mitigation difficulty. Over 100 researchers signed statement: "Mitigating the risk of extinction from AI should be a global priority"

**Systemic risks:**
- **Labour market:** 60% of jobs in advanced economies and 40% in emerging economies could be affected by LLMs. ChatGPT mass adoption already caused decrease in employment and earnings for freelance writers/editors. Wage and employment effects ambiguous
- **Global AI divide:** R&D concentrated in few Western countries plus China. American institutions produced 54% of large language and multimodal models in 2022. NVIDIA H100 GPUs at 15,000 USD hinder academic and poorer-country access. Ghost work industry (content moderation, data labelling) often in low-wage countries with limited protections
- **Market concentration:** State-of-the-art GPAI costs hundreds of millions to billions. Single GPAI model could influence many organisations simultaneously — systemic risk
- **Environment:** Data centres account for 1-1.5% of global electricity; AI rapidly growing. 2023's largest training runs used ~5e25 FLOP; by end of decade, largest run could consume 90 TWh (over half US data centre electricity in 2022). ML efficiency improves 26% annually but demand grows 4x annually
- **Privacy:** Models can memorise and leak training data. Adversarial inputs can extract training examples. Deepfakes hard to prevent technically
- **Copyright:** ~60% of popular datasets in widely used repositories have incorrect or missing licence information. Legal frameworks diverge (US fair use, EU TDM exception, Japan amendment, Israel, Singapore Copyright Act 2021)

**Cross-cutting technical risk factors:**
- Applied in many contexts, hard to test trustworthiness
- Limited understanding of internal workings
- Spec gaming / goal misgeneralisation
- Rapid global deployment
- Immature evaluation methods
- Cannot prevent all overtly harmful behaviours ("jailbreaking" techniques)
- Increasing autonomy — agent benchmarks show accuracy improving 2.2x-7.1x over months

**Cross-cutting societal risk factors:**
- Race-to-bottom dynamics in winner-take-all markets
- Regulatory response lags
- Liability hard to determine
- Tracking difficult — no broadly accepted GPAI safety standards

### Technical Safety Approaches Surveyed

**Risk management:**
- "No well-established risk management/safety engineering practices for GPAI"
- "Defence in depth" / Swiss-cheese model proposed
- Safety cases structured evidence-based arguments
- Quantitative risk thresholds (as in nuclear — one in a million radioactive release) "not yet clear how quantitative safety guarantees could be obtained" for GPAI
- Model cards, pre-defined capability thresholds

**Training more trustworthy models:**
- Alignment: state-of-the-art relies on human feedback (RLHF); researchers "do not know how to specify abstract human preferences and values"
- Sycophancy problem — models match stated user views regardless of truth
- Scalable oversight (AI overseeing AI) — "highly preliminary"
- Safe-by-design / provably safe — "practically-useful, provable guarantees of safety are not possible with general-purpose AI models and methods" currently
- Hallucination reduction — active research area, no elimination
- Adversarial robustness — fundamental trade-off with clean data performance
- Machine unlearning — imperfect, introduces side effects

**Monitoring and intervention:**
- AI content detection classifiers "limited and prone to false positives"
- Watermarks work against unsophisticated users but removable
- Model explanations often misleading
- Humans-in-the-loop effective for high-stakes but impractical at scale

**Fairness:**
- Mathematical impossibility results — "may not be possible to satisfy all aspects of fairness simultaneously"
- Experts disagree on achievability
- Google Gemini's ethnically diverse Nazi-era soldiers cited as fairness misfiring example

**Privacy:**
- Existing privacy-enhancing technologies don't scale to large GPAI
- Differential privacy impairs accuracy; cryptographic approaches too costly
- Some privacy abuses (non-consensual deepfakes) "hard to prevent through technical means"

**Interpretability:**
- "Mechanistic interpretability has not yet been useful and competitive with other analysis methods for practical applications"

### Stated Key Limits of Scientific Knowledge

1. No quantitative safety guarantees for advanced GPAI
2. No method ensures harmlessness in all circumstances
3. Mechanistic interpretability does not yet work on state-of-the-art models
4. Hallucinations cannot be eliminated, only reduced
5. Adversarial robustness intractable to guarantee
6. Fairness cannot be fully satisfied (impossibility results)
7. Privacy-preserving techniques don't scale to frontier models
8. Scalable oversight is highly preliminary
9. Explanations produced by LLMs are often misleading
10. No consensus among experts on likelihood or timing of large-scale risks

---

## Observations

### Clarity

The report is clearly written and accessibly structured for a document produced by 75 experts from over 30 countries. The three-category risk taxonomy (malicious use, malfunctions, systemic risks) plus cross-cutting factors is coherent and covers the space effectively. The distinction between capabilities (what models can do) and capability-limitation pairs (knowledge vs inconsistency, creativity vs hallucination, formal reasoning vs compositionality) is analytically useful.

The glossary (pp. 87-90) is a significant contribution — a 40+ term glossary agreed by an international expert panel creates common language that subsequent governance documents can reference. The definitions of "general-purpose AI" and "frontier AI" are particularly important given how loosely these terms are used in policy literature.

The report's greatest clarity virtue is its intellectual honesty about uncertainty. Rather than forcing scientific consensus where none exists, it explicitly flags disagreements: experts disagree about scaling, about loss of control plausibility, about labour market outcomes, about achievability of fairness, about AGI. This honesty is rare in policy-adjacent documents and is the report's most valuable contribution.

Some clarity weaknesses: the chapter structure (Capabilities -> Methodology -> Risks -> Mitigations -> Conclusion) is logical but the risk chapter is very long and the mitigation chapter somewhat fragmented. The decision to handle "differing views" in a single page at the end (p. 86) rather than integrating disagreements into the main text means the reader can miss key points of dissent.

### Measurability

The report is full of specific numbers: compute growth rates, training costs, parameter counts, benchmark scores, carbon footprints, wage impacts, adoption rates. This empirical grounding is a substantial strength.

Where it is (appropriately) unmeasured is in its conclusions about risks. The report declines to assign probabilities to extreme outcomes (extinction risk, mass unemployment, loss of control) — because the scientific community does not have agreed methodology to do so. This is honest. But it means the report cannot directly inform cost-benefit analysis of policy interventions.

The report also does not propose metrics by which AI safety could be measured over time. Subsequent iterations would benefit from a "state of AI safety" dashboard — capabilities, risks identified, mitigations deployed — that could track change. As an interim report, this is reasonable to defer; whether the final version includes such metrics would be the test.

### Gaps

**Policy recommendations.** By design, the report makes no policy recommendations. This is its IPCC-like positioning — scientific input to policy, not policy advice. But it means the report cannot be directly translated into regulatory action. Other documents (UK white paper, EU AI Act, etc.) must make the policy leap. The gap between "here is what science knows about AI risks" and "here is what governments should do" is substantial and the report does not bridge it.

**Human rights framework.** Ireland's formal dissent flags this explicitly: the report does not assess AI risks through a human rights lens. Given that several AI governance frameworks (Council of Europe AI Convention, UNESCO AI Ethics Recommendation, EU AI Act) use human rights as organising principles, the report's omission is consequential. Risks are analysed in technical and societal terms, not in terms of specific rights that might be violated.

**Private sector exclusion.** Excluding private sector representatives "to avoid conflicts of interest" is a defensible methodological choice but means the report lacks industry perspective on risk mitigation, deployment practice, and commercial incentives. Frontier AI is developed primarily by private companies; a scientific report on AI safety that excludes them has a significant blind spot. The Chair acknowledges this and commits to including company input in the next version.

**Narrow AI and LAWS.** Narrow highly-capable AI (biological design tools, cyber offence tools, persuasion models, facial recognition) is out of scope. So are lethal autonomous weapon systems. Both are substantial categories of AI risk. The scope choice is explained by the commission's focus on frontier general-purpose AI, but it creates an incomplete picture of AI safety challenges.

**Environmental and AI Divide underdeveloped.** The Chair explicitly notes these as areas needing more depth in the next version. The current treatment is useful but short — a few pages on each for a global assessment document is not proportionate to the significance of the issues.

**Chemical/radiological/nuclear risks explicitly excluded** due to insufficient scientific work. This is honest but creates a gap — terrorism and weapons of mass destruction concerns motivate much AI safety policy, and excluding them from the scientific assessment leaves a scientifically-uninformed space where policy is being made.

**Agentic AI developing faster than report captures.** The report was written in late 2023 / early 2024. AI agents advanced substantially through 2024 and 2025 (as captured in the UK Feb 2024 consultation response, which notes "agentic AI" as a formal category). The interim report notes agent capability improvements of 2.2x-7.1x over "a few months" — but the categorisation of risks is less well-developed for agentic systems than for chatbots and content-generation systems.

**Interim status.** The report is explicitly interim. A final version was intended for the France AI Action Summit. Whether that final version was produced and published, and how its conclusions evolved, is outside the scope of this interim document but is important context for any reader.

### Feasibility

The report's core activity — synthesising existing scientific research on AI safety — is feasible and was clearly delivered. 75 international experts produced a coherent 132-page document with extensive citations. The process demonstrates that international scientific assessment of AI safety can be done at scale.

The ambition of "sustained over time" — producing iterated reports that track the evolving state of science — is more challenging. The IPCC analogy is apt: climate science consensus reports take years to produce with large bureaucratic infrastructure. AI science moves faster than climate science, so the iteration cycle needs to be faster, but the international coordination that makes the output authoritative is slow.

The Chair's note acknowledges several improvements planned for the next version: more literature, more methodology assessment, more nuanced synthesis, private sector input, environmental depth, AI Divide depth, scope delineation. Delivering all of these in time for the next summit would be demanding.

### Internal Consistency

The report is internally consistent. The three risk categories and cross-cutting factors are held throughout. The empirical data is consistent within the document (compute growth rates, benchmark scores, cost figures). The acknowledgements of uncertainty are consistent.

One tension, acknowledged in the text: "broad agreement among AI experts that currently known GPAI systems pose no significant loss of control risk" sits alongside "hundred researchers signed statement that mitigating extinction risk should be a global priority." The report handles this by distinguishing current systems (consensus: no significant risk) from future systems (expert disagreement on likelihood, timing, mitigation difficulty). This distinction is defensible but invites the question: how much weight should policymakers give to current consensus vs future disagreement? The report does not address this directly.

### Coverage

Coverage within scope is comprehensive. All the major categories of identified AI risk are addressed. Technical mitigation approaches are surveyed. The international expert panel provides geographic and disciplinary breadth.

Coverage gaps (discussed above): human rights framework, narrow AI and LAWS, chemical/radiological/nuclear, private sector perspective, environmental depth, Global AI Divide depth, policy recommendations (by design), agentic AI specifics.

### International Alignment

As a cross-national scientific consensus document, the report is itself an artefact of international alignment. Expert Advisory Panel members from 30 countries plus EU and UN is a genuine international commitment. The secretariat being hosted by UK AISI — with Mila as co-secretariat — reflects the UK's lead role in creating AISI while acknowledging that Canada is also a centre of AI safety research.

The report's deliberate positioning as "scientific input, not policy recommendations" creates space for different jurisdictions to use it in different ways. The EU AI Act's horizontal regulation, the UK's context-based approach, the US's voluntary commitments, and China's sector-specific regulation all draw on different aspects of AI risk. A shared scientific baseline, even without policy recommendations, supports international dialogue.

What the report does not do — harmonise international AI safety standards — is not its job. The follow-on question, whether this scientific baseline is used by summits and regulators to develop common standards, remains open. The One Year On report (January 2026) notes that AISI now chairs the International Network for AI Measurement, Evaluation and Science, suggesting some operationalisation has occurred.

---

## Overall Assessment

This interim report is a significant institutional achievement. Producing an internationally authored scientific consensus document on AI safety, with formal representation from 30+ countries plus EU and UN, demonstrates that international AI governance can rely on shared scientific foundations in the way climate governance relies on IPCC assessments. The document is substantively credible — 75 experts, extensive citations, careful handling of uncertainty, honest acknowledgement of disagreement.

Its greatest strength is intellectual honesty about the limits of scientific knowledge. The explicit statement that "no existing techniques currently provide quantitative guarantees about the safety of advanced general-purpose AI models or systems" is a finding with significant implications. It means the UK's voluntary cooperation model, the EU's risk-classification approach, and the US's voluntary commitments all operate without underlying scientific assurance that AI systems can be made safe. This is not a comfortable finding for any jurisdiction, but it is the scientifically accurate position.

Its greatest weakness is the gap between scientific finding and policy action. The report explicitly declines to recommend policy. Governments must therefore decide, without scientific direction, how to respond to findings like "loss of control is disputed among experts," "bias mitigation remains unsolved," "provable safety guarantees are not possible," and "there is no consensus on likelihood of large-scale risks." The report provides the inputs; the political process must produce the outputs.

The report is best understood as the opening instalment of a long-running scientific assessment process. Its methodological and substantive choices — what to include, how to handle disagreement, how to treat uncertainty — will shape subsequent iterations. The Seoul Summit audience received an interim report; the Paris audience was intended to receive a more developed one. The ongoing value of this instalment depends on whether the process continues, the scope broadens (to narrow AI, human rights, environmental impact), and the iteration keeps pace with AI development.

For the UK specifically, the report serves multiple functions: it validates the UK's investment in AISI as internationally consequential, it provides scientific backing for the UK's claim to lead on AI safety, and it demonstrates that UK governance choices (non-statutory principles, voluntary cooperation) operate in an environment where science cannot provide safety guarantees. Whether UK policymakers have integrated the report's findings into subsequent regulatory decisions is a question the document itself does not and should not address.

The Ireland dissent — that the report is "excessively negative" and omits human rights — deserves final mention. The report's tone is not pessimistic so much as cautious, reflecting the authentic state of scientific uncertainty. The human rights omission is more consequential and would be a significant addition for the final version. Ireland's recorded dissent is itself a sign of institutional health: a scientific process that allows and records dissent is more credible than one that produces unanimous but potentially superficial consensus.

---

## Sources

- [International Scientific Report on the Safety of Advanced AI — Interim Report (GOV.UK)](https://www.gov.uk/government/publications/international-scientific-report-on-the-safety-of-advanced-ai)
- [AI Seoul Summit](https://www.aisafetysummit.gov.uk/)
- [Bletchley Declaration (November 2023)](https://www.gov.uk/government/publications/ai-safety-summit-2023-the-bletchley-declaration)
- [Mila — Quebec AI Institute](https://mila.quebec/)
