# DataQuest — Data Engineering Study Tracker

A small interactive, game-style study dashboard. No build step or paid service is required.

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Create a **public** GitHub repository named `dataquest-study-tracker` (or another name you prefer).
2. Upload `index.html` and this README to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish; the Pages panel will show the live URL.

## Features
- Log study sessions with date, duration, course, topic and notes.
- XP, level, streak and session totals.
- Editable course completion and self-assessed skill levels.
- Recent activity and CSV export.
- Responsive layout for desktop and mobile.

## Important data note
The first version stores data in browser local storage on the current device/browser. It does **not** sync across devices or users. Export the CSV regularly. A later version can add authenticated cloud storage (for example Supabase or Firebase) so progress follows you across devices.

## Streak and skill scoring
A streak counts calendar days with at least one logged session. SQL/Python/PySpark and other skill levels are self-assessments that you update manually; they are not automatically measured from course completion.
