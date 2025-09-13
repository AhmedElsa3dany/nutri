<p align="center">
  <img src="https://raw.githubusercontent.com/Ahmed-S-A-A/NutriMind/main/assets/images/logo.png" width="220" alt="NutriMind Logo">
</p>

# NutriMind

**Your journey to better health starts here.**
NutriMind is a Flutter app that helps users build personalized health and nutrition habits to improve both physical and mental well‑being through daily, easy-to-follow routines.

---

## 🌟 Overview

NutriMind collects detailed health and lifestyle data via interactive surveys (name, DOB, weight, height, sleep, fatigue, headaches, diet habits, activity level, etc.) and generates personalized daily routines split into Morning, Mid‑day, Evening, and Night.

---

## ✨ Key Features

* 🎬 Professional onboarding experience.
* ✅ Auth system with session persistence.
* 📝 Comprehensive health surveys for tailored recommendations.
* 🍏 Personalized daily routines and task lists.
* 💪 Simple daily task tracking (mark tasks as completed).
* 🎨 Modern UI with support for dark mode.
* ⚙️ State management with `flutter_bloc` (Cubit).
* 🌐 Backend communication using `dio` with cookie management (`dio_cookie_manager`).

---

## 🛠 Tech Stack

* Language: **Dart**
* Framework: **Flutter**
* State management: **flutter\_bloc (Cubit)**
* Networking: **dio**
* Cookie management: **dio\_cookie\_manager**, **cookie\_jar**
* Icons: **font\_awesome\_flutter**
* Fonts: **google\_fonts**

---

## 🚀 Quick Start

1. **Clone the repo**

```bash
git clone https://github.com/Ahmed-S-A-A/NutriMind.git
cd NutriMind
```

2. **Get dependencies**

```bash
flutter pub get
```

3. **Run the app**

```bash
flutter run
```

---

## ⚠️ Important Notes Before Pushing to GitHub

* Make sure all assets (images, SVGs, etc.) are declared in `pubspec.yaml` using the correct filenames and casing (case‑sensitive).
* After adding assets or changing `pubspec.yaml`, perform a full restart — hot reload might not pick up new assets.
* Never commit API keys or secrets to a public repo. Use environment variables or secure local files and add them to `.gitignore`.
* Provide example config files (e.g. `api_constants.example.dart`) and keep the real `api_constants.dart` out of version control.



---

## 🤝 Contributing

1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit and push your changes.
4. Open a pull request describing your changes.

---


