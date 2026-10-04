# DentalArchLab iPhone research build

Original research prototype 0.16.0 (build 24). Reviewed source snapshot for an unsigned iPhone build.
This separate repository excludes original private history, account credentials, signing keys and patient scans.

This snapshot adds near-focus preparation before calibration and explanatory camera/recognition diagnostics. See NEAR_FOCUS_V016.md and RELEASE_DEVICE_TEST_TR.md inside the source archive for the reviewed workflow and its limitations. The original DAL case home and landscape capture layout remain. Physical ID selection supports four or six IDs from the original DAL family; full dictionary comparison precedes selection filtering. Image-bound diagnostics retain the actual camera profile and calibration used. Tissue and reference-gated Exocad research handoff remain. Manufacturer meshes and patient data are excluded. Physical iPhone clarity and accuracy still require real-device validation.

`iphone-source.zip` has its SHA-256 in `iphone-source.sha256`; the workflow verifies it before extraction.
Synthetic fixture PNG text metadata has been stripped without changing decoded pixels.
Run **Build iPhone IPA** manually from Actions using the standard macos-15-intel runner and Xcode 16.4.
Expected tests: 393 unit and 24 UI tests. These counts do not claim execution; logs and build provenance record actual results.
Official OpenCV is pinned by digest and its license/notices are included. The ARM64 IPA needs personal signing.

Physical accuracy and clinical suitability are unvalidated. A virtual mouth on a flat monitor is a 2D recognition test.
Real sound, torch, printed flags and reference metrology require an iPhone/device check. No new license grant is made for original application code; third-party notices remain.
