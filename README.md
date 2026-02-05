# 📱 DEMO-kiet2

A simple React Native mobile application built with Expo, showcasing basic mobile development concepts.

## 🚀 About

This is a demo/learning project built with **React Native** and **Expo**, supporting iOS, Android, and Web platforms. The app demonstrates basic React Native components and interactions with bilingual content (English and Vietnamese).

## 🛠️ Technology Stack

- **React Native** `0.81.5` - Mobile framework
- **React** `19.1.0` - UI library
- **Expo** `~54.0.33` - Development platform
- **expo-status-bar** `~3.0.9` - Status bar component

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher) - [Download here](https://nodejs.org/)
- **npm** or **yarn** package manager
- **Expo Go** app on your mobile device (for testing)
  - [iOS App Store](https://apps.apple.com/app/expo-go/id982107779)
  - [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/improperboy/DEMO-kiet2.git
   cd DEMO-kiet2
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## 🎮 Usage

### Start Development Server

```bash
npm start
```

This will open Expo DevTools in your browser. You can then:
- Scan the QR code with **Expo Go** app (iOS/Android)
- Press `a` to open in Android emulator
- Press `i` to open in iOS simulator
- Press `w` to open in web browser

### Platform-Specific Commands

```bash
# Run on Android
npm run android

# Run on iOS
npm run ios

# Run on Web
npm run web
```

## 📁 Project Structure

```
DEMO-kiet2/
├── App.js                  # Main application component
├── index.js               # Application entry point
├── app.json               # Expo configuration
├── package.json           # Dependencies and scripts
└── assets/                # Images and icons
    ├── icon.png          # App icon
    ├── splash-icon.png   # Splash screen
    ├── adaptive-icon.png # Android icon
    └── favicon.png       # Web favicon
```

## 🎨 Features

- ✅ Cross-platform support (iOS, Android, Web)
- ✅ Bilingual content (English & Vietnamese)
- ✅ Interactive button with alert
- ✅ Modern UI with React Native components
- ✅ New React Native Architecture enabled

## 🐛 Known Issues

- The `Button` component in `App.js` needs to be imported from `react-native`

## 🔧 Configuration

The app is configured in `app.json`:
- **App Name**: DEMOKiet
- **Version**: 1.0.0
- **Orientation**: Portrait
- **New Architecture**: Enabled
- **Edge-to-Edge Mode**: Enabled (Android)

## 📱 Supported Platforms

| Platform | Status |
|----------|--------|
| iOS      | ✅ Supported |
| Android  | ✅ Supported |
| Web      | ✅ Supported |

## 👤 Author

**Kiet** ([@improperboy](https://github.com/improperboy))

## 📄 License

This project is private and for learning purposes.

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are welcome!

## 📞 Support

If you have any questions or issues, please open an issue on [GitHub](https://github.com/improperboy/DEMO-kiet2/issues).

---

**Note**: Make sure to have Expo CLI installed globally: `npm install -g expo-cli`

Happy coding! 🎉
