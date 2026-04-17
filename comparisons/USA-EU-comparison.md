# USA vs EU: AI Governance Comparison

A comparison of the two poles of the global AI governance debate, based on 5 US reviews, 10 EU reviews, and the broader comparative work in this repo.

The US and EU represent fundamentally different answers to the same question: how should governments respond to AI? The EU answered with the most comprehensive binding AI regulation in the world. The US answered with voluntary frameworks, volatile executive action, and a deliberate choice not to legislate at the federal level. Most multinational firms must navigate both simultaneously.

---

## What each has

| Dimension | USA | EU |
|-----------|-----|----|
| **Primary instrument** | NIST AI RMF 1.0 (voluntary, Jan 2023) + executive orders (volatile) | EU AI Act (Regulation 2024/1689, binding) |
| **Legal form** | No federal AI legislation. Executive orders, voluntary framework, agency enforcement under existing authority, state-level legislation | Directly applicable regulation across 27 Member States + EEA |
| **Current political framing** | Competitiveness-first; "Winning the Race"; deregulation; geopolitical competition with China | Risk-based; fundamental-rights protection; "Trustworthy AI"; Brussels effect |
| **Binding AI obligations** | Federal: none on private sector (OMB M-25-21 binds agencies only). State: Colorado AI Act (effective Feb 2026) | Extensive: prohibited practices, high-risk obligations, GPAI provisions, transparency, incident reporting, penalties |
| **GPAI / foundation model regulation** | None binding. Biden EO 14110 had reporting requirements — revoked. NIST GenAI Profile is voluntary | Chapter V: binding obligations above 10²³ FLOP; systemic-risk tier above 10²⁵ FLOP; GPAI Code of Practice |
| **Prohibited practices** | None at federal level. State-level varies | Article 5: 8 categories (social scoring, biometric scraping, emotion recognition in workplace/education, etc.) |
| **Transparency / deepfake labelling** | No federal requirement. AI Action Plan mentions "combat synthetic media in the legal system" | Article 50 + Transparency Code (first draft Dec 2025, final Jun 2026): provider machine-readable marking + deployer human-readable labelling |
| **Incident reporting** | No AI-specific federal regime. OMB M-25-21 requires agencies to discontinue non-compliant high-impact AI | Article 73: tiered timelines (2/10/15 days); draft guidance Sep 2025 |
| **Penalties** | No federal AI-specific penalties. FTC, EEOC, FDA enforce under existing authority. State penalties vary | Up to €35M or 7% global turnover (prohibited practices); €15M / 3% (high-risk); €7.5M / 1.5% (incorrect information) |
| **Voluntary framework** | NIST AI RMF: 4 functions (Govern, Map, Measure, Manage); 7 trustworthiness characteristics | GPAI Code of Practice (Jul 2025): 24 signatories; structured compliance route. EU AI Pact: 100+ signatories |
| **Foundational ethical framework** | Blueprint for AI Bill of Rights (Oct 2022): 5 principles; aspirational; effectively superseded | HLEG Ethics Guidelines (Apr 2019): 4 principles, 7 requirements; became intellectual foundation of AI Act |
| **Safety institution** | US AISI at NIST — status uncertain under current administration; established under Biden | AI Office within DG CONNECT — policy/enforcement focus; no dedicated scientific evaluation function |
| **Federal AI governance for government use** | OMB M-25-21: Chief AI Officer; high-impact AI risk management; binding on agencies | AI Act applies to public-sector AI use where it meets risk thresholds. No EU-wide government AI playbook |
| **State / Member State level** | Rapid proliferation: 700+ bills in 2024; Colorado AI Act is landmark; California SB 1047 vetoed | 27 national competent authorities enforce the Act; Member State variability in enforcement maturity |
| **Extraterritorial reach** | None. US AI governance applies domestically only | Article 2: applies to non-EU providers whose systems are placed on EU market or whose outputs are used in EU |
| **International positioning** | Geopolitical competition with China; did not sign Paris AI Action Summit main declaration; export controls on AI chips | Regulatory setter; Brussels effect; Council of Europe Framework Convention; multilateral engagement |
| **Compute investment** | NAIRR pilot; CHIPS Act for semiconductor manufacturing; AI Action Plan infrastructure pillar | EuroHPC-JU; AI Factories; Coordinated Plan EUR 20bn/year target |
| **Administration durability** | Executive orders revoked on day one of new administration. NIST RMF (statutory) is durable. State legislation is durable | AI Act is legislation; survives political turnover across all Member States |

---

## Where they diverge substantively

### The fundamental design choice

The EU chose **binding horizontal regulation with predetermined risk categories**. The US chose **voluntary frameworks with politically variable executive overlay**.

This is not a difference of degree — it is a difference of kind. The EU's approach says: we know enough about AI risks to classify them categorically and impose binding obligations. The US approach says: we don't know enough to legislate, markets should lead, and government should remove barriers.

Both positions have internal logic. Both have costs. The EU risks over-prescribing for a technology that is evolving faster than regulation can adapt. The US risks under-protecting citizens and creating governance uncertainty for industry.

### Administration volatility vs regulatory permanence

The EU AI Act was adopted through a multi-year legislative process (Commission proposal April 2021 → trilogue → adoption 2024). It will survive changes of Commission, Parliament, and national governments because it is a Regulation, not a political programme.

The US executive-order approach produced the most comprehensive federal AI action (EO 14110) in October 2023 and saw it entirely revoked in January 2025 — 15 months later. Mandatory reporting requirements, red-teaming mandates, content labelling directives, and agency rulemaking efforts disappeared overnight.

**Practical consequence for firms**: building compliance infrastructure on US executive orders is a poor investment. Building on the EU AI Act is a durable investment. Building on the NIST AI RMF is a reasonable middle ground (statutory mandate, bipartisan origin, survives transitions — though the AI Action Plan's content-revision directive introduces new uncertainty).

### GPAI: EU has binding obligations; US has nothing

The EU AI Act Chapter V creates binding obligations for GPAI providers above 10²³ FLOP, with additional systemic-risk obligations above 10²⁵ FLOP. The GPAI Code of Practice (July 2025, 24 signatories) provides the structured compliance route.

The US has no binding obligations on GPAI providers. Biden's EO 14110 had reporting requirements for models above certain compute thresholds — these were revoked. The NIST GenAI Profile (AI 600-1) identifies 12 GenAI risks but is entirely voluntary.

**Consequence**: US-based frontier model providers (OpenAI, Anthropic, Google, Meta) face EU obligations when serving EU users but no equivalent domestic obligations. This creates a compliance asymmetry where US firms build to EU standards for EU markets and operate under lighter domestic conditions for US markets.

### Prohibited practices: EU has 8; US has none at federal level

The EU AI Act Article 5 prohibits 8 categories of AI practices — social scoring, untargeted biometric scraping, emotion recognition in workplace/education, etc. — with penalties up to €35M or 7% of global turnover.

The US has no federal AI-specific prohibitions. Existing law (Civil Rights Act, ADA, FHA, ECOA) provides some coverage, but there is no horizontal AI prohibition framework. The AI Action Plan does not propose one.

State-level legislation partially fills the gap: Colorado's AI Act (effective February 2026) creates obligations for "high-risk" AI systems in employment, education, healthcare, housing, insurance, and financial services — conceptually parallel to the EU's Annex III categories.

### Content labelling: EU operationalises; US mentions

The EU has Article 50 transparency obligations operationalised through the Transparency Code (first draft December 2025): provider machine-readable marking, deployer human-readable labelling, two-level taxonomy (fully AI-generated vs AI-assisted), modality-specific rules, editorial review exception.

The US AI Action Plan mentions "Combat Synthetic Media in the Legal System" — addressing deepfakes as an evidentiary problem rather than a transparency obligation. No federal labelling requirement exists or is proposed.

### Enforcement architecture

**EU**: harmonised penalties (€35M / 7%), national competent authorities, AI Office coordination, market surveillance, conformity assessment, and the Court of Justice of the EU as ultimate arbiter.

**US federal**: no AI-specific enforcement. FTC enforces under Section 5 (unfair/deceptive practices); FDA under medical device authority; EEOC under employment discrimination law. The AI Action Plan directs review of prior FTC investigations to ensure they "do not advance theories of liability that unduly burden AI innovation" — actively discouraging enforcement rather than enabling it.

**US state**: Colorado AI Act has its own enforcement (Attorney General); other states developing their own approaches. No coordination mechanism.

### State-level regulation as EU parallel

The most interesting structural parallel in the US is not at the federal level — it's at the state level. Colorado's AI Act:
- Creates risk categories (high-risk based on consequential decisions)
- Imposes obligations on developers and deployers
- Requires impact assessments
- Mandates transparency
- Enforced by the state Attorney General

This is conceptually closer to the EU AI Act than to any federal US instrument. The AI Action Plan's funding-conditionality pressure against state-level regulation reflects the tension: the federal government is actively discouraging states from doing what the EU has done.

---

## Where they converge

Despite the philosophical opposition, some convergences exist:

1. **Risk-based thinking.** Both acknowledge that not all AI is equally risky. The EU codifies this into statutory tiers. The US operationalises it through NIST's risk-proportionality language and OMB M-25-21's "high-impact AI" concept. The mechanism differs; the principle is shared.

2. **Safety for frontier models.** Both acknowledge frontier model risks. The EU addresses them through Chapter V and the GPAI Code of Practice. The US AI Action Plan preserves frontier model evaluation — but reframed as national security: "Ensure that the U.S. Government is at the Forefront of Evaluating National Security Risks in Frontier Models." The evaluation function survives; the framing changes from public safety to national security.

3. **NIST and HLEG as intellectual foundations.** Both jurisdictions produced foundational voluntary frameworks (NIST AI RMF 2023; HLEG Ethics Guidelines 2019) that shaped their respective governance architectures. The EU made its foundation binding; the US kept its voluntary — but both started from expert-led, consensus-built frameworks.

4. **Government AI governance.** OMB M-25-21 and the EU AI Act both create obligations for government use of AI (OMB through administrative directive; EU through the Act itself). Both require risk management for consequential government AI use and both mandate discontinuation when AI is not performing appropriately.

5. **Open-source / open-weight support.** The AI Action Plan explicitly supports open-source and open-weight AI; the EU AI Act provides partial exemptions for open-source models (Article 53(2)). Both recognise the innovation value of open models, though they frame the support differently.

---

## The Brussels effect in practice

The US-EU divergence creates a specific dynamic for US firms: the EU AI Act effectively sets the compliance floor for US firms with global reach.

- **US firms serving EU users must comply with the EU AI Act** regardless of domestic US deregulation
- **Major US firms have signed the GPAI Code of Practice** (OpenAI, Anthropic, Google, Microsoft, Amazon, IBM) — voluntarily adopting EU-framed obligations
- **Some US firms have delayed or modified EU product launches** (Apple Intelligence, Meta multimodal Llama) due to AI Act compliance considerations
- **US firms building compliance infrastructure for the EU** typically adopt it globally because maintaining divergent compliance is more expensive than maintaining a single high-standard approach

The Brussels effect means that **EU regulatory preferences are shaping US corporate AI practices** even though the US federal government explicitly rejects the EU approach. This is the same dynamic observed with GDPR: US firms adopted GDPR-compliant data practices globally despite the absence of equivalent US federal privacy law.

**Whether this dynamic is desirable** depends on perspective:

- From the EU's perspective: mission accomplished — global standards raised
- From the US firms' perspective: compliance cost imposed without domestic benefit
- From US consumers' perspective: they receive EU-standard protections indirectly, through firms' global compliance decisions, without their own government having mandated them
- From US policymakers' perspective: regulatory sovereignty ceded to a foreign jurisdiction

---

## The structural question

The US-EU comparison surfaces a deeper question: **is voluntary governance sufficient for a technology with the potential impact of AI?**

**The EU's answer is no.** Voluntary frameworks (HLEG Guidelines) were a useful starting point but the AI Act concludes that binding obligations are necessary. The evidence: not all firms adopt voluntary frameworks; voluntary frameworks have no enforcement mechanism; citizens need predictable, enforceable rights.

**The US federal answer is yes — with caveats.** The NIST AI RMF provides the framework; firms adopt it voluntarily; agency enforcement under existing law handles egregious cases; market competition and reputational pressure handle the rest. The caveats: this only works if firms actually adopt the framework, if agency enforcement is robust, and if market pressure is real.

**The US state-level answer is increasingly no.** Colorado, California, Utah, and others are moving toward binding obligations. They believe voluntary governance is insufficient to protect their citizens.

**The practical answer for firms**: if "touching" the EU market, then it is safer to build to the EU floor. It is worth noting that the EU has no ability to enforce its regulations within the USA, but rather against EU-entities and residents. There is therefore a travel-risk question for US-based founders that serve EU residents and ignore EU AI Act compliance. Regardless of which philosophical position is "correct," the EU want the AI Act to apply to any firm serving EU users. This incurs a greater burden, but any firms that build to the EU standard satisfy all domestic US requirements automatically; firms that build to the US standard alone will not satisfy EU requirements.

---

## Practical implications for firms operating across both jurisdictions

1. **EU AI Act is the compliance floor.** It is safer to build to it, or otherwise be aware of the risks of non-compliance. Larger organizations, particularly those with EU presence, should build towards the EU floor. If you already comply with the EU AI Act, you exceed all US federal requirements.

2. **NIST AI RMF is the internal governance scaffold.** Its four-function structure (Govern, Map, Measure, Manage) is a practical framework on which to layer EU-specific obligations. Use NIST as the architecture; use EU requirements as the specification.

3. **Monitor US state-level legislation.** Colorado AI Act (February 2026) and potential California legislation may create binding obligations beyond what federal policy requires. State-level requirements can be more restrictive than federal policy.

4. **Don't build compliance on executive orders.** They can be revoked overnight. Build on statute (NIST AI RMF, state law) and regulation (EU AI Act).

5. **National security framing preserves some safety evaluation.** US frontier model evaluation continues under national security framing. UK-US AISI bilateral cooperation may continue on this basis. But public-safety-motivated evaluation (the broader mandate) is no longer a US federal priority.

### A note on enforcement realism for pure-US entities

The AI Act's extraterritorial reach (Article 2) and the Brussels effect framing above may overstate the practical risk for US firms with no EU presence. The enforcement reality is more nuanced:

**What EU authorities can do against a pure-US entity (no EU subsidiary, employees, or assets):**

- Order distribution channels (app stores, cloud marketplaces) to stop serving the product to EU users — the most realistic lever
- Assess fines — but collection against a non-EU entity with no EU assets is practically impossible without international enforcement cooperation, which doesn't exist for AI Act penalties
- Create customer-side pressure — EU enterprise buyers will increasingly require AI Act compliance assurances, making non-compliance a commercial problem even without direct enforcement
- Publicly list the entity as non-compliant — reputational damage

**What EU authorities realistically cannot do:**

- Seize US-based assets or compel appearance before EU courts
- Block services at ISP level (theoretically possible but practically unprecedented — not used even for GDPR)
- Pursue founders personally — AI Act penalties are administrative on the company, not criminal charges against individuals. No US founder has been detained in the EU for GDPR non-compliance; AI Act enforcement is likely to follow the same pattern

**The GDPR precedent is instructive.** Every major GDPR fine against a US company has been against an EU subsidiary (Meta Platforms Ireland, Google Ireland). Pure-US entities without EU presence have largely avoided direct enforcement. The AI Act will likely follow the same pattern: EU subsidiaries get fined; pure-US entities without EU presence don't.

**The authorised-representative catch-22.** Article 22 requires non-EU providers of high-risk AI systems or GPAI models to appoint an EU-established authorised representative. If a firm doesn't appoint one, they're non-compliant — but enforcing the penalty requires reaching an entity that, by definition, has no EU presence.

**Risk scales with EU exposure:**

| Profile | Enforcement risk |
|---------|-----------------|
| Pure-US, no EU users | None — Act doesn't apply |
| Pure-US, few EU users via web/API | Very low — below enforcement threshold |
| Pure-US, significant EU revenue, no EU entity | Low-medium — distribution channel orders and customer pressure are real |
| US entity with EU subsidiary | High — subsidiary is the enforcement target |
| Major US GPAI provider (OpenAI, Anthropic, etc.) | Very high — all have EU presence; all have signed the GPAI Code of Practice |

**The practical bottom line:** for pure-US firms with no EU presence, the risk is commercial (losing EU customers, app store removal) rather than legal (uncollectable fines). For firms with EU subsidiaries, the risk is fully legal. The decision to comply should be driven by commercial exposure to the EU market, not by fear of enforcement against a US-only entity.

---

## Source reviews

**USA** (5 reviews): [`../USA/analysis/review-claude/`](../USA/analysis/review-claude/)

- [NIST AI RMF 1.0](../USA/analysis/review-claude/01-nist-ai-rmf.md)
- [Executive Orders and AI Action Plan](../USA/analysis/review-claude/02-executive-orders-and-action-plan.md)
- [Blueprint for AI Bill of Rights](../USA/analysis/review-claude/03-blueprint-ai-bill-of-rights.md)
- [NIST AI 600-1 GenAI Profile](../USA/analysis/review-claude/04-nist-genai-profile.md)
- [OMB M-25-21](../USA/analysis/review-claude/05-omb-m-25-21.md)

**EU** (10 reviews): [`../EU/analysis/review-claude/`](../EU/analysis/review-claude/)

- [EU AI Act](../EU/analysis/review-claude/01-eu-ai-act.md)
- [HLEG Ethics Guidelines](../EU/analysis/review-claude/08-ethics-guidelines-trustworthy-ai-2019.md)
- [GPAI Code of Practice](../EU/analysis/review-claude/05-gpai-code-of-practice.md)
- [Commission Guidelines (3 documents)](../EU/analysis/review-claude/02-guidelines-definition-ai-system.md)
- [Transparency Code](../EU/analysis/review-claude/07-transparency-code-ai-generated-content.md)

**Related comparisons:**
- [UK vs EU](UK-EU-comparison.md)
- [Small Open Economies](small-open-economies-comparison.md)
- [EFTA and AI Governance](efta-ai-governance.md)
