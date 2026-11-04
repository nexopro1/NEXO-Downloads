# NEXO Android diagnostic test — Build 45

Version 1.0.38, Build 45. Original com.nexoisrael.app signer and lineage.

[Download APK](NEXO-1.0.38-build45-arm64-device-test.apk) · [Build manifest](NEXO-1.0.38-build45-arm64-device-test.build-manifest.json)

Diagnostic-only candidate; native Google sign-in is not yet verified on the owner device. The authentication flow remains the same as Build 44; a finite first-provider status can now accompany the support reference. No raw provider/account/token details are returned or persisted. No browser fallback.

173 authentication tests and 487 actual native SDK checks passed. Original signing, all approved Build 44 visual/native payloads and resource table verified. Installation, physical upgrade and real Google login remain unverified. No Play rollout or automatic update-feed change.

Source: 91de2812a2b3c0fe0218cb3f6db530f41d75e0bc
