# Commission Guidelines on the Definition of an AI System — Review

**Document:** Commission Guidelines on the definition of an artificial intelligence system established by Regulation (EU) 2024/1689 (AI Act)
**Published:** Brussels, 29 July 2025
**Reference:** C(2025) 5053 final — Communication from the Commission
**Issuing body:** European Commission
**Length:** 12 pages
**Legal status:** Non-binding — authoritative interpretation ultimately rests with the CJEU

**Note on filename:** The source PDF was originally stored as `Guidelines-Definition-AI-System-Feb-2025.pdf`, but the document is dated 29 July 2025 (the "Feb 2025" reflected when Article 3(1) entered application, 2 Feb 2025). File has been renamed to `Guidelines-Definition-AI-System-Jul-2025.pdf`.

---

## Summary

This Commission Communication provides authoritative (but non-binding) interpretation of Article 3(1) of the AI Act — the definition of "AI system." The Guidelines break the definition into seven elements and analyse each, adopting a lifecycle-based perspective that distinguishes the pre-deployment "building" phase from the "use" phase. The Commission is explicit that no exhaustive list of AI systems is possible; each system must be assessed against the seven elements on its specific characteristics. The Guidelines also enumerate categories of systems that fall outside the definition despite superficial similarity to AI (mathematical optimisation, basic data processing, classical heuristics, simple prediction systems). The fundamental practical message: "The vast majority of systems, even if they qualify as AI systems within the meaning of Article 3(1), will not be subject to any regulatory requirements under the AI Act." Scope determines applicability; only prohibited practices (Article 5), high-risk systems (Article 6), and certain Article 50 transparency obligations actually impose obligations. General-purpose AI models are regulated separately under Chapter V and are outside these guidelines' scope.

---

## Key Points

### Legal Context (Paragraphs 1-7)

- AI Act entered into force **1 August 2024**
- Article 3(1) definition entered application **2 February 2025**, with Article 5 prohibitions
- Guidelines adopted under **Article 96(1)(f)** requirement
- Based on stakeholder consultation and European AI Board input
- **Non-binding** — CJEU has ultimate interpretive authority
- **No exhaustive list possible** — Recital 12 emphasises the definition must be "clearly defined while providing flexibility to accommodate the rapid technological developments"
- Guidelines are "adopted in parallel to Commission guidelines on prohibited artificial intelligence practices" (i.e. the companion Article 5 document)

### The Seven Elements of the AI System Definition

The Article 3(1) definition:
> "'AI system' means a machine-based system that is designed to operate with varying levels of autonomy and that may exhibit adaptiveness after deployment, and that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments."

Broken into seven elements:

1. **Machine-based system**
2. Designed to operate with **varying levels of autonomy**
3. **May exhibit adaptiveness** after deployment
4. For **explicit or implicit objectives**
5. **Infers, from the input it receives, how to generate outputs**
6. Outputs: **predictions, content, recommendations, or decisions**
7. Outputs **can influence physical or virtual environments**

Critically, the seven elements do not need to be continuously present across both lifecycle phases — some apply only to building phase, some to use phase.

### Element 1: Machine-based System

- Covers **both hardware and software** components (processing units, memory, storage, networking, I/O infrastructure; code, programs, operating systems, applications)
- Covers diverse computational systems including **quantum computing** and **biological or organic systems** so long as they provide computational capacity
- All AI systems are machine-based because training, data processing, predictive modelling, and large-scale automated decision-making require machines

### Element 2: Autonomy — "Varying Levels"

- Requires "some degree of independence of actions from human involvement"
- Systems designed to operate **solely with full manual human involvement are excluded**
- Human involvement can be direct (manual controls) or indirect (automated systems allowing humans to delegate or supervise)
- Example: A system that takes manually provided inputs and generates output by itself qualifies (the output is generated without manual control)
- **Level of autonomy is a necessary condition** for AI system status
- Important compliance link: autonomy level informs design of human oversight (Article 14) and risk mitigation measures

### Element 3: Adaptiveness — Facultative

- "May exhibit" — adaptiveness is **not required**
- Refers to self-learning capabilities allowing system behaviour to change while in use
- Post-deployment learning, pattern discovery, or data relationship identification is "facultative and thus not a decisive condition"

### Element 4: Objectives — Explicit or Implicit

- **Explicit objectives**: goals directly encoded by developer (e.g., optimising a cost function, probability, cumulative reward)
- **Implicit objectives**: goals not explicitly stated but deducible from behaviour or underlying assumptions
- Implicit objectives may arise from training data or from interaction with the environment
- **Distinct from "intended purpose"** (Article 3(12)) — intended purpose is externally oriented (how the system is meant to be deployed and operated); objectives are internal (what the system optimises toward)
- Example: a corporate virtual AI assistant has **objectives** to answer questions with high accuracy and low failure rate; the **intended purpose** is to assist a specific department with specific tasks within specific documents

### Element 5: Inferencing Using AI Techniques

This is the **key element** distinguishing AI systems from "simpler traditional software systems or programming approaches."

- Recital 12 clarifies: "the capability to infer" is the "key characteristic of AI systems"
- Does NOT contradict ISO/IEC 22989:2022 — "In AI, a premise is either a fact, a rule, a model, a feature or raw data"
- Covers both:
  - **Building phase** — deriving models or algorithms from inputs/data
  - **Use phase** — generating outputs using those models

**AI techniques enabling inference:**

**Machine learning approaches** — learn from data:
- **Supervised learning**: learns from labelled data (e.g., spam detection, image classification, medical diagnostics)
- **Unsupervised learning**: finds patterns in unlabelled data (e.g., drug discovery via clustering or anomaly detection)
- **Self-supervised learning**: subset of unsupervised, creates own labels from data (e.g., language models predicting next tokens, image recognition predicting missing pixels, GANs, contrastive learning)
- **Reinforcement learning**: learns from environment via reward function (e.g., robot arms, personalised content recommendations, autonomous vehicles)
- **Deep learning**: subset using layered neural networks for representation learning

**Logic- and knowledge-based approaches** — learn from encoded knowledge:
- Expert systems, knowledge representation, inductive logic programming
- Knowledge bases, inference and deductive engines, symbolic reasoning
- Search and optimisation methods
- Example: classical language processing based on grammatical knowledge; early expert systems for medical diagnosis

### Systems OUTSIDE the Definition (Paragraphs 40-51)

This is the most practically useful part of the Guidelines. Four categories are specifically excluded:

**(a) Mathematical optimisation systems**
- Systems that improve mathematical optimisation or accelerate/approximate traditional methods (linear regression, logistic regression)
- **Reason:** May have capacity to infer in a narrow sense, but do not transcend "basic data processing"
- Examples:
  - Physics-based systems using ML to accelerate simulations or estimate parameters fed into established physics models (e.g., cloud microphysics, turbulence)
  - Satellite telecommunication systems using ML to optimise bandwidth allocation and resource management
- Rationale: self-adjustments address functional/computational performance rather than intelligent decision-making

**(b) Basic data processing systems**
- Systems following predefined, explicit instructions or operations
- Operate on manual inputs or rules **without learning, reasoning, or modelling** at any lifecycle stage
- Examples:
  - Database management systems (e.g., "find all customers who purchased X last month")
  - Standard spreadsheet applications without AI-enabled functionalities
  - Software computing a population average from survey data
  - Sales report visualisation software using statistical methods to create dashboards
  - Opinion-poll analysis software computing validity, reliability, correlation, statistical significance

**(c) Classical heuristics**
- Problem-solving techniques using experience-based methods for approximate solutions
- Use predefined rules, pattern recognition, or trial-and-error **rather than data-driven learning**
- Example: chess programs using minimax with heuristic evaluation functions assessing board positions without learning from data

**(d) Simple prediction systems**
- Machine-based systems whose performance is achievable via a basic statistical learning rule
- Technically may use ML approaches but do not qualify due to limited performance
- Examples:
  - Financial forecasting using baseline mean strategy (always predicting historical average)
  - Weather prediction using previous week's average temperature as tomorrow's forecast
  - Customer support response time prediction based on mean of past data
  - Demand forecasting using historical average or mean

### Element 6: Outputs — Four Categories

- **Predictions**: estimate of unknown value from known inputs (self-driving car real-time predictions, energy consumption predictions)
- **Content**: new material generation — text, images, videos, music (GPT-style generative AI)
- **Recommendations**: suggestions for actions/products/services based on preferences/behaviours. Can scale with dataset growth in ways non-AI systems cannot
- **Decisions**: conclusions/choices automating traditionally human judgement processes

AI systems differ from non-AI systems in ability to handle complex relationships and patterns, generating more nuanced outputs.

### Element 7: Influence on Physical or Virtual Environments

- "Physical or virtual" — tangible objects (robot arms) AND digital spaces, data flows, software ecosystems
- AI systems are **not passive** — they actively impact the environments in which they are deployed

### Grandfathering (footnote 6)

Systems placed on the market or put into service **before 2 August 2026** benefit from the Article 111(2) grandfathering clause. This is a critical practical point not in the main body of the Guidelines.

### GPAI Models Out of Scope (Paragraph 64)

The Guidelines explicitly do **not** address the distinction between AI systems and general-purpose AI models. Chapter V governs GPAI models; the analysis is separate.

---

## Observations

### Clarity

The Guidelines are clearly structured and technically literate. The seven-element decomposition is analytically useful, and the worked examples for machine learning approaches (spam detection, drug discovery, GANs, robotic grasping, autonomous vehicles) ground abstract concepts.

The strongest clarity contribution is the **explicit exclusion list**. For practitioners determining scope, the ability to point to paragraphs 42-51 and say "our product is a classical heuristic / basic data processing / simple prediction system" is significantly more actionable than reasoning abstractly about the seven elements.

Two clarity issues:

- **"Basic data processing" vs "AI techniques" boundary**: The distinction between a physics simulation using ML to accelerate computation (out of scope) and an AI system using ML to make predictions (in scope) is fact-specific. The test — whether the system "transcends basic data processing" — is subjective. Practitioners will need to document their reasoning carefully
- **"Simple prediction systems" scope**: The examples given (baseline mean strategy, average temperature prediction) are trivial. More realistic products typically combine simple predictions with other capabilities — a weather API may offer both mean-based historical forecasts and ML-driven probabilistic forecasts. The Guidelines do not address hybrid systems

### Measurability

The Guidelines offer no quantitative thresholds. Determining whether a system:
- "transcends basic data processing" (paragraph 42)
- uses "more than" a basic statistical learning rule (paragraph 49)
- generates outputs with "sophisticated reasoning" (paragraph 59)

...is qualitative judgement. This is partly inherent to Article 3(1)'s technology-neutral definition, but it means scope determinations in marginal cases will be contested. Providers of products near the boundary will need to document their reasoning and prepare for challenge.

### Gaps

**Boundary with software engineering.** Modern software development increasingly uses ML at the edges — autocomplete, anomaly detection in monitoring, recommender systems for code snippets. The Guidelines provide principles but not specific boundary tests. A code autocomplete feature using a fine-tuned LLM is almost certainly an AI system; what about a regex-based text classifier used to route customer complaints?

**Embedded AI components.** The Guidelines treat AI systems as unitary. In practice, many products integrate AI components into larger systems (e.g., a CRM system with AI-driven lead scoring). Whether the scope applies to the component, the containing system, or both is not addressed directly, though Article 25 on value chain roles is relevant.

**Evolution over time.** A product may start as a simple heuristic and later incorporate ML. Does scope depend on the current state or on future trajectory? The Guidelines do not address dynamic scope.

**GPAI model distinction deliberately excluded.** Paragraph 64 states that the analysis of differences between AI systems and GPAI models is "outside the scope of these Guidelines." This is a significant gap — practitioners deploying GPAI models often need to determine whether they are subject to AI system obligations or GPAI model obligations, or both. The Commission's separate GPAI Guidelines (July 2025) address this from the GPAI side but the boundary analysis is not consolidated.

**Organic and biological systems (paragraph 13).** The Guidelines briefly note that biological or organic systems providing computational capacity can be "machine-based." This is forward-looking (neuromorphic computing, biological computing) but gives no practical guidance on when such systems would be in scope.

**Interaction with OECD definition.** The Guidelines cite the OECD 2024 updated AI system definition in footnote 4 but do not systematically compare the EU and OECD definitions. For multinational firms, alignment between the two matters.

### Feasibility

The Guidelines are operationally feasible for practitioners to apply. The seven-element framework and exclusion list provide a usable decision process:

1. Is it machine-based? (usually yes for software)
2. Does it operate with some autonomy? (usually yes unless purely manual)
3. Does it use AI techniques to infer? (the key test)
4. Does it fall in one of the excluded categories?

If steps 1-2 are yes and step 3 is yes and step 4 is no, it is an AI system.

The harder question is what this means for obligations. The Guidelines themselves conclude (paragraph 63): "Only certain AI systems are subject to regulatory obligations and oversight under the AI Act." Being an AI system is a necessary but not sufficient condition for obligations. The actual regulatory burden depends on Article 5 (prohibited), Article 6 (high-risk), or Article 50 (transparency) classification.

### Internal Consistency

The Guidelines are internally consistent. Three interpretive choices deserve note:

- **Machine learning approximating traditional methods can be out of scope** (paragraphs 42-45). This is a practically important but analytically awkward position — if a system uses ML techniques, how can it not be an AI system? The Guidelines' answer is that the **functional purpose** (accelerating traditional computation) rather than the **technique** determines scope. Whether this interpretation survives CJEU scrutiny is uncertain.
- **Adaptiveness is facultative** (paragraph 23). This is correct based on "may exhibit" in Article 3(1). But it means systems trained once and deployed without further learning qualify as AI systems if the other six elements are met. This catches most traditional ML deployments.
- **Objectives vs intended purpose distinction** (paragraphs 24-25). Internal objectives can be implicit; external intended purpose is set by the provider. This distinction matters because intended purpose determines Article 6 high-risk classification and other context-dependent obligations.

### Coverage

Coverage is appropriate for a scope-definition document. The Guidelines address the definition, provide analysis of each element, give worked examples, and explicitly identify excluded categories. They deliberately do not address:

- GPAI model / AI system distinction
- Downstream classification (high-risk, prohibited, transparency)
- Provider vs deployer role determination
- Interactions with other EU law (GDPR, product safety, consumer protection)

These are addressed in other Commission documents (GPAI Guidelines, Article 5 prohibited practices guidelines, AI Act itself).

### International Alignment

The Guidelines cite:
- **OECD 2024 updated AI system definition** — foundational reference
- **ISO/IEC 22989:2022** — AI concepts and terminology, aligned with the Commission's understanding of inference

The EU definition closely aligns with the OECD definition, which is important for global regulatory interoperability. UK firms familiar with OECD-aligned definitions will find the EU definition recognisable.

The US White House Executive Order definitions (now revoked) were also OECD-aligned; the UK's functional characteristics definition in the Pro-Innovation White Paper (adaptivity + autonomy) is narrower than the EU's seven-element approach. Firms operating across UK and EU face broadly compatible but not identical definitions.

---

## Overall Assessment

These Guidelines are a useful practical document. For a 12-page interpretive communication, they accomplish significantly more than their length suggests: they structure the Article 3(1) definition, clarify what counts as "AI technique," and — critically — identify categories of systems that fall outside scope despite superficial similarity.

Their greatest strength is the explicit exclusion list. Paragraphs 42-51 provide practitioners with concrete examples of non-AI systems (physics simulations, satellite bandwidth optimisation, database queries, spreadsheets, statistical dashboards, chess engines, baseline forecasters). This is substantially more useful than a pure definitional approach would be.

Their greatest limitation is the irreducible ambiguity at the boundary. "Transcends basic data processing" requires judgement. The Commission is honest about this — paragraph 62 states "No automatic determination or exhaustive lists of systems that either fall within or outside the definition of an AI system are possible." Scope will be contested in marginal cases; the Commission's future practice (and eventually CJEU rulings) will refine the boundary.

For UK-based firms serving EU clients, the key practical implications are:

1. **Use the seven-element test systematically.** For each product, document whether each element is met. This documentation is valuable evidence if scope is later contested.

2. **Claim exclusions explicitly where they apply.** If your system is a classical heuristic, a basic data processor, or a simple predictor, document that position with reference to the specific paragraph (42, 46, 48, or 49).

3. **Being in scope does not mean being regulated.** The Guidelines emphasise (paragraph 63) that most AI systems within Article 3(1) face no regulatory burden under the Act. Only prohibited, high-risk, or Article 50-transparency systems face substantive obligations.

4. **Remember grandfathering.** Systems placed on market before 2 August 2026 benefit from Article 111(2) grandfathering. This is a significant timing consideration for products launching in 2025 or early 2026.

5. **GPAI models require separate analysis.** If you provide or deploy GPAI models, these Guidelines do not apply to that role; refer to the Commission GPAI Guidelines (July 2025).

The Guidelines reinforce the EU AI Act's technology-neutral design philosophy. By defining AI functionally (inference from input) rather than technologically (specific algorithms), the Act avoids premature obsolescence but creates interpretive complexity. These Guidelines partially resolve that complexity; future guidance and jurisprudence will continue to refine it.

---

## Sources

- [Commission Guidelines on the definition of an AI system (C(2025) 5053)](https://digital-strategy.ec.europa.eu/en/library/commission-guidelines-definition-artificial-intelligence-system)
- [EU AI Act (Regulation 2024/1689)](../../source/EU-AI-Act-Regulation-2024-1689.pdf)
- [OECD updated AI system definition (2024)](https://doi.org/10.1787/623da898-en) — explanatory memorandum
- ISO/IEC 22989:2022 — AI concepts and terminology
- Companion: [Commission Guidelines on Prohibited AI Practices](../../source/Guidelines-Prohibited-AI-Practices-Jul-2025.pdf)
