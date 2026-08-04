# 📖 Lesson Plan — AB-Testing-And-Business-Metrics

> **Chain Q — Data Analytics** | Run an experiment that actually proves something: hypotheses, sample size, statistical significance, and the traps that invalidate results.

## What This Project Is

Run an experiment end to end with the discipline that makes the result trustworthy: hypothesis first, sample size computed up front, and the result respected.

## Learning Objectives

By the end I can:

1. State a hypothesis and define the primary metric **before** starting.
2. Compute the required **sample size** with a power analysis.
3. Interpret p-values and confidence intervals correctly.
4. Explain why **peeking** inflates false positives.
5. Choose primary, secondary, and guardrail metrics.
6. Distinguish statistical from practical significance.

## Software You Will Use

- Python: scipy.stats, statsmodels.
- A power-analysis calculator.
- pandas for analysis.

## Build Order

1. Write the hypothesis and choose the primary metric.
2. Run a power analysis to fix the sample size and duration.
3. Simulate or collect the data.
4. Analyse once, at the planned stopping point.
5. Demonstrate the peeking problem by analysing repeatedly on simulated null data.
6. Write up the result, including if it is inconclusive.

## Common Mistakes to Avoid

- Choosing the metric after seeing the data.
- Stopping the moment the result looks favourable.
- Running many variants and reporting only the winner.
- Ignoring guardrail metrics that got worse.
- Calling a statistically significant 0.1% lift a business win.

## Check Your Understanding

The quiz covers power analysis, p-value interpretation, peeking, and practical vs statistical significance.

## Why This Matters (Industry Application)

Product analytics and growth roles run on experimentation, and being the person who can say "that result
isn't significant, and here's why" is genuinely valuable. Every major tech company makes decisions this way,
and misreading experiments leads to expensive wrong turns.

## Reflection Questions

- What would you do if the result is significant but the effect is too small to matter?
- Which guardrail metric would you refuse to trade away for a conversion lift?
