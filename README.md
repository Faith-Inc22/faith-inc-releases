# Faith Inc — app downloads

Installers for the Faith Inc desktop apps. Source code lives in private repositories; only
the built installers are published here, so the download links need no login.

| App | Windows | macOS (Apple Silicon) | macOS (Intel) |
|---|---|---|---|
| **ReFormat** — converters and the Shorts Maker | ReFormat-Setup.exe (signed build coming) | [ReFormat-1.0.0-mac-arm64.dmg](https://github.com/Faith-Inc22/faith-inc-releases/releases/download/reformat-v1.0.0/ReFormat-1.0.0-mac-arm64.dmg) | [ReFormat-1.0.0-mac-x64.dmg](https://github.com/Faith-Inc22/faith-inc-releases/releases/download/reformat-v1.0.0/ReFormat-1.0.0-mac-x64.dmg) |
| **Eden** — a quieter place to watch (home media server with language filtering) | Eden-Setup.exe (signed build coming) | [Eden-2.0.0-mac-arm64.dmg](https://github.com/Faith-Inc22/faith-inc-releases/releases/download/eden-v2.0.0/Eden-2.0.0-mac-arm64.dmg) | [Eden-2.0.0-mac-x64.dmg](https://github.com/Faith-Inc22/faith-inc-releases/releases/download/eden-v2.0.0/Eden-2.0.0-mac-x64.dmg) |
| **Genesis Desktop** | [download.genesisdesktop.ca](https://download.genesisdesktop.ca) | — | — |

Releases are tagged `reformat-v<version>` and `eden-v<version>`; `tools-v*` releases hold
helper binaries the apps download on first use (the whisper.cpp engine for macOS).

**Windows:** the installers are signed by 2545288 Alberta Ltd. If SmartScreen still shows
"Windows protected your PC" on a brand-new release, choose *More info → Run anyway*.

**macOS:** Apple Silicon Macs (M1 and newer) take the arm64 file, Intel Macs the x64 file. Open the `.dmg`, drag the app to Applications. Until the apps carry an Apple
Developer ID, the first launch is blocked; open *System Settings → Privacy & Security*, scroll
down and choose *Open Anyway* once.
