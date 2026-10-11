# V-Taper Coach — free self-contained app

This is a no-subscription, no-API mobile web app. It includes the 5-day plan, simplified animated SVG movement guides plus one-tap YouTube search links for real trainer demonstrations, workout checkboxes, notes, nutrition logging, weigh-ins, and JSON/CSV export. Data is stored in the browser on the device.

## Easiest way to try it
Open `index.html` in a browser. For the most reliable iPhone experience and an Add to Home Screen shortcut, publish it as a free static site.

## Publish free with GitHub Pages
1. Sign in or create a free GitHub account.
2. Create a new **public** repository, for example `vtaper-coach`.
3. Upload `index.html` to the repository root (the top level) and commit the change.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
6. Wait for the Pages URL to appear. Open it in Safari on your iPhone.
7. In Safari, tap **Share → Add to Home Screen**.

No payment details or API keys are required for this static app. GitHub's service terms and availability can change. Keep an exported JSON backup if you care about your logs. Browser data does not automatically sync between devices.

## Important health note
The plan is conservative but cannot guarantee prevention of haemorrhoid recurrence. Follow your treating clinician's advice after banding. Avoid breath-holding, forceful bracing and movements that cause pelvic/rectal pressure. Stop if pain, pressure or bleeding occurs and contact your clinician.

## Real exercise demonstrations
Each exercise includes a button that opens a YouTube search for that movement and proper form. This avoids copying or redistributing third-party videos and lets you choose a demonstration that matches your gym equipment.

## Apple Watch
This GitHub Pages version cannot directly connect to Apple Watch or read HealthKit. That needs a native iOS/watchOS app with HealthKit permissions. Automatic rep counting would require separate exercise-specific detection and testing.
