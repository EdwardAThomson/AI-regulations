# United States — AI Governance

The US has no comprehensive federal AI legislation. Its AI governance landscape is a patchwork: executive orders (subject to change on administration transitions), agency enforcement under existing authority, voluntary frameworks (NIST AI Risk Management Framework), and rapidly proliferating state-level legislation. The most consequential recent transition: Biden's EO 14110 (safety-first, mandatory reporting for frontier AI developers) was revoked on the first day of the Trump administration (January 2025) and replaced by a competitiveness and deregulation framing, with an AI Action Plan published July 2025.

Over 700 AI bills were introduced across state legislatures in 2024 alone, with Colorado's AI Act (SB 24-205, effective February 2026) being the landmark state-level statutory framework.

This directory contains the source documents and reviews that together map that position.

## Note

- This material is for research and comparison only, not legal advice.
- Reviews in this directory were produced or assisted by AI and may contain mistakes or outdated interpretations; important points should be checked against the primary sources.

## Contents

```
USA/
├── README.md                          # This file
├── source/                            # Source documents
│   ├── inventory.md                   # Tracked list of documents to collect
│   └── [source documents]
└── analysis/                          # Reviews
    └── review-claude/                 # Claude section-level reviews (5 docs)
```

## Sources

See [`source/inventory.md`](source/inventory.md) for the full inventory of documents targeted, with collection status.

Currently collected sources (7 documents):

### Enduring frameworks
- **NIST AI Risk Management Framework (AI RMF 1.0)** (January 2023) — foundational voluntary framework; bipartisan statutory mandate; four functions (Govern, Map, Measure, Manage)
- **NIST AI 600-1: Generative AI Profile** (July 2024) — GenAI extension; 12 identified risks

### Biden administration (historical)
- **EO 14110 — Safe, Secure, and Trustworthy AI** (October 2023) — **REVOKED** 23 January 2025; historically significant as the most comprehensive federal AI action
- **Blueprint for an AI Bill of Rights** (October 2022) — aspirational; 5 principles; non-binding; effectively superseded

### Trump administration (current)
- **EO 14179 — Removing Barriers to American Leadership in AI** (January 2025) — revoked EO 14110; directed AI Action Plan
- **America's AI Action Plan** (July 2025) — 3 pillars (innovation, infrastructure, international); competitiveness framing
- **OMB Memorandum M-25-21** (April 2025) — binding on federal agencies; replaces M-24-10; Chief AI Officer, high-impact AI risk management

## Analysis

### Section-level reviews — [`analysis/review-claude/`](analysis/review-claude/)

Five reviews covering all 7 collected source documents (EO 14110, EO 14179, and the AI Action Plan are reviewed as a combined narrative).

| # | Date | Review |
|---|------|--------|
| 01 | Jan 2023 | [NIST AI Risk Management Framework (AI RMF 1.0)](analysis/review-claude/01-nist-ai-rmf.md) |
| 03 | Oct 2022 | [Blueprint for an AI Bill of Rights](analysis/review-claude/03-blueprint-ai-bill-of-rights.md) |
| 04 | Jul 2024 | [NIST AI 600-1: Generative AI Profile](analysis/review-claude/04-nist-genai-profile.md) |
| 02 | Oct 2023 — Jul 2025 | [Executive Orders and AI Action Plan](analysis/review-claude/02-executive-orders-and-action-plan.md) |
| 05 | Apr 2025 | [OMB Memorandum M-25-21](analysis/review-claude/05-omb-m-25-21.md) |

### State-level legislation — [`analysis/state-legislation.md`](analysis/state-legislation.md)

The federal reviews above cover only the federal layer. The binding obligations on private-sector AI in the US today are mostly state, not federal. [State-level legislation](analysis/state-legislation.md) records the operationally-significant state regimes: Colorado AI Act (SB 24-205, the only US horizontal AI statute), California CPRA + ADMT + AB 2013 + SB 942 + the vetoed SB 1047, NYC Local Law 144 (AEDT), Illinois BIPA and Texas CUBI (biometric), Utah AI Policy Act, and the state privacy laws that function as AI overlays.

## Key findings across the US landscape

1. **No comprehensive federal AI legislation.** The US relies on executive orders (volatile), voluntary frameworks (NIST), agency enforcement under existing authority (FTC, FDA, EEOC), and state-level legislation (Colorado, California, Utah). This is the lightest-touch federal approach among major jurisdictions.

2. **Executive orders are structurally unsuitable for durable AI governance.** EO 14110 — the most comprehensive federal AI action — was entirely revoked within 15 months. Mandatory reporting, red-teaming, and content labelling requirements disappeared overnight. Statutory instruments (NIST AI RMF, National AI Initiative Act) are more durable.

3. **NIST AI RMF is the enduring framework.** Mandated by bipartisan legislation, maintained by NIST's institutional infrastructure, and widely adopted internationally. Its four-function structure (Govern, Map, Measure, Manage) survives administration changes. However, the July 2025 AI Action Plan directs politically motivated content revisions — a threat to its technical independence.

4. **Biden safety-first → Trump competitiveness-first.** The philosophical reorientation is the most consequential change. Under Biden, innovation yielded to safety concerns (mandatory reporting). Under Trump, safety concerns yield to innovation (revoke mandates, remove regulations). Both acknowledge both values; the hierarchy matters when they conflict.

5. **State-level legislation creates a two-track system.** While federal policy de-regulates, states like Colorado are introducing binding AI obligations. The AI Action Plan uses federal funding conditionality as leverage against state-level regulation — a novel preemption-by-funding approach.

6. **OMB M-25-21 preserves Biden-era safeguards within government.** The high-impact AI requirements (discontinue non-compliant AI, risk management, Chief AI Officer) survive the administration transition in substance, though reframed as "innovation enablers."

7. **National security framing preserves frontier evaluation.** The AI Action Plan directs the US government to be "at the Forefront of Evaluating National Security Risks in Frontier Models" — preserving AISI-type evaluation but narrowed to national security.

## Position in comparative landscape

The US represents the lightest-touch federal approach among major jurisdictions, with additional volatility from administration transitions:

- **NIST AI RMF** is referenced internationally (UK consultation response, CMA report, Singapore's AI Verify); it is the closest US equivalent to the EU HLEG Ethics Guidelines
- **US AISI** (announced November 2023, housed at NIST) partnered with UK AISI — status uncertain under current administration
- **State-level legislation** represents a counter-current: while federal policy de-regulates, states are introducing binding obligations
- **International positioning:** US reportedly did not sign the main declaration at the Paris AI Action Summit (February 2025); AI Action Plan frames international engagement through geopolitical competition with China rather than multilateral governance
- **Contrast with EU**: the EU AI Act is legislation surviving political turnover; US executive orders do not
- **Contrast with UK**: the UK's non-statutory approach is principled and consistent across administrations; the US approach oscillates between safety-first and competitiveness-first depending on who holds the White House
- **Contrast with Singapore**: Singapore's voluntary approach is stable and evolutionarily layered; the US voluntary framework (NIST) is stable but the political overlay is volatile
