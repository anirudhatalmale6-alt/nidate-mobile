# NiDate Mobile App

Capacitor wrapper for the NiDate dating app (nidate.com).

## Setup

```bash
npm install
npx cap sync
```

## iOS

Open in Xcode:
```bash
npx cap open ios
```

Requirements:
- macOS with Xcode 15+
- Apple Developer Account ($99/year)
- Set Team & Bundle ID in Xcode signing

## Android

Open in Android Studio:
```bash
npx cap open android
```

Requirements:
- Android Studio
- Google Play Developer Account ($25 one-time)

## Configuration

The app loads `https://nidate.com` as a WebView. All configuration is in `capacitor.config.ts`.

### Plugins Included
- Splash Screen (dark theme)
- Status Bar (dark style)
- Push Notifications
- Camera (photo verification)
- Browser (external links)
- Haptics (swipe feedback)
