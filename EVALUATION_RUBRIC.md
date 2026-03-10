# Evaluation Rubric

Detailed scoring definitions for all four evaluation criteria used in this study.

---

## Scoring Scale

| Score | Label | Meaning |
|---|---|---|
| 9-10 | Excellent | Exceeds expectations; near flawless |
| 7-8 | Good | Solid performance with minor gaps |
| 5-6 | Acceptable | Adequate but notable weaknesses |
| 3-4 | Poor | Significant problems; partially usable |
| 1-2 | Failing | Unusable or actively misleading |

---

## Criterion 1: Clarity

Is the response easy to read, well-structured, and unambiguous?

| Score | Description |
|---|---|
| 9-10 | Exceptionally clear. Perfect structure, precise language, no ambiguity. |
| 7-8 | Clear and readable. Minor phrasing issues that don't affect comprehension. |
| 5-6 | Mostly clear but some sections are confusing or poorly organized. |
| 3-4 | Hard to follow. Lacks structure; reader must re-read to understand. |
| 1-2 | Incomprehensible or contradictory phrasing throughout. |

Ask yourself: Could a target-audience reader understand this on the first read?

---

## Criterion 2: Factual Alignment

Does the content align with verifiable, up-to-date facts?

| Score | Description |
|---|---|
| 9-10 | All claims are accurate and verifiable. No hallucinations detected. |
| 7-8 | Mostly accurate. One or two minor inaccuracies that don't mislead. |
| 5-6 | Several inaccuracies or unverifiable claims that affect reliability. |
| 3-4 | Multiple factual errors or clear hallucinations present. |
| 1-2 | Largely fabricated, dangerously wrong, or completely unverifiable. |

Ask yourself: Would a domain expert trust this response without fact-checking?

---

## Criterion 3: Completeness

Does the response fully address all parts of the prompt?

| Score | Description |
|---|---|
| 9-10 | Fully addresses the prompt. No significant aspect left out. |
| 7-8 | Addresses the main ask. Minor sub-points missing. |
| 5-6 | Addresses roughly half the prompt. Key parts are missing. |
| 3-4 | Only touches on the topic. Mostly incomplete. |
| 1-2 | Fails to address the prompt in any meaningful way. |

Ask yourself: If someone acted only on this response, would they have what they need?

---

## Criterion 4: Logical Consistency

Is the reasoning internally coherent, without contradictions?

| Score | Description |
|---|---|
| 9-10 | Reasoning is airtight. Every conclusion follows from its premises. |
| 7-8 | Mostly logical. One weak inference or minor leap. |
| 5-6 | Some conclusions don't follow from evidence. Reasoning is shaky in places. |
| 3-4 | Contradictions present. Conclusions conflict with earlier statements. |
| 1-2 | No discernible logical structure. Self-contradictory throughout. |

Ask yourself: Could you construct a valid argument from this response?

---

## Issue Flag Definitions

| Flag | When to Apply |
|---|---|
| Hallucination | Model states facts, citations, names, or data that are fabricated |
| Vague Reasoning | Conclusions stated without supporting logic or evidence |
| Ambiguous Output | Response could be interpreted in multiple conflicting ways |
| Outdated Info | Uses deprecated APIs, old statistics, superseded guidelines |
| Overconfidence | Presents uncertain or contested claims as definitive fact |
| Incomplete Answer | Misses one or more explicit parts of the prompt |
| Off-Topic | Drifts into tangential content unrelated to the core ask |
| Repetition | Restates the same point 2+ times without adding value |

---

## Calibration Notes

- Score what the model produced, not what it could have produced.
- Compare against the specific prompt, not general knowledge.
- When in doubt between two scores, use your notes field to explain and pick the lower score.
- Re-read previous evaluations periodically to ensure scoring consistency.