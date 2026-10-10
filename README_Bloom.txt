# Bloom — Personal Growth Android-friendly PWA

Includes diet logs, manual steps, workouts, fasting, habits, reflections, weekly weight check-ins, JSON backup/restore, a PWA manifest and service worker.

## Try it
Open index.html in a browser to test most features. Data is saved to localStorage in that browser.

## Install on Android
PWA installation and offline service workers require HTTPS (or localhost). Host these files on an HTTPS static site, then open the site in Chrome on Android and choose Install app / Add to Home screen if offered.

## Data persistence
Entries remain in the same browser profile unless site data is cleared, but browser storage is not a true backup. Export JSON regularly. There is no account, cloud sync, encrypted database, or cross-device sync in this prototype.

## Next upgrades
For stronger structured storage use IndexedDB for a web app or Room for a native Android app. A native app can be built with Kotlin/Jetpack Compose, or the hosted PWA can be packaged as a Trusted Web Activity. Add PNG icons and validate installability before release.
