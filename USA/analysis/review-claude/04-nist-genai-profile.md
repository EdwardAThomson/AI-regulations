# NIST AI 600-1: Generative AI Profile — Review

**Document:** NIST AI 600-1: Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile
**Published:** July 2024
**Issuing body:** National Institute of Standards and Technology (NIST)
**Legal status:** Voluntary; non-binding; companion to AI RMF 1.0
**Length:** ~56 pages

---

## Summary

NIST AI 600-1 extends the AI RMF 1.0 to generative AI by identifying 12 risks unique to or exacerbated by GenAI and mapping them to the RMF's four core functions (Govern, Map, Measure, Manage). The profile is designed to be used alongside the AI RMF, not as a replacement. It provides GenAI-specific actions and suggested measures for each risk within each function.

---

## Key Points

### 12 GenAI Risks

1. **CBRN Information or Capabilities** — potential to lower barriers for chemical, biological, radiological, or nuclear attacks
2. **Confabulation** — generation of plausible but factually incorrect content (also known as hallucination)
3. **Data Privacy** — risks to personal data through training data memorisation, inference, or prompt extraction
4. **Environmental Impacts** — energy and water consumption; carbon footprint of training and inference
5. **Homogenisation** — overreliance on few foundation models leading to monoculture and systemic risk
6. **Human-AI Configuration** — anthropomorphism, over-trust, automation bias, loss of human agency
7. **Information Integrity** — deepfakes, disinformation, manipulation at scale
8. **Information Security** — novel attack vectors (prompt injection, data poisoning, model theft, adversarial inputs)
9. **Intellectual Property** — training data copyright; output similarity; attribution
10. **Obscene, Degrading, and/or Abusive Content** — generation of harmful content including CSAM
11. **Value Chain and Component Integration** — risks from third-party models, APIs, fine-tuning, and deployment chains
12. **Harmful Bias and Homogenisation** — amplification of biases from training data; societal-scale feedback loops

### Structure

For each of the 12 risks, the profile provides:
- Risk description and context
- **GOVERN** actions (policies, governance structures)
- **MAP** actions (context, categorisation, impact assessment)
- **MEASURE** actions (metrics, testing, evaluation)
- **MANAGE** actions (mitigation, monitoring, response)

### Comparison with Other GenAI Frameworks

The 12 risks overlap substantially with:
- **EU AI Act** systemic risk categories (CBRN, cybersecurity — though the EU names 4 specified risks vs NIST's 12)
- **Singapore GenAI Framework** nine dimensions (accountability, data, security, content provenance, etc.)
- **EU GPAI Code of Practice** Safety and Security chapter (CBRN, Loss of Control, Cyber Offence, Harmful Manipulation)

The NIST profile is more granular (12 risks vs EU's 4 systemic risks) and more comprehensive in scope (covering environmental impact, homogenisation, and IP alongside safety risks).

---

## Observations

The GenAI Profile is technically strong — it provides the most comprehensive enumeration of GenAI-specific risks from any US government body. Its four-function mapping is practical and consistent with the parent RMF. It remains voluntary, with no enforcement mechanism.

The profile's durability is uncertain. The July 2025 AI Action Plan directs NIST to "revise the AI RMF to eliminate references to misinformation, DEI, and climate change." Several of the 12 risks (Information Integrity, Environmental Impacts, Harmful Bias) directly address these topics. Whether NIST will revise the GenAI Profile alongside the parent RMF is an open question.

---

## Sources

- [NIST AI 600-1: GenAI Profile (PDF)](../../source/NIST-AI-600-1-GenAI-Profile-Jul-2024.pdf)
- [NIST AI RMF website](https://www.nist.gov/itl/ai-risk-management-framework)
- Related reviews:
  - [NIST AI RMF 1.0 (review 01)](01-nist-ai-rmf.md) — parent framework
  - [Singapore GenAI Framework (SG review 02)](../../Singapore/analysis/review-claude/02-model-ai-governance-framework-genai-2024.md) — comparable voluntary GenAI governance framework
