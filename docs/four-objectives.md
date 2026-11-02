# Four objectives, one accepted outcome

**Maximize verified engineering output per dollar, per token, per unit of time, and per unit of human attention.**

These are competing objectives, not four reported performance wins. A useful comparison must hold task difficulty and acceptance requirements sufficiently constant and include unsuccessful attempts.

## I. Tokenomics

The target is total cost per independently verified result. Routing work to an appropriate model, limiting redundant context, and reusing verified artifacts can reduce waste. Failures, retries, escalations, and verification consume resources too. A stronger model that succeeds once may be cheaper overall than repeated cheap failures.

Fleet implements economic-routing and invocation-accounting mechanisms. Logical budgets, provider-reported tokens, and actual attributable charges are different quantities. Unknown consumption must remain unknown. The reviewed evidence does not establish general dollar or token savings.

## II. Efficiency

The target is productive work relative to human attention and compute. Retained context, explicit tasks, repeatable handoffs, and inspectable evidence aim to reduce coordination and duplicated effort. The operator should spend more attention on priorities and acceptance decisions.

Historical bounded cases required no manual prompt relays on either Fleet or the direct comparison path. That observation does not measure total human time saved. A future evaluation should record setup, intervention, review, recovery, and reconciliation time for both paths.

## III. Speed

The target is verified throughput and completion latency. Concurrent independent work can reduce sequential waiting, but contention, dependency management, handoff costs, and verification can erase the gain.

The retained five-case paired experiment recorded 137.51 seconds of summed task cycle time for Fleet and 108.15 seconds for direct execution. Fleet was slower in that sample. Simultaneous batch throughput was not established. A future test should measure whole-batch wall time, worker concurrency, dependencies, and host conditions.

## IV. Quality

The target is correctness and reproducibility under independent acceptance criteria. Deterministic checks, provenance, source-version bindings, controlled execution, and review requirements make results assessable. Synthetic fixtures and live operations must be labeled separately.

The latest retained suite reports 2,527 passing tests and six skips. Those counts describe a defined engineering scope, not a defect-free product or acceptance of every provider. Quality comparisons should include rejected submissions and later regressions, with the same acceptance bar on each path.

## How to evaluate the combined objective

Compare accepted outcomes, total consumed resources, elapsed time, and operator attention on matched tasks. Report the dimensions separately rather than inventing one score that hides tradeoffs. Keep the denominator honest: attempted tasks and self-reported completions are not independently accepted results.

[Retained measurements and methods](engineering-results.md) · [Current limitations](limitations.md)
