# Synthetic policy-versioning fixtures

These receipts and manifests are synthetic test data, not recorded executions,
not sanitized historical evidence, and not proof of containment. All signatures
use the public deterministic test key bytes(range(32)). Never use it operationally.
The archived policy is unmodified source configuration, retained to test the
v1.3-to-v1.4 binding boundary. Its exact hash is checked independently.

From this directory, with a file containing that test key:

```sh
python3 ../../../scripts/verify-incident-gate-evidence.py synthetic-run-a --key test-only-key --policy hotcell-policy-v1.3.json --expect-all
python3 ../../../scripts/verify-incident-gate-evidence.py synthetic-run-b --key test-only-key --policy hotcell-policy-v1.3.json --expect-all
```

Public tests retain schema validation, old-policy acceptance/new-policy rejection,
complete six-probe coverage per run, verifier signature checking and wrong-key
rejection. Assertions about exact historical execution bundles remain in the
private original suite; these fixtures do not replace historical proof.
