# First Benchmark – Structured Output Reliability

## Objective
Test how reliably the model returns valid JSON.

## Method
- 20 test cases
- same prompt
- measured formatting + hallucination

## Results
Accuracy: 65%
Formatting failures: 25%
Hallucinations: 10%

## Observations
- breaks on long inputs
- sometimes adds extra commentary
- needs stricter constraints

## Conclusion
Not production safe without validation layer.
