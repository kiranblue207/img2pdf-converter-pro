# Image to PDF Converter PRO — Scan & OCR (GitHub-ready)

This repository contains the PWA source for **Image to PDF Converter PRO — Scan & OCR**.
It is prepared for uploading to GitHub as a ready-to-run PWA project that can be wrapped
into an Android app (Trusted Web Activity / Capacitor) and published to Google Play.

**Owner:** Replace in README and manifest with your name/email.

## What is included
- `index.html` — starter UI + placeholder JS (developer should replace with full app code)
- `sw.js`, `manifest.json` — PWA support
- `lib/` — placeholder library files (replace with real libs)
- `tessdata/` — placeholder traineddata files (replace with real Tesseract traineddata)
- `dev/DEV_NOTES.md` — step-by-step developer instructions
- `PRIVACY_POLICY.txt`, `TERMS.txt`
- `.gitignore`, `LICENSE` (MIT)

## How to use
1. Unzip and review files.
2. Replace placeholders in `lib/` and `tessdata/` with the real files.
3. Wrap the PWA using Trusted Web Activity (Bubblewrap) or Capacitor for Android.
4. Integrate AdMob (native) and Google Play Billing in the Android wrapper (not in web code).
5. Test, sign, and upload `.aab` to Google Play Console (owner account).

See `dev/DEV_NOTES.md` for a detailed checklist.

_Last generated: 2025-09-17T05:59:13.963197 UTC_
