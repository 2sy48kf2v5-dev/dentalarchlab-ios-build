# DentalArchLab iPhone research build

Original experimental dental photogrammetry prototype, version 0.10.1 (build 17).
This separate repository contains a reviewed source snapshot for an unsigned iPhone
build. It does not contain the original private repository history, signing keys,
patient scans, or account credentials.

`iphone-source.zip` contains the iOS source, original marker geometry, synthetic
test fixtures, and tests. Its SHA-256 is recorded in `iphone-source.sha256` and is
checked before extraction. PNG text metadata was removed from test fixtures
without changing their image pixels.

Run **Build iPhone IPA** manually from Actions. It uses the standard
`macos-15-intel` runner and Xcode 16.4, runs Apple simulator tests, then builds a
real arm64 iPhone application. The IPA is unsigned and requires personal signing
before installation. The workflow downloads the official pinned OpenCV release;
OpenCV license and third-party notices are included in the source and app.

The source includes 165 unit tests and 12 UI tests. These counts describe expected
tests, not a claim that the current build has passed. Actual workflow artifacts
contain compiler logs, executed test results, and build provenance.

This is a research prototype. Physical accuracy, clinical suitability, and
micron-level performance have not been validated. A virtual mouth displayed on a
flat monitor is a 2D marker-recognition test, not a physical 3D reference object.

No license grant for the original application code is added by this repository.
Third-party components retain their respective notices and licenses.
