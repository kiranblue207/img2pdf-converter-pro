# DEV_NOTES - Developer Handoff (short)

1. Replace placeholder libs in /lib/:
   - jspdf.umd.min.js
   - Sortable.min.js
   - tesseract.min.js
   - tailwind.min.css

2. Add tessdata files in /tessdata/:
   - eng.traineddata
   - hin.traineddata

3. Wrap PWA:
   - Option A: Trusted Web Activity (Bubblewrap)
   - Option B: Capacitor (recommended if using AdMob & Billing)

4. Native Integrations (Android):
   - Integrate AdMob SDK (banner, interstitial, rewarded)
   - Integrate Google Play Billing (subscription remove_ads_yearly)
   - Implement purchase restore & validation

5. Testing:
   - Use AdMob test IDs and Play license testers.
   - Test OCR offline, conversions up to 50 images.

6. Build:
   - Produce signed .aab, include build instructions in README.
