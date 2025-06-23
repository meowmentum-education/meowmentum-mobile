# 🐾 Meowmentum – Mobile App (React Native)

The **Meowmentum Mobile App** is the cross-platform companion to our AI-driven English learning platform. Developed with **React Native** and **Expo**, this app delivers gamified, personalized, and adaptive learning experiences — anytime, anywhere.

> 📱 Designed for learners on-the-go.  
> 🔗 See the full platform: [Meowmentum Overview](https://github.com/vutranquangminh/meowmentum)

---

## 🌟 Key Features

- 🧠 **AI-Powered Personalization**  
  Adaptive flashcards, quizzes, and recommendations tailored to user progress.

- 🎮 **Gamified Vocabulary Practice**  
  Daily goals, XP system, and memory-based learning mechanics.

- 🗣️ **Speech Recognition**  
  Practice pronunciation with real-time scoring (WIP).

- 📊 **Progress & Streak Tracker**  
  Visual feedback on daily, weekly, and long-term performance.

- 📂 **Modular Content by Topic/Level**  
  Choose vocabulary packs by CEFR level or theme.

---

## 🛠️ Tech Stack

| Layer         | Technology                       |
|---------------|-----------------------------------|
| Framework     | React Native (Expo SDK 50+)       |
| Language      | TypeScript                        |
| UI Library    | React Native Paper / Tailwind CSS (via NativeWind) |
| Navigation    | React Navigation (v7)             |
| State Mgmt    | Zustand / Context API             |
| Speech        | Expo Speech / Vosk (planned)      |
| Backend API   | ASP.NET Core (via secure JWT auth)|
| Storage       | AsyncStorage                      |

---

## 📁 Folder Structure

```
/meowmentum-mobile
├── assets/            # Icons, fonts, media
├── components/        # Reusable UI components
├── screens/           # App views (Login, Home, Quiz, etc.)
├── navigation/        # Stack/tab navigation setup
├── services/          # API calls, auth, utils
├── hooks/             # Custom React hooks
├── constants/         # Theme, config, static data
├── types/             # Shared TypeScript types
└── App.tsx            # Main app entry point
```

---

## 🚀 Getting Started

### 📦 Prerequisites

- [Node.js](https://nodejs.org/en/) (v18+)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- Android Studio or iOS Simulator (or real device with Expo Go)

### 🔧 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/vutranquangminh/meowmentum-mobile.git
   cd meowmentum-mobile
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npx expo start
   ```

4. **Run on device or emulator**
   - Scan QR with **Expo Go**
   - Or run with emulator using options `a` (Android) or `i` (iOS)

---

## 🔐 Authentication

- Secure login with JWT tokens via backend API
- User session managed via AsyncStorage

---

## 🌍 Environment Setup

Create a `.env` file:

```env
API_URL=https://localhost:5001/api
APP_NAME=Meowmentum
```

Then use it with libraries like `react-native-dotenv` or direct config.

---

## 🧪 Testing (optional)

Coming soon:  
Unit and integration tests using **Jest** and **@testing-library/react-native**.

---

## 📦 Deployment

- Expo EAS Build support (Android/iOS)
- Google Play & App Store submission planned post-MVP
- OTA updates via Expo Updates (optional)

---

## 🤝 Contributing

We welcome open-source contributions!

1. Fork the repo
2. Create a feature branch
3. Commit changes
4. Open a pull request

---

## 👥 Maintainer

- 👤 **Vũ Trần Quang Minh** – Frontend & AI Lead  
  📧 `minhvtqgcs220006@fpt.edu.vn`  
  GitHub: [@vutranquangminh](https://github.com/vutranquangminh)

---

> *Meowmentum – language learning made playful, personal, and portable.*

---