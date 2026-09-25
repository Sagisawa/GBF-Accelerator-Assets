# GBF-Accelerator-Assets

Binary runtime dependencies, companion patch tools, and portable runtimes for [GBF-Accelerator](https://github.com/Sagisawa/GBF-Accelerator).

## Purpose

This repository hosts pre-packaged, verified binary runtime dependencies required by the GBF-Accelerator Android companion patch toolchain. Distributing these binary assets separately keeps the main code repository lean while ensuring stable, permanent download endpoints across application version upgrades.

## Included Components (Release Assets)

| Component | Upstream Project | License | File Name |
| :--- | :--- | :--- | :--- |
| **Java 21+ Runtime (JBR)** | [JetBrains/JetBrainsRuntime](https://github.com/JetBrains/JetBrainsRuntime) / OpenJDK | GPLv2 + Classpath Exception | jre-windows-x64.zip |
| **Android Platform Tools** | [Google Android SDK](https://developer.android.com/tools/releases/platform-tools) | Apache License 2.0 | platform-tools-windows.zip |
| **LSPatch Portable Core** | [LSPosed/LSPatch](https://github.com/LSPosed/LSPatch) | GPLv3 | lspatch.jar |
| **GBF-Accelerator Module** | [Sagisawa/GBF-Accelerator](https://github.com/Sagisawa/GBF-Accelerator) | Apache 2.0 | xposed-release.apk |
| **Third-Party Licenses** | - | - | THIRD_PARTY_LICENSES.md |

For detailed license terms and upstream source links, see [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).
