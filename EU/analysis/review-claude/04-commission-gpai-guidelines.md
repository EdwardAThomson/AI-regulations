# Commission Guidelines on GPAI Model Obligations — Review

**Document:** Commission Guidelines on the scope of the obligations for providers of general-purpose AI models established by Regulation (EU) 2024/1689 (AI Act)
**Published:** Brussels, 18 July 2025
**Reference:** C(2025) 5045 final — Annex to the Communication from the Commission
**Issuing body:** European Commission
**Length:** 34 pages plus technical Annex on compute estimation
**Legal basis:** Article 96(1) of the AI Act
**Legal status:** Non-binding — authoritative interpretation ultimately rests with the CJEU

---

## Summary

These Guidelines clarify the scope of the Chapter V obligations for providers of general-purpose AI models (GPAI). Published two weeks before the GPAI obligations entered application on 2 August 2025, they address four operational questions: (i) when a model is a GPAI model; (ii) who is a provider placing a GPAI model on the Union market; (iii) which obligations are exempt for open-source models; and (iv) how enforcement will work during the 2025-2026 transition. The Commission takes several consequential interpretive positions, notably: a **10^23 FLOP + language/image/video generation** indicative criterion for GPAI model classification (complementing the 10^25 FLOP threshold for systemic risk); a single-lifecycle treatment of models (pre-training, fine-tuning, post-training enhancements treated as one model); a **one-third-of-training-compute rule** for when downstream modifiers become providers; a narrow but workable open-source exemption requiring genuine free-and-open licensing plus publicly available parameters and lack of monetisation; and a phased enforcement approach giving existing models until 2 August 2027 to comply and creating a grace year for Commission enforcement powers until 2 August 2026. The Annex provides technical formulas for compute estimation (hardware approach: N·L·H·U; architecture approach: 6·P·D) that will be load-bearing for scope determinations.

---

## Key Points

### When Is a Model a GPAI Model? (Section 2.1)

**Commission's indicative criterion** (paragraph 17): a model is presumed to be a GPAI model if:
- Training compute **> 10^23 FLOP**, AND
- Can generate language (text or audio/speech), text-to-image, or text-to-video

Rationale: 10^23 FLOP is the approximate amount needed to train a ~1 billion parameter model on a large amount of data. Language generation (including code and speech) inherently confers wide capability.

**Models out of scope of the criterion:**
- Sub-10^23 FLOP models (even if they can generate text)
- Narrow-task specialised models above 10^23 FLOP (speech-to-text transcription, text-to-speech, image upscaling, image inpainting, image generation for narrow tasks, chess/video game playing, weather/physics modelling, music generation for specific tasks, sound effects)

The criterion is **rebuttable in both directions** (paragraph 20): a model meeting the threshold but exceptionally lacking generality is NOT a GPAI model; a model below the threshold but exceptionally demonstrating generality IS.

### Lifecycle of a GPAI Model (Section 2.2)

**Single model, single lifecycle** (paragraphs 22-24): the Commission treats pre-training, fine-tuning, post-training enhancements, distillation, quantisation, and weight merging as all part of the same model lifecycle — not giving rise to new models. The lifecycle begins at the **start of the large pre-training run**.

Implications:
- Technical documentation (Art 53(1)(a)-(b)) kept up to date throughout entire lifecycle
- Copyright policy (Art 53(1)(c)) applied throughout entire lifecycle
- Training data summary (Art 53(1)(d)) updated throughout entire lifecycle
- Systemic risk assessment and mitigation (Art 55(1)) carried out continuously

### Systemic Risk GPAI Models (Section 2.3)

**Two routes to systemic risk classification** (Article 51):
1. **High-impact capabilities** — presumed at **> 10^25 FLOP cumulative training compute** (Article 51(2))
2. **Commission designation** — ex officio or on qualified alert from the scientific panel (Annex XIII criteria)

**Notification (Article 52):** Providers must notify the Commission **within 2 weeks** of meeting or expecting to meet the threshold. Notification may be required *before* training is complete if the provider can reasonably foresee the threshold will be met — because "planning and upfront allocation of compute resources take place before the start of the large pre-training run" (paragraph 31).

Notification must include (paragraph 32):
- Estimated compute in FLOP with two significant figures (e.g., 2.3×10^25 FLOP)
- Description of estimation approach

**Contesting classification:** Providers may submit arguments that despite meeting the threshold, the model does not present systemic risks (Article 52(2)). The burden of adducing evidence rests on the provider. Mitigations already or planned to be implemented are **NOT suitable grounds** for exclusion from classification — the model still poses systemic risks and must be continuously assessed and mitigated (paragraph 40).

**Procedural rights** (paragraph 36): Right to be heard (via draft decision letter), right to access the file respecting confidentiality. Commission decisions must include reasons.

**Reassessment:** Earliest 6 months after designation; subsequent reassessments at 6-month intervals. Must provide "objective, detailed and new reasons" (paragraph 47).

### Who Is a Provider Placing a GPAI Model on the Union Market? (Section 3)

**Provider definition** (Article 3(3)): natural/legal person, public authority, agency developing or having developed a GPAI model and placing it on the market under their own name or trademark, for payment or free.

**Provider examples (paragraph 51):**
- Actor A develops and places the model → A is provider
- Actor A commissions B to develop, places the model → A is provider
- Actor A develops, uploads to repository C → A is provider
- Collaboratives/consortia: usually the coordinator is provider (case-by-case)

**Placing on the market examples (paragraph 53):**
- Software library or package first release in EU
- API first made available to EU market
- Public catalogue/hub/repository for direct download
- Physical copy
- Cloud computing service
- Copying onto customer's own infrastructure
- Integration into chatbot via web interface
- Integration into mobile application via app stores
- Used for internal processes essential for providing products/services to third parties OR that affect rights of natural persons in the Union

**Third-country providers** must appoint an **EU authorised representative** before placing a model on the Union market (Article 54).

### Upstream/Downstream in Integrated AI Systems

Three scenarios for GPAI models integrated into AI systems (paragraphs 55-59):

1. **Provider integrates own GPAI model into own AI system placed on the EU market** — the model is considered placed on the market; GPAI provider obligations apply **in addition** to AI system obligations
2. **Upstream actor provides model to downstream actor in EU** — upstream actor is provider of the model; downstream actor may be provider of the integrated AI system
3. **Upstream actor provides model to downstream actor outside EU, who integrates into AI system placed on the EU market** — upstream actor is considered provider of the model UNLESS upstream actor has clearly and unequivocally excluded EU distribution/use. If not excluded, upstream GPAI obligations apply at the moment the AI system enters the EU market.

### Downstream Modifiers Becoming Providers (Section 3.2)

**The one-third-of-compute rule** (paragraphs 62-64) — a downstream modifier becomes provider of the modified GPAI model when:

- Training compute used for modification **> one-third** of the training compute of the original model, OR
- Where original compute cannot be known/estimated:
  - If original was a systemic risk GPAI model: threshold is **one-third of 10^25 FLOP (~3.3×10^24)**
  - Otherwise: **one-third of 10^23 FLOP (~3.3×10^22)**

**Rationale:** compute required to perform a given modification is typically proportional to the number of parameters of the model. The threshold scales with model size while ensuring equal treatment regardless of parameter count.

**Limited obligations for downstream modifiers** (paragraph 68, referencing recital 109):
- Documentation (Art 53(1)(a)-(b)) limited to the modification
- Copyright policy (Art 53(1)(c)) limited to data used for the modification
- Training data summary (Art 53(1)(d)) limited to data used for the modification

**Systemic risk inheritance** (paragraphs 70-71): if a downstream actor modifies a systemic risk GPAI model to the point of becoming a provider, the resulting model is **presumed to have high-impact capabilities** and is therefore classified as systemic risk. The downstream modifier must comply with full Article 55 obligations and notify the Commission per Article 52.

### Open-Source Exemptions (Section 4)

**Scope of exemptions** (paragraph 73) — for providers meeting the three cumulative conditions:
- Article 53(1)(a): technical documentation — exempt
- Article 53(1)(b): info for downstream providers — exempt
- Article 54: authorised representative for third-country providers — exempt

**NOT exempt** (paragraph 75):
- Article 53(1)(c): copyright policy including respecting Article 4(3) DSM Directive opt-out
- Article 53(1)(d): publicly available summary of training data
- Any obligation if model has systemic risk

**Three cumulative conditions for exemption:**

**1. Free and open-source licence (paragraphs 76-84):**
- Must grant access (no payment requirements, though reasonable safety measures permitted)
- Must allow usage (no restrictions on what the model is used for, beyond attribution/copyleft-style terms)
- Must allow modification
- Must allow redistribution (including under different licence terms)

Disqualifying restrictions include:
- Non-commercial-only licences (e.g., "research purposes only")
- Prohibitions on distributing the model
- User scale thresholds triggering additional licensing (e.g., ">X monthly active users require commercial licence")
- Separate commercial licences for specific use cases

**Permissible safety restrictions** (paragraph 84): "safety-oriented terms that reasonably restrict usage in applications or domains where such use would pose a significant risk to public safety, security, or fundamental rights" — must be proportionate, objective, non-discriminatory.

**2. Lack of monetisation (paragraphs 85-89):**

Commission considers the following to be monetisation:
- Dual licensing model (free academic + paid commercial/scale)
- Technical support indistinguishably linked to the model itself, required for operation, paid
- Users must purchase support/training/maintenance services to access the model
- Model exclusively hosted on provider's platform requiring payment (including platform with paid ads)

NOT monetisation:
- Paid services that do not affect the usability or free usage of the model
- Paid premium features available alongside free model (extensions, updates, plug-ins)
- Provider provides collection/processing of personal data exclusively for model security without commercial/financial gain

**Microenterprise exception:** monetisation considered absent for transactions between microenterprises (paragraph 89).

**3. Public availability of parameters, weights, architecture, and usage info (paragraphs 90-92):**
- Format must enable access, usage, modification, distribution
- Must include input/output modalities, capabilities, limitations
- Must include technical means (instructions for use, infrastructure, tools) for integration into AI systems

### Enforcement (Section 5)

**Effects of code of practice adherence (Section 5.1):**
- Signatories of an adequate code of practice benefit from "straightforward way of demonstrating compliance" (Article 53(4), 55(2))
- AI Office will focus enforcement on **monitoring adherence** to the code
- Non-signatories must demonstrate compliance through "other adequate means" — expected to report measures to AI Office, may face "a larger number of requests for information and requests for access to conduct model evaluations"
- Adherence to an adequate code may be taken into account as a mitigating factor for fines (Article 101(1))
- Code is **temporary** — ceases to be the primary compliance route once harmonised standards are published (Article 40)

**AI Office enforcement powers:**
- Article 91: Request information
- Article 92: Conduct model evaluations
- Article 93: Request measures (including mitigation measures and recalling model from market)
- Article 101: Fines **up to 3% of global annual turnover or EUR 15 million, whichever is higher**

**Serious incident reporting** (paragraph 103): for Chapter V purposes, "serious incident" covers:
- Events listed in Article 3(49) (death, health harm, critical infrastructure disruption, fundamental rights breaches, property/environmental harm)
- Serious cybersecurity breaches including **(self-)exfiltration of model parameters** and cyberattacks

**Downstream provider complaints** (paragraph 105): downstream providers have right to lodge complaints against GPAI providers for alleged AI Act infringements (Article 89(2)).

### Phased Enforcement Timeline (Section 5.3)

**2 August 2025** — GPAI obligations enter into application
**2 August 2026** — AI Office enforcement powers enter into application (one-year grace period)
**2 August 2027** — Providers of GPAI models placed on market **before 2 August 2025** must achieve compliance

**Specific transitional allowances:**
- Pre-August-2025 models not required to conduct retraining/unlearning where "not possible to do this for actions performed in the past" or information not available or retrieval would cause disproportionate burden — must be clearly disclosed and justified in the copyright policy and training data summary
- Post-August-2025 models: Commission expects proactive contact with AI Office if compliance difficulties anticipated
- Providers actively training systemic risk models across the August 2025 transition should notify Commission within **2 weeks after 2 August 2025**

**The one-year grace period (Aug 2025 – Aug 2026):**
"The Commission cannot take any enforcement actions because its enforcement powers only enter into application on 2 August 2026. This lack of enforcement does not put into question the applicability of the obligations laid down in Chapter V of the AI Act from 2 August 2025 onwards."

### Compute Estimation Annex

**Scope (A.1):**
- Training compute = compute directly contributing to parameter updates in the model (for non-systemic-risk)
- Cumulative training compute = includes pre-training, synthetic data generation, fine-tuning (for systemic-risk assessment)
- **Include:** forward passes generating synthetic data used in training (even if only subset selected); combined model weights via merging/averaging/initialisation
- **Exclude:** compute for publicly accessible synthetic data; diagnostic/red-teaming compute; failed experiments/research; parent model compute in distillation; auxiliary models (value functions, reward models); activation recomputation

**Error margin:** 30% of reported estimate permitted (paragraph 123); providers expected to document assumptions, method, uncertainties.

**Two approaches (A.2):**

**Hardware-based (A.2.1):** C = N · L · H · U
- N = number of GPUs/hardware units
- L = total duration in seconds
- H = peak theoretical performance in FLOP/second (weighted average if mixed)
- U = average utilisation percentage

**Architecture-based (A.2.2):** For dense large language models based on transformers:
C ≈ 6 · P · D
- P = total number of parameters
- D = total number of training tokens

**Example calculations (A.3)** — the Commission provides eight calibration models with approximately one billion parameters, ranging from 7.5×10^22 to 6.5×10^23 FLOP, supporting the 10^23 FLOP threshold. Named calculation methods include:
- Model A: 3.8B parameters × 3.3T tokens ≈ 7.5×10^22 FLOP
- Model G: 2.6B parameters × 10T effective tokens (61B × 164 epochs) ≈ 1.5×10^23 FLOP
- Model H: 370,000 H100 GPU hours (80GB) at 989 TFLOP/s × 50% utilisation ≈ 6.5×10^23 FLOP

---

## Observations

### Clarity

The Guidelines are the most technically detailed Commission Communication on the AI Act. The 10^23 FLOP indicative criterion is a significant contribution — it operationalises the previously-vague "general-purpose AI model" definition into a testable technical threshold. The one-third-of-compute rule for downstream modifiers is similarly operational.

The technical annex on compute estimation is a model of regulatory clarity. By providing formulas, calibration examples, and a 30% error margin, the Commission equips providers with the tools they need to make defensible scope determinations. The worked examples of in-scope and out-of-scope models (paragraphs 20-21) are particularly useful: they clarify that specialisation alone (speech-to-text, image upscaling, playing chess) can keep a model below the GPAI threshold even at substantial compute scale.

Two clarity issues:

**The single-lifecycle treatment** is practically important but theoretically contentious. A fine-tuned variant of Llama is, in commercial reality, a different product with different risk profile than the base model. Treating them as "the same model" simplifies compliance documentation but may obscure substantive changes. The one-third-of-compute rule partially addresses this, but a specialised fine-tune under the threshold still inherits the upstream provider's compliance package without requiring separate assessment.

**"Reasonable foreseeability" for pre-training notification** (paragraph 31) is a demanding standard. A provider must estimate training compute before starting the run and potentially notify the Commission if the estimate crosses 10^25 FLOP. This requires ex ante certainty about planned compute allocation that actual provider practice may not match (training runs get scaled up or down, efficiency improvements compound, data availability changes).

### Measurability

Highly measurable where quantification is possible:
- 10^23 FLOP GPAI threshold
- 10^25 FLOP systemic risk threshold
- One-third-of-training-compute downstream modifier threshold
- 30% error margin for compute estimation
- 2-week notification deadline
- 6-month reassessment interval
- Fine levels (3% of global turnover or €15M, whichever higher)
- Phased timeline dates

Less measurable for qualitative judgements:
- "Significant generality" — indicative criterion rebuttable in both directions
- "Clearly and unequivocally excluded" EU distribution by upstream providers
- "Sufficiently substantiated arguments" for contesting classification
- "Adequate" code of practice

### Gaps

**Fine-tuning boundary ambiguity.** The one-third-of-compute rule is a threshold, but practical fine-tuning workflows use incremental updates that may accumulate across iterations. The Guidelines clarify that lifecycle modifications stay within the same model, but do not address when cumulative small fine-tunes reach the "substantial change" threshold. Providers running continuous training regimes will need documented rules for when they cross into provider-of-modified-model status.

**API-based fine-tuning classification.** Paragraph 60 footnote 12 notes that fine-tuning via API raises a case-by-case question of who "has the control over the model's weights." For enterprise customers using cloud provider APIs to fine-tune frontier models, who becomes the provider of the fine-tuned variant is a practically important question the Guidelines flag but do not resolve.

**Evaluation/red-team compute exclusion.** The Annex excludes compute for "purely diagnostic processes that do not contribute to enhancing model capabilities, such as model evaluations or red-teaming" (paragraph 122). But extensive evaluations that feed into model improvements (e.g., RLHF from red-team outputs) can contribute to capabilities. The boundary between diagnostic and capability-enhancing evaluation compute is not sharp.

**Model distillation treatment.** Paragraph 122 excludes "compute used to train parent model(s) used in distillation." This means a small model trained via distillation from a large foundation model may have a low formal training compute figure while inheriting capabilities from the parent. The parent may separately meet the GPAI/systemic-risk thresholds, but the distilled model does not. This creates a potential scope gap for commercial products that distill large models.

**Synthetic data compute treatment asymmetry.** Paragraph 120 includes compute used to generate synthetic data not publicly accessible in the training compute estimate (even for samples ultimately discarded). Paragraph 122 excludes compute for publicly accessible synthetic data. This distinction creates an incentive asymmetry: providers generating their own private synthetic data face higher compute counts than those using public synthetic datasets.

**Open-source licensing boundary cases.** The Guidelines disqualify user-scale-triggered commercial licensing (paragraph 83). But some licences (e.g., Meta's LLaMA 2 community licence with 700M MAU threshold) currently operate this way. The Guidelines effectively exclude such licences from the exemption — a significant commercial implication for specific industry practices.

**Competition implications.** The Guidelines' one-third-of-compute rule for downstream modifiers means that substantial fine-tuning triggers provider-level obligations. This may discourage significant fine-tuning by smaller organisations while leaving lightweight fine-tuning unaffected. The competitive effect of this threshold on downstream AI ecosystems is not addressed.

**Compute estimation reliability for contested cases.** The 30% error margin is generous but still creates scope-crossing risks near the thresholds. A provider estimating 9×10^24 FLOP (below 10^25) with 30% uncertainty could actually be at 1.17×10^25 (above). The Guidelines do not address how such margin-of-error cases are resolved in enforcement.

### Feasibility

The compliance structure is feasible for well-resourced providers:
- Major foundation model labs (OpenAI, Anthropic, Google DeepMind, Meta AI, Mistral) already track training compute precisely
- Technical documentation templates exist (Model Cards, the Annex XI template)
- Code of practice signing provides a clear compliance route
- Microenterprise exception and open-source exemptions reduce burden for small/non-commercial providers

Less feasible for:
- **Academic/research consortia at scale.** BLOOM, Falcon, and similar consortium models may meet the thresholds but lack the legal/organisational infrastructure to handle EU Commission notifications, authorised representatives, and adversarial testing for systemic risk
- **Open-source communities distributing via public hubs.** Hugging Face and similar hubs host thousands of models; determining which fall under obligations and ensuring the provider has complied is practically challenging. The Commission has not addressed platform liability
- **Downstream modifiers near the one-third threshold.** Determining training compute for a base model one did not train (to calculate one-third) is often not possible. The Commission's fallback (one-third of 10^23 or 10^25) creates a default trigger that may be lower than the actual one-third of the base model's compute, pulling more modifiers into the provider category

### Internal Consistency

The Guidelines are internally consistent. The treatment of pre-training, fine-tuning, and post-training as one lifecycle (Section 2.2) aligns with the downstream modifier threshold (only substantial modifications cross the provider boundary). The phased enforcement approach is consistent with the AI Act's Article 113.

One tension: the Commission treats FLOP as "an imperfect proxy for generality and capabilities" (paragraph 16) while simultaneously using FLOP as the primary threshold for GPAI classification, systemic risk classification, and downstream modifier classification. The implicit acknowledgement — that a better metric does not yet exist — is reasonable, but the pervasive reliance on FLOP creates compound uncertainty. As algorithmic efficiency improves, the thresholds may no longer correspond to the capability levels that justified them. The Commission's delegated-act power to adjust thresholds addresses this over time but does not prevent interim mismatch.

### Coverage

Coverage within scope is comprehensive. The Guidelines address:
- GPAI model classification (Section 2)
- Systemic risk classification (Section 2.3)
- Provider determination (Section 3.1)
- Downstream modifier thresholds (Section 3.2)
- Open-source exemptions (Section 4)
- Enforcement including code of practice role (Section 5)
- Compute estimation methodology (Annex)

What is deliberately outside scope:
- Substantive content of Article 53 obligations (covered by Annex XI/XII of the Act)
- Systemic risk assessment methodology (covered by the GPAI Code of Practice)
- Copyright policy operational details (deferred to Code of Practice)
- Training data summary template (deferred to AI Office template)

### International Alignment

The FLOP-based classification approach aligns with:
- **Biden's EO 14110 (now revoked):** had a 10^26 FLOP threshold for advanced AI reporting
- **UK AI Safety Institute focus:** similar emphasis on frontier model evaluation
- **AISI's evaluation methodology:** consistent with the Commission's approach to adversarial testing

Divergences:
- **UK DUAA 2025** does not impose GPAI-specific obligations; UK firms providing GPAI to EU customers face EU Chapter V regardless of UK non-regulation
- **US federal approach (post-revocation of EO 14110):** voluntary commitments only; no compulsory thresholds
- **China's GenAI Interim Measures:** sector-specific generative AI rules; different scope and requirements

For UK firms, the Commission Guidelines are now the operational reference for any GPAI model placed on the EU market or whose output is used in the EU — even if the UK imposes no equivalent obligations.

---

## Overall Assessment

These Guidelines are the operational translation of the EU AI Act's GPAI provisions. They convert the abstract Article 3(63) definition and Article 51 systemic risk threshold into workable compliance tests: compute thresholds, generation-capability criteria, one-third-of-compute rules, open-source conditions, and compute estimation formulas.

Their greatest strength is operational specificity. The **10^23 FLOP + language/image/video generation** indicative criterion gives providers a testable first-line classifier. The **one-third rule** for downstream modifiers provides a compute-proportionate threshold that scales with model size. The **compute estimation annex** with worked examples and a 30% error margin gives providers the technical tools to document their classifications. The **phased enforcement approach** (grace period to August 2026, retrospective compliance by August 2027) recognises practical implementation challenges.

Their greatest limitation is the reliance on FLOP as a primary classifier. The Commission acknowledges this is "an imperfect proxy for generality and capabilities" and may adjust thresholds as technology evolves. In the meantime, algorithmic efficiency gains could make the 10^23 threshold too low (catching genuinely non-general models) or too high (missing genuinely general models trained more efficiently). The Commission's commitment to investigate alternative criteria (benchmarks, qualitative assessments) is sensible but unresolved.

For UK-based firms serving EU clients, the practical implications are:

1. **Determine whether you are providing a GPAI model** — apply the 10^23 FLOP + language/image/video generation test. If yes, full Article 53 obligations apply regardless of UK establishment
2. **Estimate training compute using the Annex formulas** — document assumptions, method, uncertainties. Keep within the 30% error margin
3. **If approaching 10^25 FLOP, prepare for systemic risk notification** — notify Commission within 2 weeks of meeting or reasonably expecting to meet the threshold, including a pre-training notification if applicable
4. **Determine whether you qualify for the open-source exemption** — requires genuinely free licensing (no commercial carve-outs, no user-scale triggers), lack of monetisation (dual-licensing disqualifies), and publicly available weights/architecture/usage info
5. **Consider code of practice adherence** — straightforward compliance route; non-signatories face more Commission enforcement attention
6. **Appoint an EU authorised representative** before placing any non-exempt GPAI model on the EU market
7. **If modifying a third-party GPAI model**, track compute carefully against the one-third threshold
8. **Leverage the transition period** — August 2025 to August 2026 grace period; existing models until August 2027. But notify proactively

The Guidelines work best alongside the GPAI Code of Practice (three chapters: transparency, copyright, safety/security) which operationalises the specific obligations. The Guidelines determine **whether** Chapter V obligations apply; the Code determines **how** to comply with them.

For frontier developers, these Guidelines transform the EU AI Act from a conceptual framework into a concrete regulatory regime. The 10^25 FLOP systemic risk threshold — meeting which is likely for any frontier model released from 2025 onwards — triggers substantial obligations including model evaluation, systemic risk assessment, cybersecurity for model weights, and incident reporting. The Commission's investment in the AI Office, scientific panel, and enforcement infrastructure signals intent to make these obligations binding in practice, not just in law.

---

## Sources

- [Commission Guidelines on GPAI Obligations (C(2025) 5045)](https://digital-strategy.ec.europa.eu/en/library/guidelines-scope-obligations-providers-general-purpose-ai-models-under-ai-act)
- Companion documents reviewed in this repo:
  - [EU AI Act (review 01)](01-eu-ai-act.md) — overarching Act review
  - [Guidelines on Definition of AI System (review 02)](02-guidelines-definition-ai-system.md) — AI system vs GPAI model distinction
  - [Guidelines on Prohibited AI Practices (review 03)](03-guidelines-prohibited-ai-practices.md) — Article 5 interpretation
  - GPAI Code of Practice (Transparency, Copyright, Safety/Security chapters) — to be reviewed separately
- External reference: Kaplan et al., *Scaling laws for neural language models* (arXiv 2001.08361, 2020) — basis for the 6·P·D architecture formula
