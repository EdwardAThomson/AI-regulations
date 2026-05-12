# US State-Level AI Legislation

The existing USA reviews (`review-claude/`) cover federal instruments: NIST AI RMF, the Biden and Trump executive orders, the AI Action Plan, the AI Bill of Rights, OMB M-25-21. State-level legislation is referenced throughout — particularly in [review 02](review-claude/02-executive-orders-and-action-plan.md) and the [USA README](../README.md) — but is not analysed in its own right. This note fills that gap.

The headline fact: **the binding obligations on private-sector AI in the United States today are mostly state, not federal.** Federal AI policy is voluntary frameworks plus executive direction; the substantive consumer- and worker-protection rules with teeth come from a small number of state and municipal statutes. Over 700 AI bills were introduced across US state legislatures in 2024 alone (NCSL tracking, cited in [`../source/inventory.md`](../source/inventory.md)); a much smaller number have passed and matter for compliance design.

The states and instruments covered here are the ones we currently treat as material for cross-jurisdictional compliance:

- **Colorado** — Colorado AI Act (SB 24-205), the landmark statute
- **California** — CPRA + ADMT regulations, SB 1047 (vetoed), transparency Acts (AB 2013, SB 942)
- **New York City** — Local Law 144 (AEDT)
- **Illinois and Texas** — biometric statutes (BIPA, CUBI) and their AI implications
- **Utah** — AI Policy Act
- **Other states** — privacy statutes (VCDPA, CPA, CTDPA, UCPA, TDPSA) and proliferating sector-specific bills

This note records each, with the AI-relevant points and the cross-state pattern. It is **not** a comprehensive 50-state survey — it is the operational subset we currently rely on for compliance work.

---

## 1. Reach: a model that differs from EU and UK

Before the substance: a structural point that shapes everything below.

**US state AI law attaches to the resident, not to the company.** A company need not be established in a state, have an office in a state, or even target that state's market specifically for its laws to apply. The trigger is typically:

- the company's AI system being used to make a decision about a resident of that state (Colorado, NYC Local Law 144); or
- the company processing personal data of a resident of that state above defined thresholds (state privacy statutes); or
- the company collecting biometric data of a resident of that state (Illinois BIPA, Texas CUBI).

This is **conceptually similar to GDPR Article 3(2)** — extraterritorial reach by reference to the data subject / resident — and **different from the EU AI Act**, which attaches obligations to providers and deployers via market-placement and output-use tests on AI systems specifically.

The practical implication: for any US-facing product, the question is not "which state am I in?" but "which of my users are in which states?". Compliance design has to be built around the user-residence dimension from the start.

---

## 2. Colorado — Colorado AI Act (SB 24-205)

### Status and citation

- **Senate Bill 24-205**, "Concerning Consumer Protections in Interactions with Artificial Intelligence Systems."
- Signed into law May 2024.
- **Effective date: 1 February 2026** (originally; status of any amendments / delays should be verified against the Colorado General Assembly — flagged in [`../source/inventory.md`](../source/inventory.md) as a tracked item).
- Enforced by the Colorado Attorney General. No private right of action.

### Why it matters

Colorado is the **first US state to enact a horizontal AI risk-based statute** with binding obligations on private-sector developers and deployers — structurally the closest US analogue to the EU AI Act, though substantially narrower.

### What it covers

The Act applies to "high-risk artificial intelligence systems" that make, or are a substantial factor in making, **consequential decisions**. A consequential decision is one with material legal or similarly significant effect on:

- education enrolment or opportunity
- employment or employment opportunity
- financial or lending service
- essential government service
- healthcare service
- housing
- insurance
- legal service

The category mirrors the EU AI Act Annex III high-risk list closely but is shorter.

### Core obligations

For **developers** of high-risk AI systems:

- Use reasonable care to avoid algorithmic discrimination.
- Provide deployers with a statement disclosing the system's intended purpose, known limitations, data used to train it, the methods used to evaluate performance, and known mitigations for algorithmic discrimination risk.
- Disclose to the AG any known or reasonably foreseeable risk of algorithmic discrimination within a defined window of discovery.

For **deployers** of high-risk AI systems:

- Use reasonable care to avoid algorithmic discrimination.
- Conduct and document **impact assessments** (annually, and on substantial modifications).
- Provide **pre-decision notice to consumers** that an AI system will be used and disclose the purpose, nature, and contact information.
- After a consequential decision, provide consumers with the principal reasons for the decision, the right to correct underlying personal data, and **a right to appeal to a human reviewer where technically feasible**.
- Disclose known or foreseeable risks of algorithmic discrimination to the AG.

### Where it lines up with — and differs from — the EU AI Act

- **Lines up:** risk-based categorisation; impact assessments; transparency to affected individuals; human-review rights; algorithmic-discrimination duty of care; obligations across developer / deployer roles.
- **Differs:** no pre-market conformity assessment; no notified-body system; no GPAI chapter; no prohibited-practices list; AG enforcement only, no fine schedule comparable to AI Act's €35M / 7% turnover. The duty is "reasonable care," which imports a negligence standard rather than strict liability.

### Federal pressure on Colorado

The July 2025 America's AI Action Plan directs OMB to "consider a state's AI regulatory climate when making funding decisions and limit funding if the state's AI regulatory regimes may hinder the effectiveness of that funding" (see [review 02 §150](review-claude/02-executive-orders-and-action-plan.md#L150)). This is a **preemption-by-funding** lever directed primarily at Colorado. It does not formally preempt SB 24-205 — that would require Congressional action — but it raises the political cost of state AI regulation.

### Implication

Colorado AI Act is the closest thing the US has to a binding horizontal AI regime, and it sits on a single state. For any company with US customers in housing, employment, lending, insurance, education, or healthcare-adjacent verticals, Colorado is on the compliance roadmap regardless of where the company is headquartered.

---

## 3. California — CPRA + ADMT, SB 1047 (vetoed), transparency Acts

California has the largest population, the most active AI regulatory pipeline, and the most consequential vetoed bill of the recent cycle.

### CPRA + Automated Decision-Making Technology (ADMT) regulations

The California Privacy Rights Act (CPRA, amending the CCPA) and the regulations issued under it by the **California Privacy Protection Agency (CPPA)** are the operative California regime as it applies to AI. The CPPA's ADMT regulations (finalised in 2025 after multi-year drafting) impose:

- **Pre-use notice** to California residents when ADMT is used for specified significant decisions (employment, housing, lending, education, healthcare, insurance, and access to essential goods or services).
- **Opt-out rights** for sensitive uses of ADMT.
- **Access rights** to information about the logic, the intended outputs, the consumer's role in the decision, and the consumer's rights.
- **Risk assessments** for certain processing — overlapping conceptually with both AI Act FRIA and GDPR DPIA but with California-specific scope.
- Heightened rules for **profiling** and **training of automated decision-making technology** using personal information.

ADMT is **broader than Colorado AI Act in scope** (it captures decisions involving personal information of California residents — not only high-risk AI categories) but **narrower in remedy** (it operates as a privacy-regulation overlay rather than a horizontal AI statute).

### SB 1047 (vetoed)

SB 1047 — the "Safe and Secure Innovation for Frontier Artificial Intelligence Models Act" — passed the California legislature in 2024 and was **vetoed by Governor Newsom in September 2024**. It would have imposed pre-deployment safety testing, kill-switch requirements, and reporting obligations on developers of large-scale models above a defined compute threshold.

Why it matters even though it was vetoed:

- It set the political template for state-level frontier-model regulation. Other states have signalled they may pick up similar bills.
- The veto rationale (need for risk-proportionate scope) signalled where a future re-introduced bill would have to be revised.
- The bill shaped industry voluntary commitments at the time and informed the federal debate.

For compliance design today, SB 1047 is **not** in force. For risk forecasting, it is the most likely template for a future binding state frontier-model statute.

### AI transparency Acts (AB 2013, SB 942 and others)

California has also enacted AI-specific transparency statutes outside the privacy framework:

- **AB 2013** — requires generative AI developers to publicly post documentation about the data used to train the system, on or before 1 January 2026.
- **SB 942 — California AI Transparency Act** — requires covered "generative AI providers" with significant user numbers to provide AI detection tools and to embed disclosures (manifest or latent) in AI-generated content for California consumers.

These are narrower in subject-matter than the EU AI Act's Article 50 transparency obligations but **arrive ahead of the AI Act's August 2026 application date** for transparency on AI-generated content — California-targeted services have a transparency obligation **now**, regardless of EU timing.

### Implication

California's regime is **fragmented across instruments** — CPRA / ADMT for automated decisions; AB 2013 / SB 942 for generative AI transparency; CPPA enforcement; AG enforcement; private right of action under CPRA for specified breach scenarios — but the cumulative scope is broad. Treat California as a privacy-led AI overlay, not a single AI statute.

---

## 4. New York City — Local Law 144 (AEDT)

### Status

In force since 5 July 2023. Enforced by the New York City Department of Consumer and Worker Protection (DCWP). Civil penalties per violation.

### What it covers

NYC Local Law 144 regulates **Automated Employment Decision Tools (AEDTs)** used to screen candidates for employment or promotion in New York City. The triggers are: the tool is used to substantially assist or replace discretionary employment decision-making, and the candidate or employee resides in New York City or the job is located in New York City.

### Core obligations

- **Annual independent bias audit** of the AEDT against statutorily-defined demographic groups.
- **Public posting of the bias audit summary** on the employer's or employment agency's website.
- **Candidate notice** that an AEDT will be used in the hiring decision, including disclosure of the type of AEDT, the categories of data collected, and the source of data used.
- **Right to request an alternative process** or accommodation.

### Why it matters

Local Law 144 was the **first US-jurisdiction binding AI law with public-disclosure teeth** to come into effect. It is narrow (employment AEDTs only, NYC only) but its bias-audit mechanism — publicly posted audit summaries — is **structurally different from the EU AI Act's high-risk obligations**, which require conformity assessment but not public publication of audit results. NYC Local Law 144 makes the audit visible to candidates and to the public.

### Implication

Any employer hiring in NYC using AI screening tools is in scope, regardless of headquarters location. The annual bias-audit requirement has driven a third-party audit services market that is now informing how similar audit regimes might work at state or federal level.

---

## 5. Illinois and Texas — biometric statutes

### Illinois Biometric Information Privacy Act (BIPA)

Illinois's BIPA (740 ILCS 14, in force since 2008) is the **most consequential US biometric statute** and is heavily AI-relevant because facial recognition, voiceprint analysis, and other AI biometric systems fall directly within its scope.

Core obligations:

- **Written informed consent** before collecting or storing biometric identifiers or biometric information of Illinois residents.
- **Public retention and destruction policy**.
- **Prohibition on profit** from biometric data.
- **Private right of action with statutory damages** — $1,000 per negligent violation, $5,000 per intentional violation, per person.

BIPA litigation has been the largest category of US AI-adjacent class actions, with multi-billion-dollar settlements (Facebook tagging, others). The private right of action is what makes BIPA materially different from most state regimes.

### Texas Capture or Use of Biometric Identifier (CUBI)

Texas's CUBI (Tex. Bus. & Com. Code §503.001) is structurally similar to BIPA but **lacks the private right of action** — enforcement is by the Texas AG only. CUBI was historically dormant; it has been increasingly active in recent years.

### Implication for AI

Any AI system performing biometric processing on Illinois or Texas residents — facial recognition, voice authentication, retina scans, fingerprint matching, gait or behavioural biometrics — must build BIPA / CUBI compliance into the consent flow before processing. The BIPA private right of action is the **single biggest source of US AI litigation risk** at present.

---

## 6. Utah — AI Policy Act

Utah's AI Policy Act (effective 2024) requires that businesses providing "regulated occupation" services — primarily licensed professions — **disclose to consumers when they are interacting with a generative AI system rather than a human professional** at the start of the interaction. The Act also clarifies that businesses are responsible for the outputs of generative AI used in their service.

The Act is narrower than Colorado AI Act in subject-matter but is **the first US state generative-AI disclosure regime** specifically targeted at chatbots and AI-assisted professional services. It is operationally relevant to any business using consumer-facing AI in regulated verticals (healthcare, legal, financial services).

---

## 7. Other state activity

### State comprehensive privacy laws — relevant as AI overlays

In addition to California, several states have enacted comprehensive consumer privacy laws that apply to AI processing of resident personal data:

| State | Statute | Notable AI-relevant features |
|---|---|---|
| Virginia | VCDPA | Profiling and ADM opt-out rights for significant decisions |
| Colorado | CPA (separate from AI Act) | Profiling opt-out; DPIAs |
| Connecticut | CTDPA | Profiling opt-out; data protection assessments |
| Utah | UCPA | Lighter regime; opt-out rights |
| Texas | TDPSA | DPIAs for profiling and ADM; consumer rights |
| Indiana, Iowa, Tennessee, Montana, Oregon, Delaware, New Hampshire, New Jersey | Newer state regimes | Various ADM / profiling provisions |

These statutes do **not** establish horizontal AI rules but they do impose AI-relevant obligations (profiling opt-out, ADM transparency, DPIAs for high-risk processing) on operators handling state residents' personal data. The interaction with AI services is constant; the rules are state-by-state different.

### Sector-specific and use-specific state bills

A growing number of states are enacting **use-specific** AI laws:

- **AI election content** — multiple states require disclosure of AI-generated political content (Michigan, Minnesota, Texas, Washington, California, others).
- **Deepfake / non-consensual intimate imagery** — many states criminalise or create civil causes of action.
- **AI in healthcare** — California SB 1120 requires human review of AI-driven utilisation review decisions; other states are following.
- **AI in insurance** — NAIC Model Bulletin on AI / Big Data; state Insurance Commissioners issuing companion guidance.

These are too numerous to enumerate; the pattern is **vertical-by-vertical state action filling the federal void**.

---

## 8. Cross-cutting observations

### 8.1 The federal void is filled state-by-state, not uniformly

The most accurate description of US AI regulation today is: **a horizontal void at federal level, filled vertically and unevenly at state level**. Colorado is the only state with a horizontal AI risk-based statute; California has the broadest set of overlapping privacy-led instruments; New York City has the only operational bias-audit regime; Illinois has the largest private litigation surface; Utah has the only generative-AI disclosure act.

For multi-state operators, compliance requires building to the **strictest applicable rule per use-case dimension**:

- Strictest impact-assessment rule → Colorado AI Act
- Strictest ADM disclosure rule → California ADMT + Colorado AI Act
- Strictest bias-audit rule → NYC Local Law 144
- Strictest biometric-consent rule → Illinois BIPA
- Strictest gen-AI disclosure rule → Utah + California SB 942

This is operationally similar to how multi-jurisdiction privacy compliance built around the strictest GDPR / CCPA / LGPD profile; **the US AI compliance baseline is now itself a multi-jurisdiction stack within one country**.

### 8.2 Reach attaches to the resident, not the company

For every state regime above, the trigger is the residence of the affected individual, not the location of the company. A UK-headquartered SaaS company with no US offices but with users in California, Colorado, NYC, and Illinois has obligations under California ADMT, Colorado AI Act (if its system makes consequential decisions about Colorado residents), NYC Local Law 144 (if used by NYC employers in hiring), and Illinois BIPA (if it processes biometrics of Illinois residents) — *concurrently and irrespective of UK or EU obligations*.

### 8.3 Federal preemption is a live but unresolved threat

The Trump administration's AI Action Plan uses federal funding conditionality as leverage against state AI regulation ([review 02 §150](review-claude/02-executive-orders-and-action-plan.md#L150)). It does not formally preempt state law — Congressional action would be required for that — but it raises the political cost. Compliance design should not assume state regimes will survive untouched, but **should not assume they will be preempted either**. Colorado AI Act (Feb 2026 effective date) sits squarely in the middle of this uncertainty.

### 8.4 Enforcement remedies differ enormously

- **Private right of action (BIPA, CPRA in some scenarios)** — drives class action exposure and is the largest source of US AI litigation risk today.
- **State AG enforcement (Colorado AI Act, CUBI, most state privacy laws)** — politically variable; depends on AG priorities and resourcing.
- **State agency enforcement (CPPA, NYC DCWP)** — most operationally active; produces rule-making and informal guidance.

The remedy structure shapes risk weighting: BIPA / California CPRA scenarios attract direct compensable claims; Colorado AI Act creates regulatory exposure but no direct private claim.

### 8.5 The state regimes are converging on a pattern

Reading the statutes side by side, the **pattern that is emerging** is:

1. Risk-based or use-based scoping (consequential decisions; AEDTs; significant decisions).
2. Impact / risk assessments (Colorado AI Act; California ADMT; several state privacy laws).
3. Pre-decision notice and post-decision explanation (Colorado AI Act; California ADMT; Utah).
4. Bias / disparate-impact controls (Colorado AI Act; NYC Local Law 144; California ADMT).
5. Right to human review / appeal (Colorado AI Act; California ADMT for sensitive uses; NYC Local Law 144 for AEDTs).
6. Public or candidate-facing disclosure of AI use (NYC Local Law 144; Utah; California AB 2013 / SB 942).

This pattern is **independently emerging without federal coordination**. If a federal AI statute is ever enacted, it will most likely look like the union of these state instruments — not like the EU AI Act.

---

## 9. Comparative position

| Dimension | US (state composite) | EU AI Act | UK |
|---|---|---|---|
| Legal form | State statutes + state agency rules + municipal ordinances; no federal cross-state coordination | Single binding Regulation across 27 Member States + EEA | Non-statutory; sector-regulator-led |
| Reach | Resident-based; attaches to individuals, not companies | Market placement + output use in EU | UK-established + UK data subjects (UK GDPR Art 3) |
| Risk taxonomy | Colorado AI Act has 8 consequential-decision categories; NYC focuses on employment; California focuses on ADM more broadly | 4 tiers (prohibited / high-risk / limited / minimal) + GPAI | None — sector regulators classify in context |
| Impact assessment | Yes (Colorado, California ADMT, several state privacy laws) | Yes (Article 27 FRIA + DPIA where personal data) | DPIA under UK GDPR Art 35; no AI-specific FRIA |
| Bias audit | NYC Local Law 144 — public posting | Article 15 accuracy / robustness; no public-posting obligation | Implicit via ICO and sector regulators; no statutory public bias audit |
| Human review right | Colorado AI Act; California ADMT (sensitive uses); NYC Local Law 144 | Article 14 human oversight; Article 50 transparency | Implicit via UK GDPR Art 22 (relaxed under DUAA 2025) |
| Private right of action | Yes — BIPA, CPRA scenarios | No — regulatory enforcement only | No — regulatory enforcement only |
| Penalty ceiling | BIPA — $5,000 / violation / person (class action driver); Colorado AI Act — AG civil penalties | €35M / 7% global turnover | UK GDPR — £17.5M / 4% global turnover; no AI-specific penalties |
| GPAI / foundation model rules | None binding — SB 1047 vetoed | Article 51 et seq. — binding above 10²³ FLOP; systemic risk above 10²⁵ FLOP | None binding — AISI voluntary evaluations |
| Effective dates | Variable; BIPA 2008; NYC LL 144 2023; CO AI Act Feb 2026; CA ADMT 2025 finalised | Phased: prohibitions Feb 2025; GPAI Aug 2025; high-risk Aug 2026 | Continuous; DUAA 2025 phased through Jun 2026 |

The US state composite **does not** replicate the EU AI Act's horizontal scope. It **does** replicate, piecemeal, most of the AI Act's substantive obligations on impact assessment, transparency, human review, and bias control — and adds, via BIPA, a private-litigation enforcement mechanism that the AI Act does not contemplate.

---

## 10. Implications for compliance design

1. **Build the multi-state compliance stack as the US baseline, not as an optional extra.** Colorado, California, NYC, and Illinois cover the operationally-significant obligations for most B2C and HR-adjacent AI systems. Federal voluntary frameworks (NIST AI RMF) are a layer above that, not a substitute for it.

2. **Track residence, not company location.** Architecture decisions about which users get which AI features should be informed by where they live. Hard-coding "US users get everything" is now a compliance position, not a default.

3. **Bias audit is becoming the de-facto US AI accountability artefact.** NYC LL 144 made public bias audits a regulatory obligation; Colorado AI Act and California ADMT both push in that direction. Operators should produce audit artefacts they would be willing to publish, even where publication is not yet mandatory.

4. **BIPA is the most expensive US AI law in practice.** Statutory damages × class size has produced settlements running into the billions. Biometric AI deployments need consent flows that meet BIPA's specific procedural requirements, regardless of where the company is established.

5. **Watch Colorado February 2026.** It is the first horizontal US AI statute to come into force; how its impact-assessment and notice provisions are operationalised will set the template for adjacent states. Whether it survives federal preemption pressure is the leading indicator for US state-level AI regulation as a category.

6. **Plan for instability.** State AI regimes are politically contested; federal preemption-by-funding is a real lever; private litigation under BIPA is volatile. The compliance design should be modular per state, not built around a single assumed baseline.

---

## Sources and further reading

- **Colorado AI Act** — SB 24-205, Colorado General Assembly. Status flagged in [`../source/inventory.md`](../source/inventory.md) as a tracked acquisition.
- **California** — California Privacy Rights Act (CPRA); California Privacy Protection Agency Automated Decision-Making Technology (ADMT) regulations; SB 1047 (vetoed September 2024); AB 2013; SB 942 (California AI Transparency Act).
- **New York City** — Local Law 144 of 2021, in force 5 July 2023; Department of Consumer and Worker Protection rules.
- **Illinois** — Biometric Information Privacy Act, 740 ILCS 14.
- **Texas** — Capture or Use of Biometric Identifier, Tex. Bus. & Com. Code §503.001; Texas Data Privacy and Security Act (TDPSA).
- **Utah** — Utah AI Policy Act (effective 2024); Utah Consumer Privacy Act (UCPA).
- **Other states** — Virginia VCDPA; Colorado CPA; Connecticut CTDPA; Indiana, Iowa, Tennessee, Montana, Oregon, Delaware, New Hampshire, New Jersey privacy regimes (varying scope).
- **Tracking** — National Conference of State Legislatures (NCSL) AI bill tracker; Multistate AI tracker. Numbers cited in [USA README](../README.md) and [`../source/inventory.md`](../source/inventory.md).
- **Federal interaction** — [`review-claude/02-executive-orders-and-action-plan.md`](review-claude/02-executive-orders-and-action-plan.md) for the AI Action Plan's funding-conditionality lever against state AI regulation.
- **Cross-jurisdictional comparisons** — [`../../comparisons/USA-EU-comparison.md`](../../comparisons/USA-EU-comparison.md); [`../../comparisons/gdpr-as-ai-overlay.md`](../../comparisons/gdpr-as-ai-overlay.md) for the data-protection overlay angle.
