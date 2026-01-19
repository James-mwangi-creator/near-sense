# Near Sense

Detects nearby solid objects using phone sensors to prevent collisions

## ✨ Features
- Proximity detection\n- Real-time distance display\n- Obstacle alert system\n- Detection history log

## 🚀 Quick Start

### Prerequisites
- Node.js 16 or newer
- Expo Go app on your phone (download from Play Store/App Store)

### Installation
```bash
# Install dependencies
npm install

# Start the development server
npx expo start
```

Then scan the QR code with:
- **Android**: Expo Go app
- **iOS**: Camera app (it will open in Expo Go)

## 📱 Build APK (Android)

### Using GitHub Actions (Recommended)
1. Go to the Actions tab
2. Click "Build Android APK"
3. Click "Run workflow"
4. Wait 3-5 minutes
5. Download APK from Artifacts

### Local Build
```bash
# Install EAS CLI
npm install -g eas-cli

# Build APK
eas build -p android --profile preview
```

## ☁️ Cloud Build

This repository includes GitHub Actions workflow for automatic APK builds:
- Triggers on every push to main
- Can be manually triggered from Actions tab
- APK available in Artifacts section after build completes

## 🔗 Links

- [Repository](https://github.com/James-mwangi-creator/near-sense)
- [Actions](https://github.com/James-mwangi-creator/near-sense/actions)
- [Expo Documentation](https://docs.expo.dev)

## 📄 License

MIT

---

Built with ☁️ Cloud App Builder + Expo
