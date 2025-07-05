# 🐾 Meowmentum – Mobile App

The **Meowmentum Mobile App** is the cross-platform companion to our AI-powered English–Vietnamese language learning platform.  
Built with **React Native**, **TypeScript**, and **Tailwind CSS** (via NativeWind), it offers gamified, adaptive learning experiences for learners on the go.

> 📱 Designed for vocabulary mastery, pronunciation fluency, and mobile engagement  
> 🔗 Full platform overview: [Meowmentum Overview](https://github.com/meowmentum-education)

---

## 🌟 Key Features

- 🧠 **AI-Powered Personalization**  
  Adaptive flashcards, topic recommendations, and difficulty scaling based on user progress.

- 🎮 **Gamified Practice System**  
  XP system, learning streaks, and interactive quiz modules to reinforce memory.

- 🗣️ **Speech Recognition**  
  Real-time pronunciation feedback (using Expo Speech now, Vosk planned).

- 📊 **Progress Dashboard**  
  Daily streaks, vocabulary mastered, and achievement tracking.

- 📂 **Thematic Vocabulary Packs**  
  Content grouped by CEFR levels and real-life topics for contextual learning.

---

## 🛠️ Tech Stack

| Layer         | Technology                              |
|---------------|------------------------------------------|
| Framework     | React Native (Expo SDK 50+)              |
| Language      | TypeScript                               |
| Styling       | Tailwind CSS (via NativeWind)            |
| UI Library    | React Native Paper (optional)            |
| Navigation    | React Navigation (v7)                    |
| State Mgmt    | Zustand / Context API                    |
| Speech        | Expo Speech / Vosk (planned)             |
| Backend API   | ASP.NET Core (JWT-secured endpoints)     |
| Storage       | AsyncStorage                             |

---

## 📁 Folder Structure

```
/meowmentum-mobile
├── assets/            # Icons, fonts, media
├── components/        # Reusable UI components
├── screens/           # App views (Home, Quiz, etc.)
├── navigation/        # Stack/tab navigation setup
├── services/          # API calls, auth, utils
├── hooks/             # Custom React hooks
├── constants/         # App config and UI tokens
├── types/             # TypeScript types
└── App.tsx            # Root entry point
```

---

## 🚀 Getting Started

### 📦 Prerequisites

- Node.js (v18+)
- Expo CLI (`npm install -g expo-cli`)
- Emulator or physical device with Expo Go

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

3. **Start the dev server**

   ```bash
   npx expo start
   ```

4. **Run on device or emulator**
   - Open with Expo Go
   - Press `a` (Android) or `i` (iOS) in CLI

---

## 🔐 Authentication

- JWT-based login via backend
- Tokens stored in AsyncStorage
- Auth context and protected screen logic in place

---

## 🌍 Environment Setup

Create a `.env` file at root:

```env
API_URL=https://localhost:5001/api
APP_NAME=Meowmentum
```

Use it with `react-native-dotenv` or config service.

---

## 🧪 Testing (planned)

Coming soon:
- Unit tests with Jest
- UI tests with Testing Library

---

## 📦 Deployment

- Build via **EAS Build** (Android/iOS)
- OTA updates supported via Expo Updates
- Google Play & App Store deployment planned post-MVP

---

## 🤝 Contributing

1. Fork this repo
2. Create a new feature branch
3. Make changes and commit
4. Submit a Pull Request

---

## 👥 Maintainer

- 👤 **Vũ Trần Quang Minh** – Frontend & AI Lead  
  📧 `minhvtqgcs220006@fpt.edu.vn`  
  GitHub: [@vutranquangminh](https://github.com/vutranquangminh)

---

> *Meowmentum – language learning made playful, personal, and portable.*

---