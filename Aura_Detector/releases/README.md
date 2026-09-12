# Test builds

This directory contains APKs intentionally published with the repository so a reviewer can install the current Android prototype without building it locally.

| File | Variant | Intended use |
|---|---|---|
| `AuraDetector-v1.0-debug.apk` | Debug, Android debug-key signed | Development and device testing |

These are test artifacts, not production releases. They use the standard local Android debug certificate and must not be uploaded to Google Play. For a distributable public release, create a dedicated release keystore and configure Gradle signing before building.
