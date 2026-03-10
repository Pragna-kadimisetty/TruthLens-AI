# Changelog

All notable changes and methodology refinements are documented here.
Format: [Date] - Change description and rationale.

---

## [Unreleased]

- Planned: Inter-rater reliability test with second evaluator
- Planned: Add "Tone Appropriateness" as a fifth criterion
- Planned: Python script for statistical analysis of exported CSV

---

## [v1.0.0] - 2025-11-14

### Added
- Initial evaluation rubric with 4 criteria: Clarity, Factual Alignment, Completeness, Logical Consistency
- 8 issue flag types covering the most common LLM failure modes
- Browser-based evaluation app with persistent localStorage
- CSV export functionality
- Insights dashboard with auto-generated observations

### Methodology Decisions
- Chose 1-10 scale over 1-5 for finer granularity in mid-range responses
- Separated "Factual Alignment" from "Completeness" after noticing models could be complete but inaccurate
- Added "Overconfidence" flag after observing models state contested medical/legal info as fact

---

## Evaluation Criteria Evolution Log

### Clarity
- v1.0: Defined as readability and structure
- Note: Consider splitting into "Structure" and "Language Precision" in v2.0

### Factual Alignment
- v1.0: Any verifiable claim cross-checked against known sources
- Challenge: Some domains (forecasting, opinions) are inherently unverifiable — document these in notes

### Completeness
- v1.0: Based on explicit prompt requirements
- Note: Multi-part prompts should be scored by proportion of sub-tasks addressed

### Logical Consistency
- v1.0: Internal coherence only (not external validity)
- Distinction: A logically consistent response can still be factually wrong — these are separate criteria

---

## Observations Log

### Week 1
- Models tend to score high on Clarity but lower on Factual Alignment for specialized domains
- Hallucinations more frequent in citation-heavy or statistical prompts
- "Vague Reasoning" flag often co-occurs with low Logic scores (as expected)

### Week 2
- Add observations as you continue your study...