# Kuwait Zoo Responsive Firebase Site

The main public page is `zooinfo.html`; `index.html` redirects to the report. Admin sign-in uses Firebase Email/Password Authentication.

## Firebase
- `firebase-config.js` contains public web-app configuration only.
- Firestore rules should allow public reads and restrict app writes to the authenticated admin UID.
- Add your deployed Vercel domain to Firebase Authentication's authorized domains.

## Deploy on Vercel
Import this GitHub repository into Vercel. For a static HTML site, choose **Other**, leave build command and output directory blank, and deploy. This repository's index redirects to the existing GitHub Pages report until `zooinfo.html` and `admin-login.html` are copied in.
