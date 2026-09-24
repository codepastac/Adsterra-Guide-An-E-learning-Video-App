# Adsterra Guide 🎓

> Learn how to earn with Adsterra through simple, practical video lessons, right on your phone.

[![Get it on Google Play](https://img.shields.io/badge/Google%20Play-Download-3DDC84?logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.adsterraearning.app)
![Expo](https://img.shields.io/badge/Expo-React%20Native-000020?logo=expo&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)

**Adsterra Guide** is an e-learning video app for anyone who wants to learn how to start earning with [Adsterra](https://adsterra.com). It brings video tutorials together in one easy-to-use mobile app, so beginners can follow along step by step without hunting for scattered guides.

👉 **[Download on Google Play](https://play.google.com/store/apps/details?id=com.adsterraearning.app)**

---

## ✨ Features

- 🎥 **Video lessons**: watch tutorials covering the Adsterra publisher journey, from the basics to earning tips.
- 📚 **Organized learning**: lessons are grouped so you always know what to watch next.
- 📱 **Mobile-first design**: a smooth, lightweight experience built for phones.
- 🚀 **Beginner friendly**: no prior experience needed.
- 🆓 **Free to use**: download and start learning right away.

---

## 🛠 Tech stack

- [Expo](https://expo.dev) and [React Native](https://reactnative.dev)
- [Expo Router](https://docs.expo.dev/router/introduction) (file-based routing)
- TypeScript
- ESLint for linting

---

## 🚀 Getting started

### Prerequisites

- [Node.js](https://nodejs.org) (LTS)
- npm or yarn
- Android Studio emulator, or a physical device with [Expo Go](https://expo.dev/go)

### Installation

```bash
# Clone the repository
git clone https://github.com/codepastac/Adsterra-Guide-An-E-learning-Video-App.git
cd Adsterra-Guide-An-E-learning-Video-App

# Install dependencies
npm install

# Start the development server
npx expo start
```

From the terminal output you can open the app in:

- [Development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go)

### Useful scripts

```bash
npx expo lint        # Run ESLint
npx expo start -c    # Start with a cleared cache
```

### Building for production

```bash
# Install EAS CLI
npm install -g eas-cli

# Build an Android App Bundle
eas build --platform android
```

---

## 📂 Project structure

```
.
├── app/            # Screens and routes (Expo Router)
├── assets/images/  # Images and icons
├── components/     # Reusable UI components
├── constants/      # Theme and config values
├── hooks/          # Custom React hooks
├── scripts/        # Helper scripts
├── app.json        # Expo app configuration
└── package.json
```

---

## 🗺 Roadmap

- [ ] iOS release
- [ ] Offline viewing for saved lessons
- [ ] Progress tracking and completed-lesson badges
- [ ] Search and bookmarks
- [ ] More lesson categories

---

## 🤝 Contributing

This project is open source, and contributions, issues and feature requests are welcome!

1. Fork the project
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m "Add amazing feature"`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## ⚠️ Disclaimer

This is an independent educational app and is **not affiliated with, endorsed by, or sponsored by Adsterra**. Adsterra is a trademark of its respective owner. Earnings are not guaranteed, and results depend on your traffic, effort and market conditions.

---

## 👨‍💻 Author

**Emmanuel Adesegun**, [A & J Web Technology](https://github.com/)

📧 **Contact:** [emmanueladesegun2@gmail.com](mailto:emmanueladesegun2@gmail.com)

If you find the app useful, please ⭐ the repo and leave a review on [Google Play](https://play.google.com/store/apps/details?id=com.adsterraearning.app)!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).