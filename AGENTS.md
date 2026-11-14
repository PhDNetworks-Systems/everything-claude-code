# everything-claude-code agent instructions

## Ship Standard — Cloud execution and release boundaries

Current Cloud-only execution rules take precedence over older workstation,
credential-retrieval or automatic-release examples below. They preserve all
stricter project safety and owner-approval gates. This file remains standalone
for installer consumers; reading a relative repository file is not required.


Engineering runs only in a verified remote Cloud executor. Before mutation,
record the provider/configuration and runtime/task identity, actual host/OS and
working directory, repository remote/branch/HEAD/tree and clean status, tool
versions, and measured synthetic/read-only command exits. Never use an owner's
Mac/Windows checkout, terminal, filesystem service or desktop automation as an
engineering fallback. Never print credentials or customer records.

Preserve the target project's existing owner, lease/fencing/ledger, dependency
order and production protections. Do not introduce a second orchestrator. Use
included subscription capacity only; do not spend API credits, add services or
switch accounts to evade a limit. Stop the dependent action on a CLI error or permission denial.
Do not access an owner's credential stores or put production credentials in
ordinary test environments. Normal CLI permissions remain enabled; an unattended permission request must
fail closed rather than be bypassed.

Ship bounded work through a normal PR with scoped checks and a fresh independent
review from a different model family. Same-family preparation alone does not
satisfy that review gate. Obtain packet-specific approval before transferring
sensitive review material to an external service; old approvals do not cover new
packets. Keep merge/deploy held while a required gate is unmet.

Preserve protected merge methods, deployments and rollback contracts. Record the
exact checked commit/tree, review, merge, actual deployment and live evidence
before claiming delivery. Do not revive dormant/archived products or alter DNS,
billing, production data or customer messaging. WordPress writes retain exact
release approval and a fresh backup. Apple qualification requires a verified
Cloud macOS executor; Linux checks cannot prove iOS or App Store readiness.

The canonical rollout contract is maintained in
https://github.com/PhDNetworks-Systems/quoteforge/blob/main/docs/standards/SHIP-STANDARD.md
and its companion `CODEX-ROLLOUT.md`. Apply the current owner's stricter scope.
