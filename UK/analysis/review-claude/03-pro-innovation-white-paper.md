# A Pro-Innovation Approach to AI Regulation: White Paper — Review

**Document:** A pro-innovation approach to AI regulation (White Paper)
**Published:** 29 March 2023
**Issuing body:** Department for Science, Innovation and Technology (DSIT)
**Presented to Parliament by:** The Rt Hon Michelle Donelan MP, Secretary of State for Science, Innovation and Technology
**Reference:** CP 815

**Note:** This white paper was published as HTML only on GOV.UK. It was followed by a 12-week public consultation and a government response in February 2024 (reviewed separately as `02-pro-innovation-regulation-consultation-response.md`).

---

## Summary

This is the foundational document for the UK's approach to AI regulation. It proposes a principles-based, context-specific, sector-regulator-led framework — explicitly rejecting both a dedicated AI regulator and technology-specific legislation. Five cross-sectoral principles (safety, transparency, fairness, accountability, contestability) are to be issued on a non-statutory basis to existing regulators, with central government functions for coordination, risk monitoring, and horizon scanning. The framework defines AI through two functional characteristics — adaptivity and autonomy — rather than by reference to specific technologies. The document positions itself as pro-innovation and explicitly contrasts the UK approach with what it characterises as more rigid international alternatives, citing post-Brexit regulatory sovereignty as a strategic advantage.

---

## Key Points

- **Five cross-sectoral principles** issued on a non-statutory basis: safety/security/robustness, appropriate transparency/explainability, fairness, accountability/governance, contestability/redress
- **Context-specific regulation:** "We will not assign rules or risk levels to entire sectors or technologies. Instead, we will regulate based on the outcomes AI is likely to generate in particular applications." A chatbot summarising news articles should not be regulated the same way as one providing medical advice, even if both are built on the same foundation model
- **No new AI regulator:** Existing sector regulators (FCA, CMA, ICO, Ofcom, MHRA, etc.) apply the principles within their remits. A central government function provides coordination, not direction
- **AI defined by function, not technology:** Two characteristics — adaptivity (trained on data patterns not easily discernible to humans) and autonomy (decisions without express human intent or ongoing control). This avoids rigid definitions that become outdated
- **Statutory duty anticipated but deferred:** The government "anticipates introducing a statutory duty on regulators requiring them to have due regard to the principles" after an implementation review, but sets no timeline
- **Central support functions:** Six workstreams — monitoring/evaluation, cross-economy risk assessment, horizon scanning, testbed/sandbox support, education/awareness, and international interoperability
- **Foundation models acknowledged but not directly regulated:** Recognised as presenting specific challenges (a single flaw could propagate across applications, developers may not anticipate downstream uses, market power concentration), but direct regulation deferred. The government will "monitor developments closely" and "may need to consider targeted measures"
- **Regulatory sandboxes:** Four models proposed ranging from single-sector/single-regulator to multi-sector/multi-regulator, with consultation on which sectors would benefit most
- **Tools for trustworthy AI:** A layered approach to technical standards (Layer 1: sector-agnostic governance standards; Layer 2: issue-specific standards for bias, transparency; Layer 3: sector-specific standards). Portfolio of AI Assurance Techniques to be launched in spring 2023
- **International positioning:** Active engagement through OECD, GPAI (founding member), G7, Council of Europe CAI (Bureau position), UNESCO, ISO/IEC. Bilateral engagement with EU, US, Canada, Singapore, Japan, Australia, Israel, Norway, Switzerland
- **Post-Brexit framing:** "Having exited the European Union we are free to establish a regulatory approach" — the distinct UK approach is presented as a competitive advantage
- **Existing legal coverage mapped:** Equality Act 2010, data protection, product safety, consumer rights, and tort law already address some AI risks, but gaps exist "across, or in the gaps between, existing regulatory remits"
- **Phased implementation roadmap:** First 6 months — issue principles, publish roadmap, pilot sandbox. 6-12 months — regulator guidance, monitoring framework proposals. 12+ months — first evaluation report, risk register, assessment of whether statutory interventions needed

---

## Observations

### Clarity

The document is clearly written and well-structured. The seven-part architecture moves logically from context (Parts 1-2) through proposal (Part 3) to supporting mechanisms (Parts 4-6) and implementation (Part 7). The writing is accessible and avoids excessive jargon.

The two-characteristic AI definition (adaptivity + autonomy) is elegant and the document explains clearly why it chose functional characteristics over technology-specific definitions. The context-specific regulatory philosophy is illustrated effectively through concrete examples — the chatbot comparison (news vs. medical advice), the insurance pricing case study, and the MHRA adaptation case study all help make abstract principles tangible.

However, several key concepts are left strategically vague:

- "Appropriate" transparency and "proportionate" responses are used repeatedly without defining what determines appropriateness or proportionality. This is by design — the framework delegates these judgements to sector regulators — but it means the principles themselves provide little actionable guidance.
- The relationship between the central function and regulator independence is described as "coordination" and "support" but never defined. What happens when the central function's risk assessment diverges from a regulator's? Who prevails?
- "We anticipate introducing a statutory duty" is a statement of expectation, not commitment. The document never specifies what would trigger legislation or what would constitute evidence that the non-statutory approach has failed.

### Measurability

This is the document's weakest dimension. It contains almost no measurable commitments. The implementation roadmap in Part 7 provides process milestones (publish roadmap, issue principles, launch sandbox pilot) but no outcome targets.

There are no metrics for:
- How many regulators should publish AI guidance, by when
- What level of regulator AI capability is sufficient
- How public trust in AI will be measured
- What constitutes acceptable vs. unacceptable levels of AI-related harm
- How innovation impact will be assessed
- What would trigger the transition from non-statutory to statutory

The document commits to publishing a monitoring and evaluation framework, but the framework itself is deferred to a future consultation. This is a strategy document that cannot evaluate its own success because it has defined no success criteria.

### Gaps

**Foundation model governance.** The document acknowledges that foundation models present unique challenges — cross-cutting risk, opacity, market concentration — but explicitly defers regulation. The position is that sector regulators will address risks at the application level. This creates a structural gap: the entity best placed to mitigate foundation model risks (the developer) faces no regulatory obligations, while the entities with regulatory obligations (deployers) may lack the technical capability to assess upstream risks. The document signals awareness of this gap ("we may need to consider targeted measures") but does not address it. The February 2024 consultation response subsequently built the case for binding measures on frontier AI developers — confirming that this gap was recognised as untenable within months.

**Life cycle accountability.** The document identifies the AI life cycle as spanning "inception to decommissioning" and acknowledges that "it can be challenging to identify which rules are relevant" across the supply chain. But it does not propose any mechanism for allocating responsibility between developers, deployers, and users. The fictional case studies (insurance pricing, recruitment tools) illustrate the problem without offering solutions. This is flagged as a consultation question rather than resolved.

**Workers and labour markets.** The document mentions AI's potential to "free us up from monotonous tasks" and create jobs, but contains no analysis of displacement risk, transition support, or Fair Work considerations. The workforce is treated as a beneficiary of AI, not as a group that may need protection from it.

**Citizens' rights.** The contestability and redress principle is the weakest of the five. It provides that affected parties "should be able to contest an AI decision" where appropriate, with redress proportionate to harm. But the document does not address how citizens will know when AI has been used in decisions affecting them (a prerequisite for contestation), what "appropriate" means in practice, or whether existing legal routes are adequate. The consultation subsequently found that over half of respondents said existing redress routes are inadequate.

**Environmental impact.** Not mentioned. The document discusses compute capability as critical infrastructure but does not address energy consumption or environmental costs.

**Devolution.** Addressed briefly in Part 5 — the framework applies to the whole UK, relying on reserved legislation (Data Protection Act, Equality Act) for implementation. But AI policy intersects with devolved competences in health, education, policing, and public services. The document commits to engaging devolved administrations but does not analyse where regulatory divergence might occur.

**Enforcement.** The document describes what regulators should do but does not address what happens if they don't. With principles on a non-statutory basis, there is no legal mechanism to compel regulators to act. The anticipated statutory duty would address this, but its timeline is undefined.

### Feasibility

The framework's feasibility depends on two assumptions: that existing regulators have the capability and powers to regulate AI within their sectors, and that voluntary coordination will produce a coherent national approach.

**Regulator capability is uneven.** The document acknowledges this — some regulators have "limited capacity and access to AI expertise." The MHRA is cited as a positive example of proactive adaptation, but it is an outlier. Most UK regulators have no AI-specific expertise and limited budgets. The document proposes a pooled team of AI experts and central support functions, but does not estimate what resources are needed or how they will be funded (the 10 million pound funding package came later in the consultation response).

**The coordination problem is structural.** The framework requires 14+ independent regulators to interpret and apply the same five principles consistently, without statutory backing and without a central body that can direct them. The DRCF provides a model for voluntary coordination among four digital regulators, but extending this to the full range of AI-relevant regulators (including MHRA, HSE, Ofsted, ONR) is a different challenge. The document's answer — central support functions — is necessary but may not be sufficient.

**The sandbox proposal is realistic.** The four sandbox models are practical, and the consultation approach (asking which sectors and models would be most useful) is sensible. The multi-regulator models directly address the cross-cutting nature of AI applications. This is one of the document's strongest concrete proposals.

**The timeline is ambitious for process, absent for outcomes.** Publishing principles and a roadmap within 6 months is achievable. Getting regulators to publish AI guidance within 12 months is challenging but feasible. Delivering a functioning cross-economy risk register within 12+ months is ambitious. None of these process milestones guarantee that AI is actually regulated effectively.

### Internal Consistency

The document is largely internally consistent, but contains one foundational tension that runs throughout:

**The innovation-safety balance.** The document's title, framing, and repeated emphasis are "pro-innovation." But the five principles — safety, transparency, fairness, accountability, contestability — are fundamentally about constraint. The document resolves this by arguing that good regulation enables innovation (which is true), but in practice, every principle involves trade-offs. Transparency requirements increase compliance costs. Safety testing delays deployment. Fairness audits require data access that developers may resist. The document acknowledges these trade-offs in the abstract but does not address how regulators should resolve them in practice.

A secondary tension exists between the context-specific philosophy and the cross-cutting principles. If regulation should be context-specific, why are the principles cross-cutting? The document's answer — principles provide coherence, regulators provide context — is reasonable in theory, but in practice it means the principles must be abstract enough to apply everywhere, which makes them too vague to provide actionable guidance anywhere.

The framework's treatment of foundation models also reveals an internal tension. The document argues that regulation should focus on use, not technology — but simultaneously acknowledges that some technologies (foundation models) create risks that cannot be adequately addressed at the use level. This tension was the most significant issue identified in the subsequent consultation and led to the February 2024 response building the case for entity-level regulation of frontier AI developers.

### Coverage

For a framework document, the coverage is reasonably comprehensive. It addresses:

- AI definition and scope
- Risk categories (safety, security, fairness, privacy, societal wellbeing)
- Existing legal landscape and gaps
- Regulatory principles and implementation
- Central coordination and support
- Foundation models (surface level)
- Technical standards and assurance
- Regulatory sandboxes
- Territorial application and devolution
- International engagement and interoperability
- Implementation roadmap

What it does not cover: labour market impact, environmental sustainability, defence and security applications, agentic AI, algorithmic auditing requirements, citizens' digital rights, and enforcement mechanisms. Some of these are acknowledged as out of scope; others are simply absent.

### International Alignment

The document positions the UK as a leader in AI governance while maintaining distinctiveness from the EU approach. The post-Brexit framing is explicit: regulatory sovereignty enables a lighter, faster, more innovation-friendly approach than the EU AI Act (which was in development at the time of publication).

The international engagement is genuinely extensive — OECD, GPAI, G7, Council of Europe, UNESCO, ISO/IEC, plus bilateral relationships with 9+ countries. The UK's Bureau position on the Council of Europe CAI and founding membership of GPAI demonstrate substantive commitment, not just aspiration.

The principles-based approach aligns well with the OECD AI Principles (which also emphasise transparency, accountability, safety, and fairness) and is broadly compatible with Singapore's governance framework approach. It diverges most sharply from the EU's risk-classification model, which assigns binding obligations based on risk categories — the UK explicitly rejects this in favour of context-specific regulator judgement.

The document's weakness on international alignment is that it does not address mutual recognition or compliance burden. A UK company that also operates in the EU will need to comply with both the EU AI Act and the UK framework. The document asserts that it will "promote interoperability" but does not explain how.

---

## Overall Assessment

This white paper is a thoughtful, clearly articulated framework document that makes a coherent case for the UK's distinctive approach to AI regulation. Its core insight — that AI risks are best assessed in the context of specific applications by domain-expert regulators, rather than through technology-specific legislation — is defensible and has influenced international thinking.

Its greatest strength is architectural clarity. The five principles, context-specific philosophy, sector-regulator implementation, and central coordination functions form a coherent system. The two-characteristic AI definition is more durable than the technology-specific definitions adopted by other jurisdictions. The sandbox proposals are practical and well-designed.

Its greatest weakness is the gap between framework and implementation. The document proposes a system but does not equip it. Regulators are asked to implement principles without statutory backing, additional powers, or (at this stage) additional funding. Foundation model risks are identified but not addressed. Accountability across the AI life cycle is acknowledged as problematic but deferred to consultation. Enforcement is absent. The anticipated statutory duty — the mechanism that would give the framework teeth — has no timeline and no trigger conditions.

The document is best understood as the opening position in a multi-year regulatory development process, not as a finished policy. Its value lies in establishing the principles and architecture; its limitations lie in the deliberate deferral of every hard question to future work. The February 2024 consultation response partially addressed these limitations — particularly on foundation models and binding measures — but the core structural gap (non-statutory principles, uneven regulator capability, absent enforcement) remained unresolved as of that document.

The post-Brexit framing, while politically necessary, risks conflating regulatory distinctiveness with regulatory adequacy. Being different from the EU is not the same as being effective. The document's strongest sections are those that make the case for the UK approach on its own merits (context-specificity, regulator expertise, sandbox innovation); its weakest are those that define the approach primarily by what it is not (not the EU, not prescriptive, not technology-specific).

---

## Sources

- [A pro-innovation approach to AI regulation: white paper (GOV.UK)](https://www.gov.uk/government/publications/ai-regulation-a-pro-innovation-approach/white-paper)
- [OECD AI Principles](https://oecd.ai/en/ai-principles)
- [Digital Regulation Cooperation Forum (DRCF)](https://www.drcf.org.uk/)
