# DentalArchLab iPhone research build

Original research prototype 0.12.0 (build 20). Reviewed source snapshot for an unsigned iPhone build.
This separate repository excludes original private history, account credentials, signing keys and patient scans.

Native IOS mesh import, shared-point rigid registration, independent checkpoints and gated per-FDI Exocad research export. MegaGen_N_Type_MUA_Direkt_9mm catalog identity is checked against the official source; measured physical frame transforms and target-version interoperability remain separate prerequisites. Manufacturer STL files are excluded. Close-up physical camera selection and profile-aware high-resolution preview are included; real iPhone clarity remains unverified.

`iphone-source.zip` has its SHA-256 in `iphone-source.sha256`; the workflow verifies it before extraction.
Synthetic fixture PNG text metadata has been stripped without changing decoded pixels.
Run **Build iPhone IPA** manually from Actions using the standard macos-15-intel runner and Xcode 16.4.
Expected tests: 282 unit and 17 UI tests. These counts do not claim execution; logs and build provenance record actual results.
Official OpenCV is pinned by digest and its license/notices are included. The ARM64 IPA needs personal signing.

Physical accuracy and clinical suitability are unvalidated. A virtual mouth on a flat monitor is a 2D recognition test.
Real sound, torch, printed flags and reference metrology require an iPhone/device check. No new license grant is made for original application code; third-party notices remain.
