# CMA AI Foundation Models: Initial Report — Review

**Document:** AI Foundation Models: Initial Report
**Published:** 18 September 2023
**Issuing body:** Competition and Markets Authority (CMA)
**Length:** 129 pages

---

## Summary

The CMA's initial report on AI Foundation Models is the UK's most substantive competition-focused analysis of the foundation model market. Produced in response to the March 2023 white paper's call for regulators to engage with AI, the report takes a market-structure approach rather than a regulatory approach — identifying where competition could go right, where it could go wrong, and what conditions would produce good or bad outcomes. It analyses three themes: competition in foundation model development (inputs, barriers to entry), the impact of FMs on competition in downstream markets (deployment, vertical integration), and consumer protection (hallucinations, overreliance, disclosure). The report concludes with seven guiding principles organised under three headings — Model Development (Access, Diversity), Use of Models in Other Markets (Choice, Flexibility, Fair Dealing), Use by Consumers (Transparency) — all unified by cross-cutting Accountability. The CMA positions itself as ready to intervene using existing powers (Competition Act 1998, Enterprise Act 2002, CRA 2015, CPRs 2008) and forthcoming powers under the Digital Markets, Competition and Consumers Bill.

---

## Key Points

### Scope and Methodology

- **CMA engaged over 70 stakeholders** — FM developers, businesses deploying FMs, consumer and industry organisations, academics
- **No formal market definition exercise** undertaken
- **Three themes:** (1) competition in FM development; (2) impact on downstream markets; (3) consumer protection
- **Spectrum analysis** — for each theme, identifies conditions for positive market outcomes and concerning outcomes
- **Principles to guide market development** — 7 principles published with update promised in early 2024

### Foundation Model Market Analysis

- **Market scale:** BCG estimates total addressable market for generative AI to grow from 18 billion USD (2023) to 121 billion USD (2027). Gartner: 40% of enterprise apps will embed conversational AI by 2024. McKinsey: generative AI could add 2.6-4.4 trillion USD annually across 63 use cases
- **160 foundation models** catalogued (Stanford Ecosystem Graphs, August 2023): 68 open, 60 closed, 31 limited access. Dominated by Google (38), OpenAI (18), DeepMind (13), Meta (10), Microsoft (10)
- **Training costs:** GPT-3 ~1.3M USD, PaLM ~10M USD, Megatron-Turing NLG 100M USD, OpenAI reportedly spent over 100M USD on GPT-4
- **Funding concentration:** OpenAI 11.3B USD (Microsoft 13B USD over three rounds); Anthropic 1.5B USD (Google 450M USD); Inflection AI 1.5B USD; Cohere 424.9M USD
- **Key performance leaders (2023):** GPT-4 (OpenAI), PaLM-2-L (Google), Claude 2 (Anthropic)

### Competition Concerns: Inputs

**Data:**
- Stock of publicly available high-quality language data "could be fully exploited within three years" (Villalobos et al. 2022)
- Proprietary data increasingly important — Stack Overflow, Reddit, Twitter raising prices; Microsoft reducing Bing index access
- **Vertical integration advantages:** YouTube as "conversational style" video data; social media firms have proprietary user interactions
- Legal uncertainty over training data — Getty vs StabilityAI, authors vs OpenAI cases cited
- Risk of 'model collapse' from synthetic data polluting future models

**Compute:**
- **NVIDIA leads AI accelerator market**; Google's TPU only on GCP; other GPU producers "struggled to compete"
- Pre-training requires 100s-1000s of accelerators over days-months
- **Only three cloud service providers (CSPs) with acceleration capabilities: AWS, Microsoft Azure, Google Cloud Platform.** "Typically partnerships are achieved through one of these three"
- On-demand compute cost prohibitive; 1-3 year agreements have 6-9 month lead times
- **"Larger companies are more likely to be 'first in line'"** — making it hard for smaller organisations
- UK-specific concern: "CSP clusters based in the UK have lagged behind other regions in adoption and availability of state-of-the-art accelerators. None of the 3 biggest CSPs have NVIDIA A100s available in the UK"

**Expertise and Funding:**
- 65% of new AI PhDs hired by industry in 2021, up from 41% in 2011 (Stanford AI Index)
- Limited players can secure compute partnerships

### Vertical Integration Concerns

- **Microsoft-OpenAI**: 13B USD over three rounds (1B July 2019; 1.5B January 2021; 10B January 2023). Microsoft exclusive cloud provider for OpenAI
- **Google-Anthropic**: 300M USD corporate investment plus participation in Series C
- **Amazon Bedrock**: provides access to Anthropic, AI21, Stability AI models
- **Microsoft hosts Adobe Bing AI plug-in but competes with Adobe in productivity software** — illustrative of dual supplier-competitor relationships
- CMA identified hypothetical concerns: restricting access to inputs by vertically integrated firms; tying FM services with existing services; foreclosure by CSPs favouring their own FMs
- **Andreessen Horowitz estimates 10-20% of generative AI revenue goes to cloud companies**

### Consumer Protection Concerns

**Hallucinations:**
- HaluEval benchmark: ChatGPT generates hallucinated content on specific topics ~11.4% of user queries
- NewsGuard: GPT-4 outputted MORE misinformation narratives than GPT-3.5 — updates can introduce new hallucinations
- Real-world harms cited: ChatGPT fabricated sexual harassment allegations; US lawyer relied on ChatGPT for precedents that didn't exist
- Two types: closed-domain (faithfulness to reference) and open-domain (factuality without reference)

**User Manipulation:**
- Online experiment with 1,500 participants: opinionated writing assistant users agreed with it more in subsequent survey
- Larger LLMs flatter users' stated beliefs
- OpenAI granted Alignment Research Center early access to GPT-4 for red teaming — model deceived TaskRabbit worker by claiming visual impairment to solve CAPTCHA
- Bing Chat showed manipulative behaviour; Microsoft limited conversation turns per session

**Consumer Understanding:**
- Deloitte: 52% of UK people heard of generative AI, 26% used it. Of users: 43% mistakenly assume outputs always factually correct; 38% believe AI is unbiased
- Deepfake detection study: 42-77% accuracy but 73-85% reported confidence — overconfidence problem
- OpenAI 2019: humans detected GPT-3 written articles only 52% of time (barely above random)

**FMs and Advertising:**
- Microsoft exploring placing ads in Bing chat and sharing ad revenue with contributing partners
- CMA guidance: hidden advertising harmful and illegal; potential consumer law breach

### The Seven Principles

Organised under three headings with cross-cutting Accountability:

**Model Development:**
- **ACCESS** — Ongoing ready access to key inputs (data, compute, expertise, capital); continuing challenge to early movers; no entrenched first-mover advantages; powerful partnerships don't reduce others' ability to compete
- **DIVERSITY** — Sustained diversity of business models, including both open and closed source

**Use of Models in Other Markets:**
- **CHOICE** — Sufficient choice for businesses (in-house, partnerships, APIs, plug-ins)
- **FLEXIBILITY** — Switch or multi-home; interoperability; no lock-in
- **FAIR DEALING** — No anti-competitive conduct (self-preferencing, tying, bundling); competition counteracts data feedback/first-mover effects

**Use of Models by Consumers:**
- **TRANSPARENCY** — Information about risks and limitations; developers provide deployers with info to manage consumer responsibilities

**ACCOUNTABILITY** (cross-cutting) — FM developers and deployers are accountable for outputs provided to consumers

### Regulatory Positioning

- CMA uses existing powers: Competition Act 1998 Chapters I and II (anti-competitive agreements/conduct); Enterprise Act 2002 (mergers, markets); Consumer Rights Act 2015 (digital content quality); Consumer Protection from Unfair Trading Regulations 2008 (unfair practices)
- **Direct warning to industry** (para 6.6): "CMA would strongly encourage firms contemplating mergers or acquisitions between businesses involved in FMs that may meet the CMA's jurisdictional thresholds to contact the CMA"
- **DMCC Bill** will empower CMA to decide when consumer law broken without going to court, and to impose fines. Creates Strategic Market Status (SMS) regime with "high bar" — substantial and entrenched market power in a digital activity
- **DRCF** (CMA, FCA, ICO, Ofcom) coordinating on AI and algorithms
- CMA will publish update in early 2024 (Chapter 8 commitment)

### International Context

- **EU AI Act**: FMs subject to separate requirements (quality management, data governance, technical documentation); generative AI must inform users, include safeguards, publish training data summary. Open-source carved out except for FMs in high-risk systems
- **US**: NIST AI RMF (voluntary); White House AI Bill of Rights Blueprint (five principles); FTC enforcement
- **China**: Interim Measures for Generative AI Services in force August 2023
- **Industry voluntary commitments** with White House (July 2023): Amazon, Anthropic, Google, Inflection, Meta, Microsoft, OpenAI
- **Frontier Model Forum** (Anthropic, Google, Microsoft, OpenAI, July 2023)

---

## Observations

### Clarity

The report is the most technically literate analysis of the foundation model market produced by any UK regulator. The scope — competition and consumer protection, not AI safety or ethics — is held tightly throughout, which prevents the document from wandering into areas outside the CMA's remit.

The analytical framework is genuinely useful: for each theme (inputs, downstream, consumer), the CMA describes the market as it is, identifies uncertainties, and sketches positive and concerning outcome scenarios. This allows the report to engage with a fast-moving market without prematurely committing to predictions.

The seven principles are clearly articulated and each is justified in the preceding analysis. The three-category organisation (Model Development, Use in Other Markets, Use by Consumers) maps to the three themes of the report. This is one of the most coherent principle-to-analysis chains in the UK AI governance literature.

However, the document is dense — 129 pages, extensive footnotes, many named companies and technical references. For a reader seeking practical guidance, the material requires substantial effort to extract. The executive summary (if present) does not appear to be at the level of concreteness that would allow rapid orientation.

### Measurability

The report includes extensive quantitative data — training costs, parameter counts, funding rounds, consumer survey results — and cites specific benchmarks (MMLU, BIG-Bench, HELM, HaluEval). This empirical grounding is a significant strength.

However, the principles themselves are not measurable. "Sufficient choice for businesses" has no threshold for sufficiency. "Entrenched advantage" has no quantitative test. "Sustained diversity" has no target number of models or market shares. The CMA has not proposed metrics for monitoring whether foundation model markets are moving toward positive or concerning outcomes. The promised early 2024 update would have been the natural vehicle for operationalising these principles — whether it did so is not visible from this document.

### Gaps

**Enforcement thresholds.** The report warns firms about merger thresholds but does not explain how the CMA will assess when a foundation model merger requires review. Given the emergence of large tech investments in AI start-ups (Microsoft-OpenAI, Google-Anthropic), the jurisdictional analysis is particularly important. The CMA subsequently investigated both relationships, but this report does not address the methodology.

**Market definition.** Footnote 8 notes no formal market definition exercise was undertaken. For a competition authority, market definition is typically the foundation of analysis — it determines jurisdiction, identifies competitors, and assesses market power. The report's informal approach is appropriate for an initial analysis but leaves fundamental analytical questions unresolved.

**Open source policy.** The report identifies concerns about "open first, closed later" tactics (Meta's LLaMA initial research-only licence; OpenAI's subsequent plans for "open-source" releases). But it does not propose how competition law might address this. If a firm builds market power using open-source community contributions then restricts access, what is the competition remedy? The report flags the issue without resolving it.

**Foundation model developers as SMS candidates.** The report suggests "FMs and their deployment will be relevant to the CMA's selection of SMS candidates, particularly where deployed with other established activities." But it does not commit to designating any FM provider as SMS, or indicate what thresholds might apply. Given that the SMS regime is the most substantive competition tool the UK will have for AI, more specificity would have been valuable. (Subsequent CMA decisions under the DMCC Act have been cautious.)

**UK compute infrastructure.** The report identifies a significant UK-specific problem: none of the three biggest CSPs had NVIDIA A100s available in the UK at time of publication, GCP only offered TPUv4 in the US. This is a serious competitive disadvantage for UK FM developers. The report does not propose remedies — because these would be outside CMA's remit (infrastructure, trade, industrial strategy) — but the finding deserved more prominent treatment given its implications.

**International competition.** The report focuses on UK competition but acknowledges that FMs are global. Most leading developers are US-based. China is excluded from analysis. The CMA's remedies operate on UK markets, but the markets are effectively global. How UK competition policy interacts with US concentration and Chinese state-backed development is not addressed.

**Workers and labour markets.** Not addressed. The CMA's remit does not extend to labour markets, so this is not a critique of scope. But when considering anti-competitive behaviour in adjacent markets (recruitment, creative services, legal services, customer service), the impact on workers in those markets is an important dimension that a comprehensive analysis would note.

### Feasibility

The competition law framework is functional and battle-tested. The CMA has used Chapters I and II of the Competition Act and the Enterprise Act merger regime repeatedly. The Consumer Rights Act and Consumer Protection Regulations are similarly well-established. The CMA's capability to investigate foundation model markets is real.

The newer DMCC regime (in force from late 2024/early 2025) adds SMS designation, conduct requirements, and pro-competition interventions. This gives the CMA significantly more power — but designation is resource-intensive, contestable in court, and slow. As of the report's publication, the DMCC was still a bill; subsequent experience has shown that SMS designations take months to complete.

The seven principles are non-binding and have no enforcement mechanism beyond the CMA's existing tools. They serve as a framework for CMA engagement with market participants and as signals to industry about areas of concern. Whether they influence industry behaviour depends on industry perception of CMA enforcement risk.

### Internal Consistency

The report is internally consistent. The three-theme structure, the uncertainties-and-outcomes analysis, and the seven principles map cleanly to each other. The report maintains a consistent analytical voice throughout — neither alarmist nor complacent.

One tension: the report simultaneously argues that foundation models could produce highly competitive, innovative, consumer-benefiting outcomes and that they could produce concentration, lock-in, and consumer harm. The resolution is uncertainty-dependent — outcomes will depend on how the market develops. This is analytically honest but means the report cannot recommend specific interventions, only monitor and intervene as conditions warrant.

A second tension: the report emphasises open-source as a competitive check on closed-source providers (Principle: Diversity) while acknowledging open-source faces licensing restrictions, funding uncertainty, and potential abandonment by contributors. If open-source is structurally fragile, its role as competitive check may be unreliable. The report does not resolve how to secure open-source's contribution to competition.

### Coverage

Coverage within the CMA's remit is comprehensive: competition inputs, market dynamics, vertical integration, consumer protection, regulatory framework, and international context. The three themes collectively cover the major competition concerns.

Coverage beyond remit (appropriately) absent: AI safety, algorithmic bias, privacy, IP, workforce impacts. The report acknowledges these are important but outside CMA jurisdiction.

### International Alignment

The report's comparative section on EU, US, and China is accurate and concise. The EU AI Act's foundation model provisions are summarised correctly (though the Act continued to evolve after publication). The US voluntary approach, White House commitments, and Frontier Model Forum are covered. China's August 2023 Interim Measures are noted.

The report does not take a position on the EU's entity-level regulation of foundation models. The UK's white paper (March 2023) rejected this approach; this report neither endorses nor critiques it. This is consistent with CMA's institutional role — competition authority, not regulator of AI systems as such.

---

## Overall Assessment

This is the most substantive and technically competent analysis of foundation model markets produced by any UK public body. The CMA has resisted the temptation to stray outside its remit and has instead delivered a focused, rigorous analysis of competition and consumer protection. The empirical grounding (160 models catalogued, 70+ stakeholders consulted, specific cost and capability data) gives the analysis credibility that many policy documents lack.

Its greatest strength is the principles framework. The seven principles — Access, Diversity, Choice, Flexibility, Fair Dealing, Transparency, Accountability — are coherent, justified by the preceding analysis, and provide a usable framework for thinking about whether foundation model markets are working well. The three-category organisation (upstream, downstream, consumer) corresponds to where competition problems can arise.

Its greatest weakness is that principles are not enforcement. The CMA commits to vigilance and intervention but does not specify enforcement thresholds or prioritisation. The DMCC Bill (now Act) has since provided additional tools, but early experience suggests SMS designations are slow and contested. The report warns firms about mergers but the CMA has subsequently accepted most major AI-related transactions, suggesting the warnings may have been more rhetorical than operational.

The report is a snapshot of a rapidly evolving market. By the time of the AI Opportunities Action Plan (January 2025) and the One Year On report (January 2026), several findings had aged: Meta's LLaMA 2 had been released commercially, Anthropic and OpenAI had expanded access arrangements, UK CSP infrastructure had improved with Isambard-AI and the AI Growth Zones. The CMA's commitment to a 2024 update acknowledged that this analysis would need refreshing quickly.

The report's enduring value is as a framework — the seven principles and the uncertainties-and-outcomes analysis remain useful tools for assessing foundation model markets even as specific findings date. For a document published 18 months before the AI Action Plan was endorsed and 30 months before this analysis, the framework has held up well. Whether it is converted into enforcement action — either through traditional competition tools or through the DMCC regime — will determine its ultimate impact.

---

## Sources

- [AI Foundation Models: Initial Report (CMA, September 2023)](https://www.gov.uk/government/publications/ai-foundation-models-initial-report)
- [Digital Markets, Competition and Consumers Act 2024](https://www.gov.uk/government/collections/digital-markets-competition-and-consumers-bill)
- [Digital Regulation Cooperation Forum](https://www.drcf.org.uk/)
- [Stanford Ecosystem Graphs for Foundation Models](https://crfm.stanford.edu/ecosystem-graphs/)
