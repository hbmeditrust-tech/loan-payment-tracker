# Loan Payment Tracker — APK-ready package

App name: Loan Payment Tracker
Package ID: com.healthbuddy.loantracker

## Included
- index.html — mobile app
- manifest.webmanifest — Android/PWA manifest
- sw.js — offline service worker
- icons/ — app icons

## Important
The app stores loan data locally in IndexedDB. Data in the browser and data in an installed Android package may use different storage origins, so use the app Backup/Restore JSON feature to move existing data.

## Android packaging
This package is prepared for a PWA packaging service such as PWABuilder. PWABuilder can generate sideloadable Android packages from a properly hosted PWA.
