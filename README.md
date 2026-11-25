# tebako-intake-fixture

A **doctored fixture registry** for the tebako community feedstock
lane's intake-review evidence (tebako-packages/index#23,
tebako-packages/index#25). The `tpkg-registry.yaml` here describes the
REAL `hello-ruby@1.0.0` artifact from tebako-packages/hello-runtimes but
pins a deliberately wrong sha256 (first nibble flipped). The
intake-review workflow must fail the submission red, naming
`Sha256Mismatch`. Not a payload source; never register this repo.
