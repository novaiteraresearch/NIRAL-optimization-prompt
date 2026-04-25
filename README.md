# NIRAL Optimization Metaprompt

> **Repository:** `novaiteraresearch/NIRAL-optimization-prompt`  
> **Version:** 1.0.0  
> **Author:** Ariel J. Furlow — Nova Itera Research Group  
> **Created:** 2026-04-25  
> **Status:** Active  

---

## Overview

This repository contains the official **metaprompt** for optimizing the **Nova Itera Research Artifact License (NIRAL) v1.0.0** — a bespoke open-research licensing instrument developed by Nova Itera Research Group.

The metaprompt is designed to be submitted to a capable large language model alongside the current NIRAL v1.0.0 license text. It directs the model to produce a fully optimized, legally refined, and machine-readable version of the license across four structured output components.

---

## Repository Contents

| File | Description |
|------|-------------|
| `NIRAL-optimization-metaprompt.md` | Full metaprompt with role, objectives, criteria, constraints, and output format |
| `README.md` | This documentation file |

---

## What the Metaprompt Does

The prompt instructs a model to optimize NIRAL across **8 domains**:

1. **Structural Refinement** — Hierarchical numbering, logical grouping, cross-references, TOC
2. **Legal Clarity Enhancement** — Quantifiable standards, jurisdiction, enforcement, remedies
3. **Provenance & Attribution Precision** — JSON-LD/Dublin Core/YAML, DOI/ORCID, cryptographic hashing
4. **Commercial Restriction Boundaries** — Academic vs. Commercial thresholds, dual-use, incidental benefit
5. **AI/ML Training Dataset Governance** — Opt-in consent, Data Provenance Initiative tags, fine-tuning/RAG scope
6. **Termination & Survival Precision** — Retroactive vs. prospective, notice periods, surviving obligations
7. **International Applicability** — EU/UK enforcement, GDPR, jurisdictional conflict resolution
8. **Format & Accessibility** — SPDX compatibility, screen-reader metadata, QR/short URL

---

## Output Components

The metaprompt produces four structured outputs:

1. **Optimized license text** (plain text, consistent indentation)
2. **Redline comparison** (all changes from original NIRAL v1.0.0)
3. **YAML frontmatter** (machine-readable license metadata, 40+ parameters)
4. **Explanatory memo** (≤500 words justifying structural changes)

---

## Usage

### Prerequisites
- Access to a capable LLM (Claude Opus 4+, GPT-4o, Gemini Ultra, or equivalent)
- Current NIRAL v1.0.0 license text

### Recommended Workflow

```
1. Obtain the current NIRAL v1.0.0 license text
2. Open your preferred LLM interface
3. Paste the NIRAL v1.0.0 text followed by the full contents of NIRAL-optimization-metaprompt.md
4. Request outputs in sequence:
   YAML frontmatter → Optimized license → Redline → Memo
5. Validate all cross-references and defined-term Title Case usage
6. Review against California contract law precedents before publishing
```

---

## Constraints Summary

- Preserves all existing NIRAL rights and restrictions without dilution
- Compatible with CC-BY-NC-SA and GNU AGPL-style licenses
- Output must not exceed 5,000 words
- Flesch-Kincaid grade level ≤14 (comprehensible to non-lawyer researchers)
- All technical terms defined in Section 1 or a glossary

---

## About Nova Itera Research Group

Nova Itera Research Group is an independent research organization focused on AI biosecurity policy, provenance engineering, and open research governance. We develop licensing frameworks, attribution standards, and AI safety policy instruments.

- **GitHub:** [novaiteraresearch](https://github.com/novaiteraresearch)
- **Founder:** Ariel J. Furlow

---

## License

This metaprompt itself is released under the **Nova Itera Research Artifact License (NIRAL) v1.0.0**.  
Non-commercial academic use permitted with full attribution.  
AI/ML training dataset inclusion requires explicit opt-in consent from Nova Itera Research Group.

---

*Nova Itera Research Group · 2026*
