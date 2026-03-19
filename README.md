# VIT Admin Panel

## Setup
1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase use --add` (select your project: vision-it-institute-8e414)
4. Deploy rules: `firebase deploy --only firestore:rules,firestore:indexes`
5. Deploy hosting: `firebase deploy --only hosting`

## Files
- `index.html` — Admin panel (all features)
- `firestore.rules` — Firestore security rules (deploy once, shared)
- `firestore.indexes.json` — Required composite indexes (deploy once)
- `firebase.json` — Firebase project config
