ASCEND LifeOS v2.1 - iPhone setup

WHAT'S NEW
- Liquid-glass inspired translucent surfaces, smoother transitions, animated flame glow and XP micro-feedback.
- iPhone haptics are not reliably exposed to PWAs; best-effort native bridge support and browser vibration fallback are included where supported.
- Five spaces: Today, Study, Sadhana, Progress, Settings.
- Personalised starter study plan: Data Science & ML, Mathematics/Statistics, Power BI (including SalesData.xlsx dashboard milestone), Psychology, Communication.
- Study focus timer with subject selection and logged sessions.
- Sadhana tracker and private daily reflection.
- Custom commitments, categories and custom learning subjects.
- XP and level progression, individual completion feedback, daily completion celebration and streak milestones (3, 7, 14, 21, 30, 50, 75, 100, 180, 365 days).
- Weekly reflection, progress summaries, export/import backup.
- Local-first storage and offline caching after first successful load.
- Existing ASCEND v1 local data is migrated when v2 loads on the same site origin.

IMPORTANT ABOUT IPHONE HAPTICS
iOS Safari does not provide a dependable public web vibration API. ASCEND therefore uses animated visual feedback and optional sound on iPhone instead of promising a vibration that may not happen. navigator.vibrate is used only where the browser actually exposes it (typically supported Android browsers). See the app's Settings for details.

INSTALL ON IPHONE 15 (FREE HOSTING VIA GITHUB PAGES)
1. Create a public GitHub repository named ascend-lifeos.
2. Upload index.html, manifest.webmanifest, service-worker.js, icon.svg and icon-180.png to the repository root.
3. Open repository Settings -> Pages.
4. Choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site.
6. Open the published HTTPS URL in Safari on your iPhone.
7. Tap Share -> Add to Home Screen. Keep Open as Web App enabled, then Add.

DATA AND PRIVACY
Your data is stored locally in the browser/app on this device. It does not automatically sync to your computer or another phone. Export backups regularly. The Home Screen web app may have a separate storage space from the Safari tab, so export/import if moving data between contexts.

This is a functional personal-use PWA starter. It does not yet include cloud sync, account login, background scheduled reminders, or native iOS haptic integration. A true native iOS app would be required for dependable Core Haptics/Taptic Engine control.

ASCEND 2.2 reward feedback update:
- Reward sounds are enabled by default for existing users unless they explicitly changed the sound setting.
- Task completions play a short ascending chime. Completing the day plays a longer celebration flourish.
- Settings includes a Preview Reward Sound button. On iPhone, tap Preview once to allow Safari to initialise audio.
- Haptics remain best-effort: iOS Safari/Home Screen PWAs do not expose a reliable public Taptic Engine API.
