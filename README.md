# Ghost Rail: Escape the Dead Station

Ghost Rail is a horror escape experience for the web and Android.

## v1 Android APK

Download and install the v1 debug APK:

- [GhostRail-v1-debug.apk](./releases/GhostRail-v1-debug.apk)

Android may require allowing installation from unknown sources for this debug build.

## Run locally

**Prerequisites:** Node.js

```bash
npm install
npm run dev
```

The development server runs on port `3000`.

## Build

```bash
npm run lint
npm run build
```

The Android project is in [`android/`](./android/). Build the debug APK with:

```bash
npx cap sync android
./android/gradlew -p android assembleDebug
```
