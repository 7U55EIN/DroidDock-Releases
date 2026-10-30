# DroidDock

رفيق أندرويد للماك وويندوز — Arabic / English Android desktop companion.

[Download releases / تنزيل الإصدارات](https://github.com/7U55EIN/DroidDock-Releases/releases)

Choose the package for macOS Apple Silicon, macOS Intel, or Windows x64. Extract macOS ZIP files completely before launching. Windows uses the NSIS setup executable.

## Development status / حالة التطوير

0.16.0 is an unsigned development preview. DroidDock checks this repository for releases. Automatic download and installation are disabled in this development build until release code signing is configured. Production macOS automatic updates require Developer ID signing; no signature checks are bypassed.

The backup workspace supports resumable interrupted backups and selective staged restores with skip / keep-both / replace policies and on-device SHA-256 verification. Shared storage for the primary Android user is supported; private app data is outside this backup scope.

The firmware workspace is an initial inspection tool only. It reads device properties and hashes local firmware packages. ZIP entry names can be previewed; compatibility and manufacturer signatures remain unverified. Flashing, unlocking and wiping are not enabled.

هذه نسخة تطوير غير موقعة. فحص الإصدارات مربوط بهذا المستودع، والتثبيت التلقائي ينتظر تجهيز التوقيع الرقمي. قسم السوفت وير للفحص والتحضير فقط، والتفليش غير مفعّل.

This repository contains release distribution material, not development source history. Checksums and update metadata accompany each release. SHA checksums identify file bytes; they do not replace publisher code signing.
