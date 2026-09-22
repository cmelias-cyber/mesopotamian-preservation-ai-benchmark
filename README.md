# Testing General-Purpose LLMs on Under-Documented Cultural Heritage through Erasure of Distinct Sub-Traditions and Misattribution of Contested Facts

### *A Case Study Using the Mesopotamian Aroma Preservation Initiative's Archive, a Heritage Preservation Non-Profit*

> **One-line Summary:** Benchmarking four general-purpose LLMs against a retrieval-grounded assistant built on MAPI's verified archive across two core failure modes—representational erasure of distinct sub-traditions and false confidence on under-documented facts—to produce reusable evaluation guidance for cultural and public-interest organizations.

---

## Overview

The Mesopotamian Aroma Preservation Initiative’s (MAPI) website will serve as the foundation for a controlled research environment. Grant funding will support the integration and secure deployment of a limited-access, retrieval-augmented generation (RAG) prototype grounded in MAPI’s verified archive, together with hosting, backups, access controls, evaluation infrastructure, and participant-testing capabilities. The study will create a structured benchmark and compare responses from four widely used general-purpose LLMs with responses from the MAPI retrieval-grounded assistant.

The benchmark focuses on two recurring epistemic failure modes. First, it tests whether systems erase or flatten distinct Assyrian, Chaldean, Mandaean, Kurdish, Jewish, Sunni Muslim, and other regional or diasporic traditions into a generic “Mesopotamian” narrative. Second, it tests whether systems misattribute sources or present contested and under-documented claims with false confidence. The assistant is the experimental comparison system, not merely a product deliverable. The intended outputs are comparative evidence, a reusable benchmark and evaluation toolkit, and practical guidance for other cultural organizations.

## Core Deliverables

- **150-Item Evaluation Benchmark:** Prompts designed to test representational erasure, flattening, source misattribution, and unjustified certainty.
- **Scoring Rubric & Taxonomy:** Structured evaluation criteria for blinded double-coding and participant review.
- **RAG Security & Defense-in-Depth Architecture:** Specifications for vector retrieval boundaries, custom API access controls, rate limits, and prompt-injection defenses.
- **Disaggregated Comparative Analysis:** Performance evaluation across five experimental configurations (4 base LLMs + 1 RAG assistant).

## Repository Structure (Work in Progress)

- `prompt-schema-and-examples.md` — Prompt schema specs and pilot prompt examples testing baseline failure modes.
- `scoring-rubric-draft.md` — Draft failure taxonomy and qualitative rater guidelines.
- `project-scope-and-budget.md` — Itemized $20k budget breakdown and execution scope.
- `upcoming-implementation-plan.md` — Post-award execution roadmap and planned directory structure.

## License

[MIT License](LICENSE) — Maintained by the Mesopotamian Aroma Preservation Initiative (MAPI).
  
