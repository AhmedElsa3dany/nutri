#!/usr/bin/env bash
set -e

# === تعديل هنا: ضع رابط مستودع GitHub الخاص بك ===
REPO_URL="https://github.com/USERNAME/REPOSITORY.git"

# === أسماء ملفات ===
README_FILE="README.md"
GITIGNORE_FILE=".gitignore"
LICENSE_FILE="LICENSE"

echo "1/5 - إنشاء README.md ..."
cat > "$README_FILE" <<'EOF'
# NutriMind 🥗

<p align="center">
  <img src="https://raw.githubusercontent.com/Ahmed-S-A-A/NutriMind/main/assets/images/logo.png" width="200" alt="NutriMind Logo">
</p>

<p align="center">
  <strong>Your journey to better health starts here.</strong>  
  A mobile app that helps you build personalized health and nutrition habits to improve your physical and mental well-being.
</p>

---

## 🌟 Overview  
**NutriMind** is a Flutter application designed to be your **personal health companion**.  
Through a series of detailed health surveys, the app understands your needs and goals to create customized daily routines that help you achieve a balanced lifestyle.

---

## ✨ Key Features  

- 🎬 **Professional Onboarding** – Smooth and engaging onboarding screens.  
- ✅ **Integrated Auth System** – Sign up / login with session management.  
- 📝 **Comprehensive Health Surveys**  
  - Collect personal info: *name, date of birth, weight, height*.  
  - Track health issues: *sleep hours, fatigue, headaches*.  
  - Lifestyle habits: *desk work, exercise, nutrition*.  
- 🍏 **Personalized Daily Routines** – Divided by *morning, mid-day, evening, night*.  
- 💪 **Daily Task Tracking** – Mark tasks as completed easily.  
- 🎨 **Modern & Attractive Design** – Clean UI with icons & images.  
- ⚙️ **Advanced State Management** – Built with `flutter_bloc (Cubit)`.  
- 🌐 **Backend Communication** – Using `Dio` + `dio_cookie_manager`.  

---

## 📁 Project Structure  

\`\`\`
lib/
├── core/
│   ├── utils/       # Helper files (colors, images, styles)
│   └── widget/      # Shared widgets
│
├── feature/
│   ├── onboarding/              # Onboarding screens
│   ├── regestration_and_login/  # Login & registration
│   ├── health_info_input/       # Health info & surveys
│   ├── routines/                # Personalized routines
│   └── splah/                   # Splash screen
│
└── main.dart   # App entry point
\`\`\`

---

## 🛠️ Tech Stack  

- **Language:** Dart  
- **Framework:** Flutter  
- **State Management:** flutter_bloc (Cubit)  
- **Networking:** Dio  
- **Cookie Management:** dio_cookie_manager  
- **Icons:** font_awesome_flutter  
- **Fonts:** google_fonts  

---

## 🚀 Getting Started  

### 1️⃣ Prerequisites  
- Install [Flutter SDK](https://flutter.dev/docs/get-started/install).  
- Make sure you have an emulator or a real device connected.  

### 2️⃣ Clone the Repository  
```bash
git clone https://github.com/Ahmed-S-A-A/NutriMind.git
cd NutriMind
3️⃣ Install Dependencies
bash
نسخ الكود
flutter pub get
4️⃣ Run the App
bash
نسخ الكود
flutter run
<p align="center"> Developed with 💚 by <a href="https://github.com/Ahmed-S-A-A">Ahmed S. A. A</a> </p> EOF
echo "2/5 - إنشاء .gitignore (Flutter) ..."
cat > "$GITIGNORE_FILE" <<'EOF'
