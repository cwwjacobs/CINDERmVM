# CINDERmVM validation summary

This is a sanitized narrative summary prepared for the new source-only tree.
It is not an original receipt, signed evidence bundle, or independently reproduced
validation of this new tree. The underlying historical records are retained
privately and excluded from this release; none were edited to manufacture evidence.

## Recorded execution

Historical Cindermote records report real jailed Firecracker microVM execution
on a Void Linux host. The agent-probe run verified guest, egress, cleanup and
teardown witnesses but intentionally used an invalid provider key, leaving
EVALUATION_INCOMPLETE. A live-provider agent ALLOW has not been demonstrated.

The browser profile recorded five controlled HTTPS cases: clean ALLOW, and DENY
for POST, WebSocket, popup and unauthorized image-origin cases, with cleanup
verified. That evidence is bounded to the recorded source/host, not a claim of
production security or proof that arbitrary hostile workloads are contained.

The deprecated namespace profile also recorded six hostile probes with DENY,
signed receipts and cleanup. Detection efficacy and false-positive/negative
rates have not been established. HMAC receipts provide integrity for holders
of the host key, not public third-party authentication.

## This source snapshot

CINDERmVM is the public-facing name. Runtime modules and protocols retain
Cindermote identifiers for compatibility. Source identifiers and pinned guest
files have not been globally renamed. Consult RELEASE_SCOPE.md for exclusions.

Fresh local checks are reported separately; historical runs are not a fresh
validation pass and do not establish production readiness.
