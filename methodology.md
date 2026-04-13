# Assessment Methodology

A structured framework for analysing national AI strategies, policies, frameworks, and regulations. Adapted from the methodology developed for the [multi-LLM review of Scotland's AI Strategy 2026-2031](https://github.com/EdwardAThomson/AI_Scotland).

## Approach

### 1. Source collection

Gather the primary documents that define a country's AI governance position:

- National AI strategies and action plans
- Binding legislation and regulations
- Non-binding governance frameworks and guidance
- Sector-specific AI policies
- Progress reports and implementation updates
- Relevant international commitments

Source documents are stored as PDFs in each country's `source/` directory. Where useful, key documents are converted to markdown for structured analysis.

### 2. Landscape mapping

Before deep analysis, map the full landscape of a country's AI governance documents. Many countries do not have a single consolidated strategy — the UK, for example, distributes its AI policy across multiple publications (action plans, sector strategies, playbooks, safety frameworks). Understanding which documents exist and how they relate to each other is a prerequisite for meaningful analysis.

### 3. Section-level review

For major strategy documents, conduct section-by-section reviews using the following analytical lenses:

- **Clarity** — Is the language precise and unambiguous? Are commitments specific or vague? Does jargon obscure meaning?
- **Measurability** — Are outcomes defined with baselines, metrics, and success criteria? Could the government claim success without meaningful change?
- **Gaps** — What is missing? What does the document avoid addressing? Are there obvious questions left unanswered?
- **Feasibility** — Are proposed actions realistic given the timelines, resources, and powers available to the government?
- **Internal consistency** — Do actions map to stated outcomes? Do different parts of the strategy contradict each other?
- **Coverage** — Does the document address the full AI landscape (foundation models, agentic systems, sector applications, safety) or is it narrow in scope?
- **International alignment** — How does the approach align with or diverge from international standards and the positions of other nations?

Not every lens applies to every document. Use the ones that are relevant.

### 4. Multi-LLM review (where applicable)

For flagship strategy documents, the full multi-LLM review process can be applied:

1. **Extract** — Convert the document into structured markdown sections
2. **Review** — Each LLM independently reviews every section using the shared analytical lenses
3. **Reconcile** — Cross-reference all reviews to identify consensus findings, unique insights, disagreements, and meta-gaps

This approach was validated on Scotland's AI Strategy, where three LLMs (Claude, GPT, Gemini) independently reviewed 21 sections, producing 63 section-level reviews that were then reconciled. The reconciliation identified 17 consensus findings, 26 unique findings, and 18 disagreements.

The multi-LLM approach is most valuable for long, substantive strategy documents. Shorter frameworks, guidance documents, or regulations may not warrant the full treatment — a single analyst review using the shared lenses is sufficient.

### 5. Cross-country comparison

As country-level analyses accumulate, comparative analysis identifies:

- **Common themes** — commitments or concerns that appear across multiple national strategies
- **Divergent approaches** — areas where countries take meaningfully different positions
- **Universal gaps** — issues that no country adequately addresses
- **Leading practices** — approaches from one country that others could learn from

## Review structure

Each review file follows this format:

### Summary
A concise summary of the section or document (2-3 sentences). What is it about and what is it trying to achieve?

### Key points
A bullet list of concrete commitments, claims, or arguments. Focus on what the government is committing to, not general scene-setting.

### Observations
Critical analysis organised under the relevant analytical lenses (clarity, measurability, gaps, feasibility, internal consistency, coverage, international alignment).

## Tone

Analysis should be rigorous and constructive. The goal is to understand each country's strengths and weaknesses, identify gaps, and enable meaningful comparison — not to score political points. Where criticism is warranted, it should be specific and grounded in the text.

## Output

Analysis files are stored in each country's `analysis/` directory. File naming should be descriptive and consistent:

```
analysis/01-national-strategy-overview.md
analysis/02-regulatory-framework.md
analysis/03-agentic-ai-governance.md
```

For countries that receive the full multi-LLM review, the directory structure expands:

```
analysis/
  review-claude/
  review-gemini/
  review-gpt/
  review-reconciliation/
```
