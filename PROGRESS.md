
## 2026-11-12 final Android/device migration acceptance

Migrated upstream `c0975f27b05dc33dd303742cea519f390552fb4c` with the standalone repository boundaries preserved.
- build-android.yml: success; release `android-v0.1.0-ci.1`; run https://github.com/YooDesk/vnc/actions/runs/43203358994; tested commit `daf8b0a21dec3fa8f72555bdfb19fa87e7336a99`.
- build.yml: success; release `v0.1.0-ci.33`; run https://github.com/YooDesk/vnc/actions/runs/43203922554; tested commit `daf8b0a21dec3fa8f72555bdfb19fa87e7336a99`.
Android builds use ARM64, API 24 and NDK 26.1.10909125 with 16 KiB ELF load alignment. Actual Android-device acceptance remains pending.
Original repository visibility and workflow activation were restored after the build. Documentation-only acceptance commits do not change the tested executable source.
