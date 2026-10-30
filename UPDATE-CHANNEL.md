# DroidDock desktop update feed

This repository distributes macOS Intel / Apple Silicon packages and Windows NSIS installers. The release metadata files are latest-mac.yml and latest.yml.

The 0.16 development build can check this feed. Automatic download/install is intentionally disabled until release packages are code signed. This setting is visible in DroidDock Settings. Never embed GitHub access tokens or signing credentials in the app.

Development packages are unsigned previews. Device flashing is not enabled: the firmware workspace currently reads properties and inspects local package structure/hashes only.

Backup improvements include resumable interrupted backups, source SHA-256 verification, selected-folder restores, skip/keep-both/replace policies, staged restore files, and on-device hash verification.
