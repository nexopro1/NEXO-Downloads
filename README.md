# NEXO Android device test — Build 44

Version 1.0.38, Build 44. Original com.nexoisrael.app signing identity and lineage.

[Download APK](NEXO-1.0.38-build44-arm64-device-test.apk) · [Build manifest](NEXO-1.0.38-build44-arm64-device-test.build-manifest.json)

Uses the supported native Google account sheet, with one separate explicit request only after NoCredential. Cancellation never retries and NEXO never falls back to a browser. Incomplete requests can show an app-defined G00–G06 reference; no raw credential/provider details are displayed or persisted.

169 auth/runtime tests and 191 native API/runtime checks passed. Actual device installation, upgrade and Google sign-in remain unverified. Manual test candidate only; no Play rollout or automatic update-feed change.

Source: 02fefde43573eb6e66449965b36a8d443336c62b
