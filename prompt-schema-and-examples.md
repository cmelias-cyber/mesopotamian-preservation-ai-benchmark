# Pilot Prompt Schema & Benchmark Metadata

This document outlines the metadata structure, failure modes, and target traditions for the Mesopotamian Preservation AI Benchmark.
  
## Benchmark Metadata
* **Version:** `0.1.0-pilot`
* **Target Total Prompts:** 150
* **Evaluations per Prompt:** 3 (producing 2,250+ outputs)
* **Represented Traditions:** Assyrian, Chaldean, Mandaean, Kurdish, Jewish, Sunni Muslim, Regional/Diasporic

---

## Schema Structure (JSON)

```json
{
  "benchmark_metadata": {
    "title": "Mesopotamian Preservation AI Benchmark (Pilot)",
    "version": "0.1.0-pilot",
    "total_target_prompts": 150,
    "pilot_prompt_count": 10,
    "evaluations_per_prompt": 3,
    "target_traditions": [
      "Assyrian",
      "Chaldean",
      "Mandaean",
      "Kurdish",
      "Jewish",
      "Sunni Muslim",
      "Regional/Diasporic"
    ]
  },
  "failure_taxonomy": {
    "erasure_and_flattening": [
      "tradition_identification",
      "cross_tradition_conflation",
      "minority_perspective_omission",
      "dominant_narrative_default",
      "representation_balance"
    ],
    "misattribution_and_false_confidence": [
      "claim_support",
      "source_attribution",
      "citation_entailment",
      "uncertainty_calibration",
      "responsible_abstention"
    ]
  },
  "metrics_tracked": [
    "cross_tradition_conflation_rate",
    "minority_perspective_omission_rate",
    "unsupported_claim_rate",
    "incorrect_source_attribution_rate",
    "citation_entailment_rate",
    "uncertainty_or_abstention_rate",
    "inter_rater_reliability"
  ]
}
```
