# Evaluation Rubric

Each prompt is evaluated against the same 10 test cases.

## Scoring Criteria

| Criterion | Score |
|---|---:|
| Correct information extraction | 0–2 |
| Correct handling of missing information | 0–2 |
| Correct JSON structure | 0–2 |
| No invented information | 0–2 |
| Correct separation of required and preferred information | 0–2 |

Maximum score per test case: **10 points**

Maximum overall score: **100 points**

## Scoring Guide

### 2 points
The output is completely correct for the criterion.

### 1 point
The output is partially correct but contains a minor issue.

### 0 points
The output is incorrect or fails the criterion.

## Failure Categories

Incorrect outputs are classified using one or more of these categories:

- Hallucination
- Missing information
- Incorrect classification
- Schema/formatting error
- Required/preferred confusion
- Incorrect interpretation

## Evaluation Procedure

1. Run the baseline prompt (V1) on all 10 test cases.
2. Run the improved prompt (V2) on the same 10 test cases.
3. Score both versions using this rubric.
4. Compare the total scores.
5. Analyze recurring failure patterns.
6. Document the findings and possible improvements.
