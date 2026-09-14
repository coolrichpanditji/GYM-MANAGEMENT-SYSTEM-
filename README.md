# The UK Gym – Management System

A responsive Firebase-authenticated gym management website. Each logged-in account has its own private member records stored in Firestore, including joining dates, fees, due months, diet charts and workout charts.

## Included
- Email/password and Google login
- Dynamic logged-in user name in the welcome area and header
- Responsive desktop and mobile layout
- Add, edit, delete and search members
- Fee collection, pending dues and payment status
- Personal diet and workout charts

## Setup
1. Upload all files to GitHub Pages.
2. In Firebase Authentication enable Email/Password and Google.
3. Add your GitHub Pages domain to Authorized domains.
4. Create Firestore Database.
5. Add secure Firestore rules so users can access only `users/{userId}/members` where `userId == request.auth.uid`.

## Important
The Firebase configuration is in `firebase-app.js`.
