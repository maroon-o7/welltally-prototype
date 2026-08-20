# welltally interactive prototype

This repository hosts the sample-data prototype for **welltally**, a planned privacy-first iPhone health log for routines, measurements, and personal trends.

## Important testing boundary

Use sample data only. This public web prototype does not connect to Apple Health, Apple Watch, Fitbit, the App Store, iCloud, or the iPhone share sheet. It simulates those flows so testers can evaluate the product direction. It is not a medical device and does not provide medical advice.

First-run tracking and Apple Health choices intentionally begin unselected. After setup, the prototype loads a labeled sample dashboard so every feature remains available for testing; those sample cards do not imply that permission was granted.

Sample entries and an active fasting timer reset when the page reloads. The appearance preference is the only prototype setting retained by the browser. Automatic measurement units use the browser device's region when available. Setup and the optional calculators accept metric, pounds, or stone-and-pounds input; the setup height fields remain feet and inches when stone-and-pounds is selected.

The Today greeting follows the device's local clock. The **Weekly insight** preference shows or hides the **What stands out** section. Health-category selectors are interactive demonstrations only and begin unselected; they do not request real Apple Health access in Safari.

The production iPhone app is intended to keep health records on the user's device, request Apple Health categories individually, avoid location and product-analytics telemetry, and offer user-controlled encrypted backups.

## Test on an iPhone

1. Open the published prototype link in Safari.
2. Tap **Share**.
3. Choose **Add to Home Screen**.
4. Keep **Open as Web App** enabled, then tap **Add**.
5. Launch **welltally** from the Home Screen and use only the included sample information.

Useful feedback areas: first-time setup, light and dark appearance, clarity of Daily Progress, rapid or repeated taps, tracking and undo flows, measurement states, unit switching, calculators, privacy language, and whether the $9.99 one-time price feels fair after the 14-day trial.
