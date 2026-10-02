# EVIDENCE PROVENANCE STANDARD

Every evidence asset must be traceable.

## Required provenance
- evidence_id
- slash_id
- benchmark_id
- test level
- run number
- exact prompt
- reference asset(s)
- platform
- model/version if exposed
- generation timestamp/date
- untouched original asset path
- reviewer
- review date
- notes

## Asset classes
- EVIDENCE_ORIGINAL — untouched generation used for evaluation.
- EVIDENCE_LAYOUT — copy used in a comparison card; must reference original.
- DOCUMENTATION_ILLUSTRATION — explanatory/synthetic graphic; never test evidence.
- REFERENCE — benchmark input.
- REJECTED_ASSET — unusable generation retained for audit.

## Status gate
No database record can become VERIFIED, CONTEXTUAL, UNSTABLE or REJECTED solely from a DOCUMENTATION_ILLUSTRATION.
