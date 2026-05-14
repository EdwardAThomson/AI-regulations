## Summary

UK AI governance to date has been overwhelmingly executive and regulator-led: white papers, playbooks, regulator updates, and the DUAA 2025 reform of UK GDPR. The reviews in `review-claude/` cover that body of work. What they do not cover is **case law**, which is now starting to fill some of the gap left by the absence of a single AI statute. Two recent UK matters are material enough to record alongside the document reviews:

1. **Munir v Secretary of State for the Home Department [2026] UKUT 81 (IAC)** — reported Upper Tribunal decision on the risks of disclosing confidential or privileged material to public AI tools, with supervisor responsibility implications.
2. **Getty Images (US) Inc. & Ors v Stability AI Ltd** — High Court (Chancery Division) proceedings on copyright and trade-mark exposure for AI training and image generation; the substantive judgment was handed down 4 November 2025.

This note records both, with primary citations and the points relevant to AI policy design. It deliberately stays within what is in the public record at the time of writing — neither matter is yet fully settled in higher appellate authority.

---

## 1. Munir v Secretary of State for the Home Department [2026] UKUT 81 (IAC)

### Forum and posture

The Upper Tribunal (Immigration and Asylum Chamber) sits within its established **"Hamid" supervisory jurisdiction** over legal representatives appearing before it. The decision is not a substantive immigration judgment — it is a regulatory reasoning about professional conduct where AI tooling was used in the preparation of documents lodged with the Tribunal.

### What the Tribunal held

In the reported decision, the Upper Tribunal said that uploading confidential or privileged information into open-source AI tools — naming consumer ChatGPT — "is to place this information on the internet in the public domain, and thus to breach client confidentiality and waive legal privilege."

The Tribunal distinguished **closed-source AI tools** (it named Microsoft Copilot as an example) on the basis that, where data is not exposed to the public domain, such tools are available for tasks like summarisation without the same risks. The distinction was drawn on the architecture and data handling of the tool, not on its branding.

The Tribunal also treated supervisors as more culpable than the staff who directly used the AI tool, on the basis that the supervisor bears responsibility for the practice and training of those they supervise.

### Why it matters for AI governance, not just for lawyers

The case sits in the Tribunal's "Hamid" jurisdiction over legal representatives, but the underlying reasoning is **persuasive across regulated professional contexts** where confidentiality, privilege, or special-category data is in play. Read in combination with UK GDPR and ICO guidance on AI and data protection, the practical implications are:

- Uploading personal data, confidential information, or privileged communications to an **open-source / consumer-grade public LLM** is itself a disclosure event. For personal data, that raises UK GDPR Article 5 / Article 32 issues; for privilege, it may amount to waiver, and in *Munir* the Tribunal treated it that way on the facts; for regulated professional contexts, it may also trigger referral pathways (e.g. Solicitors Regulation Authority for solicitors, ICO for personal data).
- **Tool architecture matters.** Closed-source / enterprise deployments that contractually exclude training use and isolate tenant data sit in a different risk category from public consumer chat interfaces. AI policies that treat "AI tools" as a single category fail to make the distinction Munir relies on.
- **Supervisor accountability**: the Tribunal's reasoning that supervisors carry greater culpability than the staff who used the tool implies AI policy needs explicit allocation of supervisor responsibility for training, tooling choices, and oversight — not just user-facing acceptable use rules.

### Status

The decision is a reported Upper Tribunal judgment within the Hamid supervisory jurisdiction. It has immediate practical force for legal representatives appearing before the IAC and is a significant reported authority in that setting. Outside that forum, its effect is persuasive rather than universally binding, but firms in healthcare, financial services, education, and central government should still treat it as a serious signal of how UK decision-makers may view the use of public AI tools with confidential material until higher appellate authority addresses the point.

### Policy implication

AI policies and acceptable-use rules drafted before late 2025 typically do not address the public-vs-closed-source distinction with sufficient sharpness. Munir is the cleanest articulation in UK case law of why that distinction is material, and is the reference point we now use in policy generation downstream (see the Policy Wizard / Policy Scanner products in the `octonion-apps` workspace).

---

## 2. Getty Images (US) Inc. & Ors v Stability AI Ltd

### Forum and posture

England & Wales High Court, Chancery Division (Intellectual Property List). The action was brought in 2023 by Getty Images against Stability AI, alleging that Stable Diffusion was trained on Getty's image library without licence and that the model's outputs reproduced Getty's watermarks. The trial took place in mid-2025 and the substantive judgment was handed down on **4 November 2025**.

### What is settled in the public reporting

The case is the first substantive UK High Court judgment addressing AI training data and copyright. Headline points, based on the public judgment and contemporaneous reporting:

- Stability AI succeeded on the **primary copyright training-infringement claim** at the UK end, on the basis that the relevant training acts took place outside the UK and could not be brought within the relevant UK copyright infringement provisions.
- Getty succeeded in part on **trade-mark** and **passing-off** grounds in relation to outputs that reproduced Getty's watermarks.
- The judgment **did not** establish that scraping Getty's library for AI training was lawful as a matter of UK copyright law; it turned in significant part on where the acts of reproduction took place.

The CMA's 2023 Initial Report (review 09) had already flagged "legal uncertainty over training data — Getty vs StabilityAI, authors vs OpenAI cases cited" as a foundational uncertainty in the UK AI market. The November 2025 judgment is the first UK substantive answer, and it answers a narrower question than the market wanted.

### Why it matters for AI governance

- **Jurisdictional fragility of the training-data claim.** A UK-only copyright action against a foreign trainer of a foreign model is structurally hard. This re-emphasises that copyright reform — not litigation — is the lever for the UK if it wants to settle the training-data question. That is consistent with the position the AI Opportunities Action Plan and DUAA 2025 have *not* taken.
- **Output-side liability is real.** The trade-mark / passing-off finding shows the legal vulnerability is on outputs that reproduce identifiable third-party marks, watermarks, or distinctive features. AI deployers — not just trainers — sit in that risk space.
- **The "training data lawful basis" gap remains open.** Getty did not produce a clean UK answer to whether scraping copyrighted material to train a model is itself infringement under UK law. The UK Government's TDM-exception proposals (consulted on in 2024–2025) are now the policy track that matters.

### Status

The High Court judgment is first-instance. Appeals are reportedly contemplated. Outside the trade-mark issues, the case does not finally resolve UK copyright liability for foundation-model training; it resolves a jurisdictional and pleading question on the specific facts.

### Policy implication

For UK firms deploying third-party AI image generators or training their own models on third-party content:

- Treat **output-side IP exposure** (watermarks, distinctive marks, recognisable third-party content in generations) as the demonstrated legal-risk surface, not a theoretical one.
- Continue to treat **training-data lawful basis** as unsettled — the position is neither "lawful by default" nor "infringing by default" in UK law after Getty.
- For procurement of third-party generative tools, vendor indemnities for training-data and output IP claims are no longer optional in mature AI risk frameworks.

---

## Cross-cutting observations

1. **UK AI law is now partially case-led.** The pro-innovation framework relies on existing law applied by sector regulators and the courts. Munir and Getty are the first UK rulings of any substance applying that approach to actual AI use. Future reviews in this directory should treat case law as a recurring source category alongside government documents.

2. **The two cases hit different layers of the AI lifecycle.** Munir is about **deployer / user conduct** in handling data through AI tools; Getty is about **training and output IP**. Together they show the UK approach (existing law + sector regulation + litigation) does generate enforceable outcomes — but they are scattered across regimes (privilege / professional conduct / data protection / IP), not unified under an AI statute.

3. **Neither is fully settled.** Munir is a Upper Tribunal Hamid-jurisdiction ruling; Getty is a first-instance High Court judgment with appeal contemplated. Both are nonetheless operationally significant *now* — UK firms have to act on the law as it currently stands, not the law as it may eventually be settled.

---

## Sources

- Munir v Secretary of State for the Home Department [2026] UKUT 81 (IAC) — Upper Tribunal (Immigration and Asylum Chamber), Hamid supervisory jurisdiction; primary text relied on at ¶21.
- Getty Images (US) Inc. & Ors v Stability AI Ltd — England & Wales High Court (Chancery Division, Intellectual Property List); substantive judgment handed down 4 November 2025.
- CMA, AI Foundation Models: Initial Report (September 2023) — for the pre-Getty articulation of the training-data uncertainty (see review 09).
- DUAA 2025 — relevant for the data-protection overlay implicated by Munir (see review 14).
