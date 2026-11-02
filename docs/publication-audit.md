# Publication security and privacy audit

**Publication review: November 1, 2026.** Scope: the exact public files listed in [publication-manifest.json](../evidence/publication-manifest.json). This is a maintainer publication audit, not a third-party security certification.

## Publication allowlist

| Allowed material | Files | Review treatment |
|---|---|---|
| Original showcase text | README, rights notice, and the documentation pages | Newly authored; inspected for unsupported claims and confidential detail. |
| Conceptual architecture | `assets/architecture.svg`, `assets/architecture.png` | Newly drawn; planned corps explicitly labeled; no implementation or infrastructure topology. |
| Actual interface with synthetic data | `assets/mission-control.png`, `assets/demo.gif` | Captured from isolated fixtures; visible content and every animation frame reviewed. |
| Sanitized quantitative summary | `evidence/engineering-summary.json` | Explicit field selection and fresh serialization; no raw receipt or log copied. |
| Fictional execution narrative | `examples/synthetic-execution.json` | Newly authored and prominently labeled; no private execution data. |
| Publication metadata | Manifest and `.gitignore` | Paths, sizes, content hashes, and minimal repository hygiene only. |

The exact manifest is the publication allowlist. Its own hash is excluded from its file-hash list to avoid recursion; Git binds the manifest itself. Future changes require renewed review.

## Excluded confidential material

No backend source, source archive, compiled application bundle, private commit object, environment file, credential, token, private key, provider configuration, internal prompt, private task payload, private ledger, raw execution log, unpublished third-party material, or sensitive infrastructure detail is approved for publication.

Source material was confidential by default. Uncertain artifacts were excluded. Raw private evidence stays outside the public repository; published hashes identify selected retained verification records without exposing their contents.

## Content and evidence review

The publication check scans allowed text for recognizable secrets, personal filesystem paths, credential-bearing URLs, and prohibited file types. JSON is parsed, local documentation links are resolved, metrics and receipt identifiers are checked against the sanitized summary, and asset formats and metadata are inspected. All image frames receive visual review. Automated pattern checks supplement that review; they cannot establish universal absence of secrets.

Claims distinguish implemented mechanisms, defined engineering verification, bounded historical authenticated demonstrations, and planned capabilities. Focused tests are not added to full-suite totals. Synthetic dashboard counts are not real metrics. Historical latency overhead and present operational limitations are included. Biography and award claims are identified as the author's account.

## Independent history and source preservation

The showcase is initialized in an empty directory with its own fresh Git history. Private source commits are not imported as Git objects, parents, submodules, or alternate object stores. Only the allowlisted showcase files are staged. There are no workflows, private-source checkouts, backend services, or live credentials in the public repository.

The publication procedure reads the private source and evidence without modifying them. Before and after snapshots compare the private GitHub refs and visibility, plus the inspected local source HEADs, status, and tracked-file bytes. Existing uncommitted engineering work is preserved and excluded from showcase acceptance. This publication does not change the private repository's visibility or history.

## Publication verification procedure

After the audited files are pushed, anonymous requests must verify the public repository, README, and visual assets. An anonymous clone must match the reviewed manifest and contain only the independent showcase history. An authenticated read must reconfirm that the original source repository remains private; an anonymous read of that private repository must remain inaccessible.

The final publication outcome is returned with the repository URL. Detailed private source comparisons and anonymous HTTP receipts are retained outside the showcase, rather than publishing internal paths or unreviewed logs.

## Rights

Original materials carry an [all-rights-reserved notice](../LICENSE). Provider and event names remain their owners' marks. This is a portfolio and technical showcase, with no open-source license for Engineering Fleet.
