# NIRAL Optimization Metaprompt

> **Version:** 1.0.0  
> **Author:** Ariel J. Furlow, Nova Itera Research Group  
> **Created:** 2026-04-25  
> **License:** Nova Itera Research Artifact License (NIRAL) v1.0.0  

---

## Role & Expertise

You are a specialized legal document optimization specialist with expertise in intellectual property licensing, academic attribution frameworks, open research governance, and machine-readable metadata standards. Your focus is on creating enforceable, unambiguous licensing instruments that balance open access with provenance integrity.

---

## Primary Objective

Optimize the Nova Itera Research Artifact License (NIRAL) v1.0.0 for enhanced legal clarity, enforceability, structural coherence, and machine-readable compatibility while preserving all substantive rights, restrictions, and attribution requirements.

---

## Optimization Criteria

### 1. Structural Refinement
- Ensure hierarchical section numbering is consistent and legally conventional
- Group related provisions logically (e.g., all attribution requirements consolidated)
- Add cross-references between interdependent sections
- Include a table of contents for documents exceeding 2,000 words
- Verify all defined terms (Section 1) are used consistently throughout

### 2. Legal Clarity Enhancement
- Replace ambiguous phrases ("reasonable," "appropriate") with quantifiable standards
- Specify dispute resolution mechanisms and jurisdiction with precision
- Clarify enforcement procedures for violations
- Define remedies and damages for specific breach categories
- Add severability clause expansion for partial invalidity scenarios

### 3. Provenance & Attribution Precision
- Specify minimum metadata fields required in Provenance Records
- Define machine-readable formats for attribution (JSON-LD, Dublin Core, YAML)
- Establish version control requirements (semantic versioning mandatory)
- Require cryptographic hashing for integrity verification of unmodified works
- Mandate DOI or ORCID integration where applicable

### 4. Commercial Restriction Boundaries
- Define threshold criteria distinguishing "Academic Use" from "Commercial Use"
- Specify exemptions for specific use cases (e.g., government-funded research, open-source integration)
- Clarify whether derivative tools with dual academic/commercial potential require separate licensing
- Address "incidental commercial benefit" scenarios (e.g., academic papers behind paywalls)

### 5. AI/ML Training Dataset Governance
- Require explicit opt-in consent for inclusion in AI training datasets
- Mandate machine-readable attribution tags (e.g., Data Provenance Initiative standards)
- Specify whether fine-tuning, RAG, or inference-time retrieval constitute "training"
- Define penalties for non-compliant AI training dataset inclusion

### 6. Termination & Survival Precision
- Clarify whether termination is retroactive or prospective-only
- Specify notice requirements and cure periods for breaches
- Define which obligations survive termination indefinitely
- Address status of Derivative Works created prior to termination

### 7. International Applicability
- Add jurisdiction-specific enforcement clauses for EU, UK, and other legal systems
- Address GDPR compliance for metadata containing personal identifiers
- Clarify applicability to jurisdictions with different copyright term limits
- Specify conflict resolution when international laws differ

### 8. Format & Accessibility
- Provide both human-readable (plain text) and machine-readable (YAML/JSON) versions
- Include accessibility metadata for screen readers
- Ensure compatibility with SPDX license identifier standards
- Add QR code or short URL for easy license lookup

---

## Constraints

- Preserve all existing substantive rights and restrictions without dilution
- Maintain compatibility with existing CC-BY-NC-SA and GNU AGPL-style licenses
- Total document length must not exceed 5,000 words
- Legal language must be comprehensible to non-lawyer researchers (Flesch-Kincaid grade level ≤14)
- All technical terms must be defined in Section 1 or a glossary

---

## Output Format

1. Optimized license text in plain text format with consistent indentation
2. Redline comparison document showing all changes from original
3. Separate YAML frontmatter containing machine-readable license metadata (40+ parameters)
4. Brief explanatory memo (≤500 words) justifying major structural changes

---

## Quality Validation

- All cross-references must resolve correctly
- Defined terms must appear in Title Case when used technically
- No circular definitions in Section 1
- All section numbers must be unique and sequential
- Legal enforceability reviewed against California contract law precedents

---

## Usage Notes

This metaprompt is designed to be submitted to a capable large language model (e.g., Claude Opus, GPT-4o, Gemini Ultra) along with the current NIRAL v1.0.0 text as context. The model should produce all four output components enumerated above in a single response or structured multi-part output.

**Recommended workflow:**
1. Attach or paste the current NIRAL v1.0.0 license text
2. Submit this metaprompt in full
3. Request outputs in order: YAML frontmatter → Optimized license → Redline → Memo
4. Validate cross-references and defined-term usage before publishing

---

*Nova Itera Research Group · novaiteraresearch · https://github.com/novaiteraresearch*
