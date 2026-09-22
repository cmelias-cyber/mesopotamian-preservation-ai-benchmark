# Testing General-Purpose LLMs on Under-Documented Cultural Heritage through Erasure of Distinct Sub-Traditions and Misattribution of Contested Facts

### *A Case Study Using the Mesopotamian Aroma Preservation Initiative's Archive, a Heritage Preservation Non-Profit*

> **One-line Summary:** Benchmarking four general-purpose LLMs against a retrieval-grounded assistant built on MAPI's verified archive across two core failure modes—representational erasure of distinct sub-traditions and false confidence on under-documented facts—to produce reusable evaluation guidance for cultural and public-interest organizations.

---

## Overview

This repository contains the research assets, benchmark schemas, evaluation rubrics, and security specifications for the 12-week study funded through the BlueDot Rapid Grant initiative.

The project evaluates how general-purpose large language models (LLMs) handle under-documented cultural heritage across seven distinct regional, minority, and diasporic sub-traditions (Assyrian, Chaldean, Mandaean, Kurdish, Jewish, Sunni Muslim, and regional/diasporic communities across Türkiye and Iraq).

## Core Deliverables

- **150-Item Evaluation Benchmark:** Prompts designed to test representational erasure, flattening, source misattribution, and unjustified certainty.
- **Scoring Rubric & Taxonomy:** Structured evaluation criteria for blinded double-coding and participant review.
- **RAG Security & Defense-in-Depth Architecture:** Specifications for vector retrieval boundaries, custom API access controls, rate limits, and prompt-injection defenses.
- **Disaggregated Comparative Analysis:** Performance evaluation across five experimental configurations (4 base LLMs + 1 RAG assistant).

## Repository Structure (Work in Progress)

- `prompt-schema-pilot.json` — Pilot dataset (10–20 prompts) testing baseline failure modes.
- `scoring-rubric-draft.md` — Draft failure taxonomy and qualitative rater guidelines.
- `rag-architecture-spec.md` — Security boundaries and defense-in-depth integration notes.

## License

[MIT License](LICENSE) — Maintained by the Mesopotamian Aroma Preservation Initiative (MAPI).
  
