# DentalArchLab iPhone research build

Original research prototype 0.13.0 (build 21). Reviewed source snapshot for an unsigned iPhone build.
This separate repository excludes original private history, account credentials, signing keys and patient scans.

Macro workflow: continuous autofocus while aiming, verified focus lock at capture start, explicit physical ultra-wide calibration for XYZ. Per-frame hardware intrinsics bind new identity trials to the actual sample; calibrated XYZ retains measured intrinsics/distortion. Bounded local-illumination proposals recover shadowed target candidates without weakening geometric acceptance. Native 4/6-flag calibration-to-XYZ synthetic tests, frame metadata binding and negative recognition tests are included. Tissue and reference-gated Exocad research handoff remain. Manufacturer meshes and patient data are excluded. Physical iPhone clarity and accuracy still require real-device validation.

`iphone-source.zip` has its SHA-256 in `iphone-source.sha256`; the workflow verifies it before extraction.
Synthetic fixture PNG text metadata has been stripped without changing decoded pixels.
Run **Build iPhone IPA** manually from Actions using the standard macos-15-intel runner and Xcode 16.4.
Expected tests: 332 unit and 18 UI tests. These counts do not claim execution; logs and build provenance record actual results.
Official OpenCV is pinned by digest and its license/notices are included. The ARM64 IPA needs personal signing.

Physical accuracy and clinical suitability are unvalidated. A virtual mouth on a flat monitor is a 2D recognition test.
Real sound, torch, printed flags and reference metrology require an iPhone/device check. No new license grant is made for original application code; third-party notices remain.
