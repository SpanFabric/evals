# Fresh BREAKER handoff — missing-parent fixture

Repository: SpanFabric/evals
Base: eb03a96418af56eb8d7d7d85bee5b577262d32c7
Material: d049ea0a32bea04835311f03594bd1b41c86fe69
Digest: da67a1981f6493cf9f403648ea8e53e504b8b1112b42cffc181fa0466fbc6488
Changed material: tests/verification/test_lifecycle_history.py
Builder ceiling: INDEPENDENT_REVIEW_PENDING

Reconstruct independently; Builder claims and CI are untrusted until checked.
Attack loose/GC/repack storage, GC commit-graph exit0 with incomplete traversal, paired valid/corrupt tips, exact absent 40-hex nonzero grandparent, successful base guard, strict direct+immutable runner history rejection, and positive restoration with malformed objects still present but unreachable.
Reproduce historical setup failure after GC without rerunning/deleting historical Actions run39800181504. Confirm validator/policy/runner/workflows unchanged, full authority/shallow/root/history regressions, old Owner/Breaker evidence inactive, material digest exact, and exact new PR-head verification-gate/bootstrap-integrity/windows prerequisite success.
Do not remediate, merge, accept as Owner, touch UP-003 or persistence PRs, or start MIG-001.
