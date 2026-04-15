# First Draft Code of Practice on Transparency of AI-Generated Content — Review

**Document:** First Draft Code of Practice on Transparency of AI-Generated Content
**Published:** 17 December 2025
**Status:** First draft; second draft expected mid-March 2026; final expected June 2026 ahead of Article 50 entry into application (2 August 2026)
**Issuing body:** EU AI Office, facilitated by two dedicated Working Groups
**Legal basis:** Code of practice under Article 56 AI Act, covering Article 50(2), (4) and (5) obligations
**Length:** 32 pages

**Working Group leadership:**
- WG1 (Providers — marking/detection): Kalina Bontcheva (Chair), Dino Pedreschi (Co-Chair), Christian Riess (Vice-Chair)
- WG2 (Deployers — deepfake and text labelling): Anja Bechmann (Chair), Giovanni De Gregorio (Vice-Chair), Madalina Botan (Vice-Chair)

**Drafting process inputs:**
- 187 written submissions from multi-stakeholder public consultation
- Three workshops (17 and 18 November 2025)
- Review of commissioned academic studies
- Relevant standards and international approaches
- Hundreds of participant industry, academia, and civil society contributions, plus Member State input

---

## Summary

This first draft Code operationalises Article 50 of the EU AI Act — the transparency obligations for AI-generated and manipulated content — through two parallel tracks. Section 1 addresses **providers of generative AI systems** (Article 50(2) and (5)), requiring machine-readable marking and detection mechanisms for synthetic audio, image, video, and text outputs. Section 2 addresses **deployers of AI systems** (Article 50(4) and (5)), requiring human-readable labelling of deepfakes (images, audio, video that appreciably resemble real persons/objects/events) and of AI-generated or manipulated text published on matters of public interest. The draft establishes a "multi-layered approach" to marking — recognising that no single technique can satisfy all legal requirements — combining metadata embedding, imperceptible watermarks, fingerprinting, and open API detectors. Section 2 introduces a common two-level taxonomy distinguishing "fully AI-generated" from "AI-assisted" content, an interim AI icon (two-letter acronym in Member State languages), and modality-specific labelling rules for real-time video, non-real-time video, multimodal, image-only, and audio-only content. The Code is explicitly a work-in-progress — the draft acknowledges several underdeveloped areas including marking of AI-generated software code, very short text outputs, agentic AI outputs, gaming, VR, and voice assistants.

---

## Key Points

### Scope and Legal Framework

**Section 1 (Providers)** implements:
- Article 50(2) AI Act — providers of AI systems generating synthetic audio, image, video, or text must ensure outputs are marked in a machine-readable format and detectable as artificially generated or manipulated. Technical solutions must be **effective, interoperable, robust, and reliable** as far as technically feasible
- Article 50(5) AI Act — information provided to natural persons in a clear and distinguishable manner at the latest at first interaction/exposure, conforming to applicable accessibility requirements

**Section 2 (Deployers)** implements:
- Article 50(4) AI Act — deployers must disclose when image/audio/video constitutes a deepfake, and when AI-generated/manipulated text is published on matters of public interest
- Article 50(5) AI Act — clear and distinguishable disclosure at first interaction/exposure

**Exceptions:** The Article 50(4) obligation does not apply where use is authorised by law for criminal offence detection/prevention/investigation/prosecution. For artistic, creative, satirical, fictional or analogous works, the obligation is limited to disclosure of existence in an appropriate manner that does not hamper display or enjoyment. For AI-generated text published on matters of public interest, the obligation does not apply where the content has undergone human review or editorial control with a natural or legal person holding editorial responsibility.

### Section 1: Provider Obligations (Marking and Detection)

**Four Commitments, twelve Measures total.**

#### Commitment 1 — Multi-layered Marking of AI-Generated Content (7 measures)

- **Measure 1.1: Machine-readable marking techniques** — Implement multiple layers of marking:
  - **Sub-measure 1.1.1**: Metadata embedding for content formats that support it (image, video, document files). Must include provenance information and a digital signature of the generative AI system describing the operation type (prompting, editing, generation)
  - **Sub-measure 1.1.2**: Imperceptible watermarks interwoven within the content, difficult to separate, resistant to typical processing. Providers may embed watermarks during model training, model inference, or within model/system output. GPAI model providers should implement marking at the model level to facilitate downstream compliance
  - **Sub-measure 1.1.3**: Fingerprinting or logging facilities where necessary to address deficiencies in the other approaches — direct logging for text; perceptual hashing for visual content

- **Measure 1.2: Marking techniques for specific modalities**
  - **Sub-measure 1.2.1**: Provenance certificate for AI-generated text and other content that does not allow secure metadata embedding — digitally signed manifest enabling deployers to certify AI origin
  - **Sub-measure 1.2.2**: Marking of multimodal content must be synchronised across modalities so marking is recognisable when only one or a subset of modalities has been altered or exchanged

- **Measure 1.3: Structural marking for open-weight AI models and systems** — Signatories releasing open-weight models should implement structural marking techniques encoded in the weights during training, facilitating third-party compliance for generative systems built on top

- **Measure 1.4: Marking techniques at the level of the generative AI model** — Providers who are also model providers must implement machine-readable marking prior to model placement on the market, to facilitate downstream provider compliance

- **Measure 1.5: Non-removal of machine-readable marking** — Signatories must:
  - Ensure existing detectable marks are retained and not altered/removed when AI-generated content is used as input and transformed into a new output
  - Include in acceptable use policy, terms and conditions, or accompanying documentation a **prohibition on removal/tampering with marks** by deployers or third parties

- **Measure 1.6: Transparency of the provenance chain** — Record and embed through content marking the origin and provenance chain from AI-assisted or partially modified content where technologically possible. Consistently check marking and provenance of inputs; add or record all content provenance steps within AI systems (both AI and human) in a way that distinguishes additional operations

- **Measure 1.7: Functionality for perceptible markings** — For compliance with deployer obligations (Section 2), Signatories who provide generative AI systems must provide a functionality in their system's interface to enable deployers to directly include a perceptible mark or label in the content, enabled by default

#### Commitment 2 — Detection of the Marking of AI-Generated Content (5 measures)

- **Measure 2.1: Enable detection by users and other third parties** — Free-of-charge interface (API or user interface) or publicly available detector to verify with confidence scores whether content is AI-generated/manipulated. In case of business discontinuation, Signatories must make detectors available to market surveillance authorities to ensure legacy content remains detectable
- **Measure 2.2: Detectors for already marked AI-generated content produced by a generative AI model** — Model providers must provide detection mechanisms for content generated by their models
- **Measure 2.3: Forensic detection mechanisms** — Additional line of defence not depending on presence of active AI marking. Encouraged collaboration on development of an aggregated forensic detector
- **Measure 2.4: Human-understandable and accessible disclosure of verification and detection results** — Results embedded with human-understandable explanations; compliance with accessibility requirements
- **Measure 2.5: Support literacy for AI content provenance and verification** — Documentation, training materials for deployers and users; collaboration with academia and civil society

#### Commitment 3 — Requirements for Marking and Detection Techniques (5 measures)

- **Measure 3.1: Effectiveness** — Fit-for-purpose, effective in informing about artificial origin, computationally efficient, real-time-capable, quality-preserving, environmentally sustainable
- **Measure 3.2: Reliability** — False positive/false negative rates and bit error rates measured using relevant established metrics on samples unseen during training
- **Measure 3.3: Robustness** — High robustness to common alterations (mirroring, cropping, compression, screen capturing, paraphrasing, character deletions, resolution changes, pitch shifting, time stretching, format changes) and adversarial attacks (copying, removal, regeneration, modification, amortisation attacks). Security robustness via rate limits on detector access
- **Measure 3.4: Interoperability** — Solutions that work across distribution channels and technological environments. Collaboration on shared aggregated verifier(s) for outputs across generative AI systems
- **Measure 3.5: Advancing the state of the art** — Investment in scientific research; collaboration on watermark renewal/revocation/replacement schemes and future forensic models

#### Commitment 4 — Testing, verification and compliance (4 measures)

- **Measure 4.1: Compliance framework** — Documented framework of marking/detection processes; shared with market surveillance authorities on request
- **Measure 4.2: Testing, verification and monitoring** — Real-world testing prior to market placement and regularly thereafter, potentially involving independent experts or AI regulatory sandboxes. **Adaptive threat modelling approach** — moving beyond generic robustness benchmarks to realistic use-case-specific scenarios (recompression, transcoding, speech-to-speech revoicing)
- **Measure 4.3: Training** — Personnel training proportionate to provider size and resources (with SME/SMC considerations)
- **Measure 4.4: Cooperation with market surveillance authorities**

### Section 2: Deployer Obligations (Labelling)

**Three general commitments (Part A) + specific measures for deepfakes (Part B) + specific measures for AI-generated text (Part C).**

#### Part A: General Commitments for Deployers

**Commitment 1 — Disclosure of Origin of AI-Generated and Manipulated Content based on a Common Taxonomy and an Icon**

- **Measure 1.1: Implement a common taxonomy** — Two-level taxonomy:
  - **Fully AI-generated content** — fully and autonomously generated without human authorship (e.g., images, books, articles, political/social texts intended to persuade)
  - **AI-assisted content** — mixed human and AI involvement where AI affects meaning, factual accuracy, emotional tone, or elements that may falsely appear authentic. Examples listed:
    - Object removal
    - Face/voice replacement or modification
    - Adding AI-generated text to existing human-authored text or onto real images
    - Hybrid audio formats combining deep fake audio and authentic audio
    - Significant visual or audio alterations (beauty filters altering perceived age/emotional tone)
    - AI rewriting or summarising human-created text
    - AI-generated text imitating a specific person's style
    - AI-enabled alterations to description of events, actors, arguments, interpretations
    - Seemingly small AI alterations that change context (noise removal changing interview setting; background editing; colour adjustments like skin tone)

- **Measure 1.2: Applying a common icon**
  - **Sub-measure 1.2.1 (Interim)**: Two-letter acronym referring to AI, localised to Member State languages (AI, KI, IA). Icon requirements: clearly visible at first exposure, positioned appropriately for content format, non-interfering with artistic works, includes two-level taxonomy
  - **Sub-measure 1.2.2 (Pending development)**: Interactive EU common icon with different degrees of deceitful content indication; interactive features showing what was AI-generated or manipulated using Section 1 machine-readable information; placed in fixed position; potentially with audio-only disclosure variants

**Commitment 2 — Compliance, training and monitoring (3 measures)**
- **Measure 2.1**: Internal compliance documentation specifying labelling practice with concrete examples
- **Measure 2.2**: Training for personnel covering legal requirements, taxonomy/icon application, artistic work exceptions, accessibility, correction procedures. Proportionate to size and risk
- **Measure 2.3**: Cooperation with market surveillance authorities and third parties (including VLOPs/VLOSEs under DSA, certified fact-checking organisations like EFCSN and IFCN members) for confidential, secure flagging of mis-labelled or non-labelled content

**Commitment 3 — Ensure Accessible Disclosure for all Natural Persons**
- **Measure 3.1**: Accessibility for persons with disabilities — audio descriptions for visual indicators, visual/tactile cues for audio-only, high contrast icons, screen-reader compatibility, alt-text/metadata. Encourage implementation of harmonised standards including ETSI EN 301 549

#### Part B: Specific Commitment for Deepfakes (Article 50(4), 50(5))

**Commitment 4: Specific Measures for Deepfake Disclosure (3 measures)**

- **Measure 4.1: Internal processes for consistent classification of deepfake content** — Apply Article 3(60) definition consistently; consider target audience, distribution channels; determine exception applicability; human oversight (not only automation)

- **Measure 4.2: Clear and distinguishable disclosure** — Modality-specific sub-measures:
  - **4.2.1 Real-time video**: Icon displayed non-intrusively throughout exposure where feasible; disclaimer at beginning for appropriate duration
  - **4.2.2 Non-real-time video**: Icon disclosure via one or combination of: opening disclaimer (oral disclaimer requires simultaneous icon); icon consistently throughout in fixed place (for online platforms, just outside the video frame); closing credits disclaimer (must be accompanied by one of the first two)
  - **4.2.3 Other multimodal content** (image-text-sound, text-sound, image-sound, image-text): Consistently disclosed using icon; clearly visible without further interaction
  - **4.2.4 Image (single modality)**: Common icon placed consistently at every exposure in a fixed place; clearly distinguishable; not hidden in image layers
  - **4.2.5 Audio (single modality)**:
    - Short audio (<30 seconds, e.g., commercials/ads): Short audible disclaimer in plain language at beginning
    - Longer audio (podcasts etc.): Repeated audible disclaimers at beginning, intermediate phases, end
    - When screen available (car/smartphone display): Display icon at first exposure
    - If EU-wide icon includes audio-only solution, it may replace natural language disclaimer

- **Measure 4.3: Apply appropriate disclosure for creative works** — For evidently artistic, creative, satirical, fictional or analogous works:
  - Icon placed non-intrusively
  - Real-time/near-real-time video: Top or bottom corners, at least 5 seconds without further warnings throughout exposure
  - Video: Icon placed for timing sufficient to inform at first exposure without significantly interfering
  - Other multimodal: Icon at first exposure clearly visible
  - Image: Appropriate place at first exposure, possibly integrated into image or background, preserving user's ability to discern icon
  - Audio: If screen available, place icon at beginning; if no screen, non-intrusive audible disclaimer (potential EU-wide audible disclaimer using spoken disclosure, rhythmic cues, or sound-based signals)
  - **Third-party safeguards**: Deepfakes addressing political/societally sensitive topics require safeguards including disclaimers of deceitful elements and compliance with privacy/dignity rights under Union and Member States' law

#### Part C: Specific Commitment for AI-Generated and Manipulated Text (Article 50(4), 50(5))

**Commitment 5: Specific Measures for Disclosure of AI-Generated or Manipulated Text (3 measures)**

- **Measure 5.1: Internal processes** — Consistently identify AI-generated/manipulated text publications on matters of public interest where no human has reviewed and no natural or legal person has assumed editorial responsibility. Human oversight required
- **Measure 5.2: Clear and distinguishable disclosure** — Icon placed in fixed, clear and distinguishable position at first exposure. Possible locations: top of text, beside text, in colophon, after closing sentence
- **Measure 5.3: Human review, editorial control and responsibility** — To rely on the exception, Signatories must establish internal procedures and maintain minimal documentation demonstrating:
  - Identification of the natural or legal person with editorial responsibility (name, role, contact details)
  - Overview of concrete organisational and technical measures and human resources for human review/editorial control, including national specificities (linguistic, cultural, context-specific factors)
  - Date of review and approval
  - Reference to final approved version (file name, URL, internal identifier)
  - Optionally: nature of review, type of AI involvement

#### Glossary

Defines key operational terms:
- **Active marking** — adding/embedding marking (watermark or metadata)
- **Active detection** — verification of purposefully added markings
- **Adaptive threat modelling** — continuously monitoring and adapting security
- **Amortization attacks** — one-time attacker effort reused to make follow-up attacks cheaper
- **Digital signature** — cryptographic signature for authenticity verification
- **Fingerprinting** — detection via hashing or logging
- **Forensic detection** — detection not relying on active marking; signal characteristics or ML-trained classifier
- **Hashing / Perceptual hashing** — content reduction to short identifier for lookup
- **Logging** — verbatim recording for lookup (usually text)
- **Open-weight model** — model with publicly available weights, code, parameters
- **Provenance information** — digital record of origin and processing steps
- **Shared verifier** — detector for markings from multiple providers
- **Structural marking** — watermark embedded into model during training or inference
- **Synchronisation of markings** — cross-referencing between markings in multimodal content
- **User** — deployer per Article 3(4) AI Act, or another person using or exposed to content
- **Watermark** — marker interwoven within content

#### Appendix 1 — Sample Icons

Four example icon concepts:
- Figure 1: Two-colour "AI" icon distinguishing fully automated from AI-assisted (ChatGPT zero-shot prompt December 2025)
- Figure 2: Round icon with "AI" in bottom-right corner of AI-generated photo (Centre for AI Safety)
- Figure 3: Artifact studio icon using colors and acronyms (AI-generated vs AI-H for AI-assisted; with interactive function showing alterations) — published by Fast Company
- Figure 4: Adobe Content Credentials with embedded metadata

### Open Questions for Second Draft

The introductory note explicitly identifies areas requiring further development:

**Section 1 (Providers):**
- Feasible approaches to marking AI-generated software code (treated as a specific type of AI-generated text)
- Marking of very short texts (where marking reduces quality/utility significantly)
- Applicability to agentic AI, gaming, VR, voice assistants, and other novel content types
- Implementation of shared aggregated verifier(s) for Measures 2.1 and 3.4
- Clarity of terminological definitions in the Glossary

**Section 2 (Deployers):**
- Common icon specification — interim and long-term interactive solution, including audio-only dimension. Academic studies on citizens' discernment of AI content (with/without labels), use of similar labelling practices such as advertisement-labels including eye-tracking studies, experiments, surveys, focus groups
- Technical solutions for audio-only labelling
- Interactive function specification for what exactly has been AI-generated or manipulated
- Flagging system details
- Icon placement for specific modalities and creative works

### Consultation Timeline

- First draft: 17 December 2025
- Written feedback deadline: **23 January 2026 at 22:00 CET** via EUsurvey
- Stakeholder meetings: January 2026
- Second draft: Mid-March 2026
- Final Code: Expected June 2026
- Article 50 enters into application: **2 August 2026**

---

## Observations

### Clarity

The draft is clearly structured and explicitly flags its own limitations. The division between provider (Section 1) and deployer (Section 2) obligations aligns with the AI Act's architecture. The Model Documentation Form equivalent does not exist here because Article 50 is more operationally diverse — different modalities require different approaches, and different exceptions apply.

**Clarity strengths:**
- The **two-level taxonomy** (fully AI-generated vs AI-assisted) with concrete examples of AI-assisted content (voice replacement, noise removal that changes setting, colour adjustments like skin tone) gives deployers a tractable classification test
- **Modality-specific sub-measures** in Commitment 4 (real-time video, non-real-time video, multimodal, image, audio with sub-30-second and longer variants) are operationally actionable
- The **human review exception** for AI-generated text (Measure 5.3) specifies exactly what documentation is required to claim the exception: identified editorial responsibility holder, overview of review measures, date of review, reference to final version
- The **open questions section** in the introduction explicitly tells stakeholders what to focus feedback on

**Clarity weaknesses:**
- The draft itself acknowledges it "remains high-level and broad" in many areas — this is an early draft, not operationally complete
- The icon specification is deliberately incomplete pending usability research
- The boundary between "AI-assisted" requiring disclosure and AI tools that improve but don't materially change content (grammar check, translation) is not drawn precisely
- "Matters of public interest" for text disclosure (Measure 5.2) is left to AI Act interpretation; no additional clarity

### Measurability

Limited measurement specification, reflecting the draft's early stage. Where measurement exists:

- False positive / false negative rates for detection (Measure 3.2) — no specific thresholds set
- Bit error rates in decoded marker information — measured but no pass/fail threshold
- Short audio threshold of 30 seconds for single-disclaimer rule (Sub-measure 4.2.5)
- Creative works icon minimum duration of 5 seconds without further warnings (Measure 4.3)

Broader measurement challenges are acknowledged but not resolved:
- "Effectiveness" (Measure 3.1) — qualitative criteria
- "Robustness" (Measure 3.3) — list of alterations/attacks but no resistance thresholds
- "Interoperability" (Measure 3.4) — works "across distribution channels" with shared verifier TBD

### Gaps

**Software code marking.** Explicitly flagged as a gap (introductory note). AI-generated code is increasingly common in enterprise development; compliance approaches need to be defined. The existing measures assume content with display characteristics — text with displayable output, images, audio, video. Code is text but operates through execution rather than display.

**Agentic AI outputs.** AI agents producing sequences of actions, tool calls, or orchestrated outputs don't map cleanly onto "content" assumptions. An AI agent that writes a document, edits an image, and posts to social media creates multiple content artifacts each potentially triggering Article 50; the Code does not address agent-level compliance architecture.

**Very short text outputs.** Flagged as a gap. A one-sentence AI-generated comment, a chat response, a translated phrase — these are text but marking them may destroy utility. Threshold rules need defining.

**Novel content types.** Gaming, VR, voice assistants flagged as requiring new measures. These are large commercial domains not covered by current draft.

**Flagging system detail.** Section 2 Measure 2.3 commits to cooperation with third parties (VLOPs/VLOSEs under DSA, fact-checking organisations) but does not specify the technical flagging infrastructure — what API, what confidence metadata, what response times, what appeals process.

**Artistic/creative content boundaries.** Measure 4.3 addresses creative works but the boundary between evidently artistic content (e.g., deepfake in a comedy sketch) and content that purports to be factual (e.g., satirical political deepfake that some viewers take seriously) is left to case-by-case judgement. The political/societally sensitive topics safeguard requirement adds another interpretive layer.

**Deployers of aggregated content.** The Code addresses individual deployer obligations. Platforms that aggregate or distribute third-party content (social media, news aggregators) have DSA obligations but unclear AI Act interaction. The Code mentions VLOPs/VLOSEs but does not systematically address platform roles.

**Provider-deployer information flow.** Measure 1.7 (provider functionality for perceptible marking) is useful but the reverse — providers informing deployers about capability limitations, about the boundaries of marking reliability, about update schedules — is less developed. Deployers relying on provider marks need clear information about what they can claim.

**Enforcement coordination with sectoral regulators.** Article 50 transparency obligations interact with DSA, AVMSD, European Media Freedom Act, political advertising rules. The Code briefly acknowledges this in Recital (f) but does not map the compliance matrix in detail.

**Older content.** Content created before Article 50 entry into application (August 2026) is not retrospectively marked. Older AI-generated content circulating post-August 2026 will lack marks despite being AI-generated. The Code does not address this.

### Feasibility

For **providers**, feasibility varies by technique:

- **Metadata embedding** (Sub-measure 1.1.1) — feasible and already common (C2PA, Adobe Content Credentials)
- **Imperceptible watermarks** (Sub-measure 1.1.2) — technically feasible but robustness remains limited. Watermarks can be removed by determined adversaries
- **Logging/fingerprinting** (Sub-measure 1.1.3) — feasible for text but creates privacy concerns for logged queries
- **Forensic detection** (Measure 2.3) — research ongoing; current forensic classifiers have high false positive rates for recent generative models
- **Shared aggregated verifier** (Measure 3.4) — ambitious and dependent on industry cooperation; currently no such shared infrastructure

For **deployers**, feasibility is generally higher because labelling is a front-end implementation:

- **Common icon** (Measure 1.2) — easy to implement once designed
- **Real-time video disclosure** (Sub-measure 4.2.1) — feasible for most video platforms
- **Audio disclaimers** (Sub-measure 4.2.5) — feasible with existing audio production tooling
- **Text labelling** (Measure 5.2) — straightforward for publishers
- **Human review documentation** (Measure 5.3) — feasible but adds administrative burden for every published piece

The Code's feasibility crucially depends on:
1. Industry cooperation on shared verifier development
2. Finalisation of the EU common icon (pending usability research)
3. Development of marking protocols for underrepresented modalities
4. Clear thresholds for short-content marking exceptions

### Internal Consistency

The draft is internally consistent. The provider and deployer tracks reinforce each other — provider marks enable deployer verification; deployer interfaces use provider-supplied marking functionality (Measure 1.7 referencing Commitment 2 of Section 2).

One tension: The Code emphasises machine-readable marking (Section 1) alongside human-readable labelling (Section 2). These operate at different layers but can interact. A deployer might rely on provider's machine-readable mark to trigger human-readable label application — yet if the provider's mark is robust but hidden, users cannot verify by inspection, requiring trust in detection tooling. The Code partially addresses this via public detection interfaces (Measure 2.1) but does not resolve the trust architecture.

### Coverage

Coverage within scope is broad, though depth varies. Article 50(2), (4), and (5) are all addressed. Article 50(1) (chatbots disclosure that interaction is with AI) and Article 50(3) (emotion recognition, biometric categorisation) are not covered by this Code — they are addressed separately.

Major content modalities are addressed: text, image, audio, video, multimodal. Gaps (software code, agentic AI, gaming, VR, voice assistants) are acknowledged.

Exceptions are addressed: law enforcement, artistic/creative works, human editorial review for text. Implementation of exception reliance (e.g., editorial review documentation) is specified.

### International Alignment

The draft references:
- **C2PA (Coalition for Content Provenance and Authenticity)** standard for content credentials (implicit in metadata approaches; explicitly referenced in UK AI Playbook and earlier UK documents)
- **ETSI EN 301 549** harmonised standard for accessibility requirements
- **DSA (Digital Services Act)** for VLOPs/VLOSEs
- **AVMSD (Audiovisual Media Services Directive)** and **European Media Freedom Act** for political advertising

For UK-based firms, the Code aligns broadly with the UK's less prescriptive but conceptually similar approach to AI content transparency. The UK has no direct equivalent obligation, but:
- UK media regulators (Ofcom) have separate deepfake and disinformation concerns
- UK Data Protection Act and associated ICO guidance address AI-generated content affecting personal data
- UK election rules (PPERA) overlap with political advertising deepfake concerns

UK firms deploying AI-generated content for EU users or markets will face the EU obligations regardless of UK non-regulation. The Code creates a compliance floor that UK firms will likely adopt globally to avoid maintaining divergent implementations (the "Brussels effect" applied to AI content transparency).

---

## Overall Assessment

This first draft is an early but structurally coherent foundation for operationalising Article 50. It establishes the architecture (provider machine-readable marking + deployer human-readable labelling), the techniques (multi-layered marking, common icon with two-level taxonomy), and the modality-specific operational rules (real-time video, audio disclaimers, text labelling with editorial review exception).

Its greatest strength is the **explicit acknowledgement of incompleteness**. The introductory note lists the areas requiring further development (software code, agentic AI, very short text, gaming/VR/voice assistants, icon specification, flagging system). This positions the document as work-in-progress rather than finished product, inviting stakeholder input on specific questions.

Its greatest weakness is the dependency on future technical development. The Code requires:
- A finalised EU common icon (pending usability research)
- Operational shared aggregated verifier(s) (not yet built)
- Industry-agreed watermarking protocols with defined robustness thresholds
- Forensic detection mechanisms with acceptable false positive rates
- Implementation of novel modality coverage (VR, gaming, voice)

Without these, Signatories implementing the Code today are building against specifications that will change materially before August 2026.

For UK-based firms providing AI-generated content to EU users, the practical implications are:

1. **Plan for machine-readable marking** of generative AI system outputs. Adopt C2PA Content Credentials or similar metadata standards; implement watermarking where available; provide public detection interfaces. Expect requirements to tighten in second draft.

2. **Implement deployer labelling infrastructure.** Any firm deploying AI systems generating deepfakes or AI-generated text on matters of public interest needs:
   - Classification process (automated + human oversight) for identifying reportable content
   - Icon display infrastructure across all relevant distribution channels (video, audio, image, text)
   - Training programmes for personnel
   - Monitoring and third-party flagging response processes

3. **Document human editorial review.** For AI-generated text publications, maintain the Measure 5.3 documentation per publication: editorial responsibility holder, review measures, date, reference to approved version. This is the operational requirement to claim the exception.

4. **Track the second draft (March 2026) and final (June 2026).** The Code will evolve substantially. Build compliance processes that can adapt — particularly around the common icon, audio-only disclosure, and novel modality rules.

5. **Prepare for sectoral interaction.** AI content deployment intersects with DSA (for large platforms), AVMSD (for media services), European Media Freedom Act, political advertising rules, copyright, and personal data protection. Article 50 compliance is necessary but not sufficient.

6. **Build for the "Brussels effect."** UK firms serving both UK and EU markets will likely find it simpler to adopt EU-compliant transparency practices globally than to maintain divergent implementations. The UK's lighter-touch approach means EU practices become the default.

7. **Engage with the consultation.** The 23 January 2026 written feedback deadline is an opportunity to shape the second draft. Industry input on the acknowledged open questions (software code marking, short text, agentic AI, shared verifier implementation) will influence the June 2026 final.

The draft is more substantive than many "first drafts" in EU regulatory processes. It is not merely a placeholder but a genuine attempt to grapple with the operational challenges of transparency at scale. The final Code, due June 2026, will be the most detailed operational specification for AI content transparency globally. UK firms serving EU clients need to treat it as an operational compliance framework from August 2026.

---

## Sources

- [First Draft Code of Practice on Transparency of AI-Generated Content (PDF)](../../source/Transparency-Code-AI-Generated-Content-Draft1-Dec-2025.pdf)
- [Commission announcement page](https://digital-strategy.ec.europa.eu/en/library/first-draft-code-practice-transparency-ai-generated-content)
- [Policy landing page](https://digital-strategy.ec.europa.eu/en/policies/code-practice-ai-generated-content)
- Related reviews:
  - [EU AI Act (review 01)](01-eu-ai-act.md) — Article 50 source provisions
  - [Guidelines on Prohibited AI Practices (review 03)](03-guidelines-prohibited-ai-practices.md) — distinction from Article 5(1)(a) deceptive techniques
  - [GPAI Code of Practice (review 05)](05-gpai-code-of-practice.md) — provider obligations for GPAI models
- External standards referenced:
  - C2PA (Coalition for Content Provenance and Authenticity) — content credentials
  - ETSI EN 301 549 — accessibility requirements for ICT products and services
  - Digital Services Act (Regulation 2022/2065) — VLOPs/VLOSEs obligations
  - AVMSD (Directive 2010/13/EU as amended) — audiovisual media services
  - European Media Freedom Act
