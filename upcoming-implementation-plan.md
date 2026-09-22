# Upcoming Implementation Plan & Target Repository Structure

This document outlines part of the planned repository structure and execution workflow for the 12-week grant period upon funding award. 

The proposal specs currently in the root directory will be maintained as baseline reference assets under `/docs/proposal/`, while live execution data and scripts will populate dedicated directories.

---

## Planned Directory Structure

```text
mesopotamian-preservation-ai-benchmark/
├── README.md                          <-- Live project overview & status updates
├── LICENSE                            <-- MIT License
├── docs/                              <-- Documentation & Protocol Specifications
│   ├── proposal/                      <-- Original pre-award specs (rubric, budget, schemas)
│   ├── corpus-governance.md           <-- Archive governance & source provenance protocols
│   └── participant-protocol.md        <-- Evaluation guidelines & anonymization standards
├── data/                              <-- Datasets & Prompts
│   ├── raw/                           <-- MAPI verified archive excerpts & embeddings config
│   ├── benchmark-150.json             <-- Full 150-item benchmark dataset
│   └── reference-answers/             <-- Archive-grounded ground truth notes
├── src/                               <-- Implementation Code & RAG Prototype
│   ├── rag_assistant/                 <-- Vector retrieval, API integration & security controls
│   ├── eval_pipeline/                 <-- Automated multi-model test runner (4 LLMs + RAG)
│   └── analysis/                      <-- Inter-rater reliability & statistical scripts
├── results/                           <-- Scored Outputs & Evaluation Data
│   ├── raw_outputs/                   <-- 2,250+ logged model runs across all systems
│   ├── scored/                        <-- Blinded & double-coded evaluation logs
│   └── disaggregated_reports/         <-- Performance breakdowns across sub-traditions
└── public_outputs/                    <-- Final Public Deliverables
    ├── report/                        <-- Final comparative research paper & findings
    └── evaluation-toolkit/            <-- Reusable evaluation framework for cultural orgs
