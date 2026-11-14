# CINDERmVM source-release scope

This candidate includes application source, policies, schemas, tests, source build
scripts, and developer documentation. It does not include the original Git history,
private benchmark branches, private audit records/raw receipts, provider credentials,
downloaded Firecracker/kernel binaries, rootfs images, or container images.

Runtime identifiers remain `cindermote`; only the public project label has changed.
The existing PolyForm Noncommercial license and required author/contact notices
are preserved. No new license grant or legal clearance is implied.

The small compiled seccomp filter is reproducible byte-for-byte from
`observer/ptracer.py::seccomp_blob`; it is not a downloaded third-party binary.
Its SHA-256 is `caaf79daa5e893f0c6389fb81ba2d2a2265b17438417f4ed2fa84cdc30edde9c`.

`VALIDATION.md` is explicitly a sanitized narrative, not signed proof.
This candidate has not been published, and publication requires separate approval.

Policy-versioning tests use clearly labeled synthetic fixtures under
`tests/fixtures/policy-versioning`, not redacted historical receipts. Original
private evidence assertions are retained outside this release. The archived v1.3
policy is source configuration with its original SHA-256, not personal evidence.
