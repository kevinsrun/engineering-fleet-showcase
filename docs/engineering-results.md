# Engineering results and evidence scope

The latest completed full verification inspected for this publication is bound to private source **`96545043d0e55127c6e0efcfd03ccfbd55b44110`**. Its result identifies a clean checkout at verification time. Later uncommitted development was present during publication review and is outside this checkpoint. This source is a local engineering checkpoint, not a claim that GitHub's private default branch contains it.

Public values are collected in [engineering-summary.json](../evidence/engineering-summary.json). The summaries below were newly authored from retained private records. No raw private logs or implementation files were transferred.

## Evidence classifications

| Label | Meaning | Does not establish |
|---|---|---|
| **Implemented** | The mechanism exists in the inspected source. | Successful tests or present provider eligibility. |
| **Engineering Verified** | Defined checks passed at an identified source version. Fixtures are labeled where relevant. | Authenticated live acceptance of every provider or production readiness. |
| **Operationally Verified** | Identified authenticated live execution occurred within a bounded recorded scope. | Broader workloads, later versions, or indefinite readiness. |
| **Planned** | An architectural objective without the required demonstration. | Implemented or accepted simultaneous operation. |

Independent verification here means acceptance checks and retained evidence separate from the coding worker's completion claim. It does not mean a third-party human certified the system.

## EV-01 · Latest completed full verification

| Field | Retained result |
|---|---|
| Source | `96545043d0e55127c6e0efcfd03ccfbd55b44110` |
| Verification interval | November 1, 2026, 20:07:40–20:11:33 UTC |
| Required checks | Lint, typecheck, full test suite, build: all passed |
| Test cases | **2,533 total: 2,527 passed, 6 skipped, 0 failed** |
| Cancelled / todo | 0 / 0 |
| Focused scope | Eight relevant files: **208 passed, 1 skipped, 0 failed**, 209 total |
| Process outcome | Exit 0, termination confirmed, no timeout or truncation |
| Model inference | No new model requests in the verification campaign |

The focused tests overlap the full suite and must not be added to it. The focused readiness skip occurred in an isolated home without the required authentication file. The six full-suite skips remain part of the reported result; this is not an all-environments acceptance.

The source includes tested task lifecycle, routing constraints, retained-artifact and evidence handling, verification workflows, and dashboard projections. This campaign also verified delivery-integrity regressions with deterministic and local transport fixtures. Those fixtures establish engineering behavior; they do not establish a new authenticated upstream model result. Positive live acceptance of the repaired runtime remains outstanding.

## EV-02 · Historical recovery checkpoint

| Field | Retained result |
|---|---|
| Source | `5c35a244ece4a07fd87253c46186b788887fff1b` |
| Summary recorded | October 31, 2026, 01:44:38 UTC |
| Required checks | Lint, typecheck, full tests, build: passed |
| Test cases | **2,450 total: 2,444 passed, 6 skipped, 0 failed** |
| Focused scope | **53 passed, 0 failed** |
| Preservation scope | **1,291 file comparisons matched** |

These are the earlier campaign figures cited in the project brief. They are historical measurements at their own source version. Preservation comparisons are not tests, unique file counts, or accepted engineering tasks. The raw preservation receipt explicitly excludes transient shared-memory reader-lock metadata; it does not establish byte identity of every file on the machine.

## EV-03 · Historical paired live coding experiment

The retained benchmark was observed on October 18, 2026. Its Fleet path used source `9bf8f163873f953a0e1918d7656922f8b311577c`; the benchmark records were also inspected in the EV-01 source tree.

Five paired bounded cases used matched baselines and independent predetermined acceptance checks. The direct path used a native coding client with a thin deterministic application, verification, and delivery harness. Fleet added its orchestration workflow. Both paths were tool-free bounded generation, not unrestricted interactive coding sessions.

| Case | Direct cycle time | Fleet cycle time | Result on each path |
|---|---:|---:|---|
| Backend idempotency | 24.87 s | 24.62 s | Verified draft delivered |
| HTTP filtering and pagination | 23.61 s | 26.94 s | Verified draft delivered |
| Browser/API error handling | 28.50 s | 41.51 s | Verified draft delivered |
| Test command and CI repair | 8.22 s | 11.92 s | Verified draft delivered |
| Controlled interruption and fresh-task recovery | 22.95 s | 32.52 s | Verified draft delivered |
| **Sum of task cycle times** | **108.15 s** | **137.51 s** | **5/5 on each path** |

Fleet's summed latency was **27.1% higher** in this sample, computed from the unrounded public rows. The sum is not simultaneous batch wall time: some tasks overlapped. There is no established throughput advantage. The median task cycle times were 23.61 seconds direct and 26.94 seconds Fleet.

Each path recorded six native attempts, including one controlled interrupted attempt, and zero human prompt relays. Recovery required an explicit fresh-task decision on each path. Unknown interrupted-call usage prevents complete consumption accounting. The small nonrandomized sample, host load, output differences, and scope of the direct harness limit generalization. No dollar-saving, productivity-multiplier, or current multi-provider claim follows from this experiment.

These historical observations establish a bounded operational demonstration at that version. They do not commission the latest repaired runtime, establish independently attributable billing, or justify attributing hackathon awards to Fleet.

## What a public reader can verify

The sanitized JSON contains aggregate counts, version bindings, original receipt hashes, and the ten benchmark timing rows. Readers can recompute the timing sums and latency difference and inspect consistency between the documentation and summary. Private source and raw receipts are withheld, so the backend's test outcomes and live execution remain **maintainer attestations based on privately retained evidence**. A hash is an artifact identifier, not independent public proof of its contents.

| Summary | Retained artifact SHA-256 |
|---|---|
| EV-01 full verification result | `46042eb2836acfa12f2a2a1da78204a87ba15229e36db5416103584246fafe79` |
| EV-02 historical summary | `db50e382a4819ae59965aa3c790ff2d57a3e1e2e532d4eb5cc73b96e1b18674b` |
| EV-03 benchmark | `6e224b35939edc5d36932d1760db263177c82eb913b90233b97af08fab39c111` |

The machine-readable JSON is authoritative for the receipt identifiers; publication validation checks this table against it. No private repository link, task payload, provider account, ledger, or execution log is required to read the public showcase.
