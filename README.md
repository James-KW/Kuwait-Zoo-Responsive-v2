# Kuwait Zoo Responsive Firebase Site

This repository contains the public population report and admin login for the Kuwait Zoo app.

## Files
- `zooinfo.html` — public report page
- `admin-login.html` — admin sign-in page
- `firebase-config.js` — Firebase public web config
- `admin-species.js` — Firestore species add/delete support

## Deploy on Vercel
1. Import this repo into Vercel.
2. Use the default static project settings.
3. Set the root directory to the repository root.
4. Add the deployed domain to Firebase Authentication authorized domains.

## Important
- Firestore rules should allow public reads and restrict writes to the admin UID.
- Do not commit private Firebase service-account credentials.
