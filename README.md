# Torchlight Below (Android)

Isometric roguelike dungeon crawler, packaged as an Android app with Capacitor.

- The game lives in `www/index.html`, fully offline (three.js and fonts are bundled).
- Every push builds a debug APK through GitHub Actions and attaches it to a release.
- To build locally: `npm ci && npx cap sync android`, then open `android/` in Android Studio, or run `cd android && ./gradlew assembleDebug`.
