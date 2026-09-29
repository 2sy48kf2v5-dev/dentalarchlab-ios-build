# DentalArchLab iPhone research build

Original research prototype 0.11.1 (build 19). Reviewed source snapshot for an unsigned iPhone build.
This separate repository excludes original private history, account credentials, signing keys and patient scans.

Camera-first scanning with per-flag/FDI progress, analyzed-frame point highlights, accepted-frame and confirmation sounds, continuous torch controls and schematic MUA visualization. MUA placement requires a measured marker-to-MUA transform; a display body never supplies that transform. MG-MUASB9 is a user-supplied component reference, not a verified manufacturer CAD library.

`iphone-source.zip` has its SHA-256 in `iphone-source.sha256`; the workflow verifies it before extraction.
Synthetic fixture PNG text metadata has been stripped without changing decoded pixels.
Run **Build iPhone IPA** manually from Actions using the standard macos-15-intel runner and Xcode 16.4.
Expected tests: 229 unit and 13 UI tests. These counts do not claim execution; logs and build provenance record actual results.
Official OpenCV is pinned by digest and its license/notices are included. The ARM64 IPA needs personal signing.

Physical accuracy and clinical suitability are unvalidated. A virtual mouth on a flat monitor is a 2D recognition test.
Real sound, torch, printed flags and reference metrology require an iPhone/device check. No new license grant is made for original application code; third-party notices remain.
