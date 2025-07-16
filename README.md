# 🍽️ Food App – Flutter Recipe & Search UI

A beautiful and user-friendly Flutter application to browse, search, and explore simple food recipes.  
This app features interactive food cards, smooth animations, and clean UI — ideal for showcasing Flutter development and UI/UX design skills.

---

## ✨ Features

- 🥗 **Food Cards UI** – Browse delicious-looking food cards with images
- 🔍 **Search Functionality** – Search for food by name in real time
- 📋 **Simple Recipes** – Tap on any card to view an easy-to-follow recipe
- 📱 Responsive Layout – Works on all screen sizes
- 🎞️ Lottie animations & Text effects for enhanced experience
- 🖼️ Custom image, icon, and font assets

---

## 📦 Tech Stack

| Category     | Tools / Packages              |
| ------------ | ----------------------------- |
| UI Framework | Flutter                       |
| Language     | Dart                          |
| Animations   | `lottie`, `animated_text_kit` |
| HTTP         | `http` (for future API use)   |
| Fonts        | Exo, Merienda                 |
| Icons        | Cupertino Icons               |
| Linting      | `flutter_lints`               |

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK `>=3.5.4`
* Dart SDK
* Android Studio / VS Code
* Emulator or physical device

### Installation

```bash
git clone https://github.com/Satyam070/food_app.git
cd food_app
flutter pub get
flutter run
```

---

## 🔎 App Overview

* Home screen shows food cards
* Search bar filters food items as you type
* Tap a food card → Navigate to a detail screen with a **simple recipe**
* Uses local assets for images, icons, and fonts

---

## 📂 Folder Structure

```
food_app/
├── assets/
│   ├── images/         # Food images
│   ├── icons/          # App icons
│   └── fonts/          # Custom fonts
├── lib/
│   ├── main.dart       # Entry point
│   ├── screens/        # Home, Detail, Search screens
│   ├── widgets/        # Reusable UI components
│   ├── models/         # Data models
│   └── utils/          # Constants, helpers
├── pubspec.yaml
└── README.md
```

---

## 🧪 Run Tests

```bash
flutter test
```

---

## 🧹 Lint Check

```bash
flutter analyze
```

---

## 📌 To-Do / Future Plans

* 🔥 Add Firebase or API integration for real data
* 🧾 Save favorite recipes
* 🍳 Step-by-step cooking mode
* 🌐 Multilingual support

---