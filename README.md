# A Minimal Common Assurance Architecture for Stateful AI Systems

**A lightweight, implementation-neutral framing for connecting existing and future defensive mechanisms around stateful AI systems.**

It does **not replace existing security practice or define a new security standard**. Instead, it makes key assurance relationships explicit—including evidence and provenance, AI auditing, authorization and delegation, recovery validation, and human auditability.

The architecture is intentionally **incremental**: existing security remains the foundation, and individual assurance capabilities can be added where useful.

**Public Technical Note · Discussion Draft v0.1 · CC BY 4.0 · 5 pages**

**DOI:** [10.5281/zenodo.23061143](https://doi.org/10.5281/zenodo.23061143)
## Core Idea

The architecture connects several roles and relationships around an existing security foundation, including:

- Target AI / Agent
- Evidence Sources
- Evidence Provenance
- AI Auditors
- Evidence Paths
- Shared Dependencies
- Authorization and Delegation
- Recovery Validation
- Human Auditability

A central distinction is:

> Multiple auditors do not necessarily provide independent evidence.

Evidence independence should be assessed with attention to provenance and shared dependencies rather than inferred from the number of monitoring components alone.

The architecture also distinguishes:

> User Intent ≠ Granted Authority ≠ Task-Scoped Delegation ≠ Available AI Capability ≠ Executed Action

These distinctions are intended to support clearer auditing, recovery, delegated-authority analysis, and human reconstruction of externally recorded system history.

## Status

**Version:** v0.1  
**Document type:** Public Technical Note  
**Status:** Discussion Draft / Initial Public Release

This is a provisional architectural framing intended to be tested, criticized, modified, extended, simplified, or discarded where appropriate.

It is not presented as a complete architecture, security standard, or guarantee of protection.

## Documents

### English Master

The English version is the authoritative public version of the Technical Note.

- `A_Minimal_Common_Assurance_Architecture_v0.1.pdf`

### Japanese Meaning-Review Version

A Japanese counterpart is provided for semantic review and verification of the English Master.

It is intended to preserve claim strength, uncertainty, exceptions, and architectural distinctions rather than serve as an independently authoritative version.

- `A_Minimal_Common_Assurance_Architecture_v0.1_RC1_JA_meaning_review.docx`

## Relation to Existing Work

The individual security and assurance mechanisms referenced in the Technical Note are not assumed to be new.

Existing terminology is used where it adequately preserves the intended distinctions. Local terminology is introduced only where necessary.

Cited external work provides terminology and context; it does not define the structure of the proposed architecture.

## License

This work is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You may share and adapt the material, including for commercial purposes, provided that appropriate credit is given, a link to the license is provided, and changes are indicated.

https://creativecommons.org/licenses/by/4.0/

## Citation

Hiraku, T. (2026). *A Minimal Common Assurance Architecture for Stateful AI Systems* (Version 0.1). Zenodo.  
https://doi.org/10.5281/zenodo.23061143

**All versions:** https://doi.org/10.5281/zenodo.23061142

## Author

Tetsuya Hiraku


