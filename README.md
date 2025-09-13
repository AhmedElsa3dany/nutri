<p align="center"> <img src="https://raw.githubusercontent.com/Ahmed-S-A-A/NutriMind/main/assets/images/logo.png" width="200" alt="NutriMind Logo"> </p> <p align="center"> <strong>Your journey to better health starts here.</strong> A mobile app that helps you build personalized health and nutrition habits to improve your physical and mental well-being. </p>
🌟 Overview

NutriMind is a Flutter application designed to be your personal health companion.
Through a series of detailed health surveys, the app understands your needs and goals to create customized daily routines that help you achieve a balanced lifestyle.

✨ Key Features

🎬 Professional Onboarding – Smooth and engaging onboarding screens.

✅ Integrated Auth System – Sign up / login with session management and session persistence.

📝 Comprehensive Health Surveys

Collect personal info: name, date of birth, weight, height.

Track health issues: sleep hours, fatigue, headaches.

Lifestyle habits: desk work, exercise, nutrition.

🍏 Personalized Daily Routines – Routines generated and divided by morning, mid-day, evening, night.

💪 Daily Task Tracking – Simple UI to mark tasks as completed.

🎨 Modern & Attractive Design – Clean layouts, high-quality icons and imagery.

⚙️ Advanced State Management – Implemented with flutter_bloc (Cubit).

🌐 Backend Communication – Uses Dio with cookie management (dio_cookie_manager) for authenticated requests.

📁 Project Structure
lib/
├── core/
│   ├── utils/       # Helper files (colors, images, styles)
│   └── widget/      # App-level shared widgets
│
├── feature/
│   ├── onboarding/              # Onboarding screens
│   ├── regestration_and_login/  # Login & registration screens
│   ├── health_info_input/       # Health info input and surveys
│   ├── routines/                # Screens for displaying personalized routines
│   └── splah/                   # Splash Screen
│
└── main.dart   # App entry point

🛠️ Tech Stack

Language: Dart

Framework: Flutter

State Management: flutter_bloc (Cubit)

Networking: Dio

Cookie Management: dio_cookie_manager

Icons: font_awesome_flutter

Fonts: google_fonts

🔧 Dependencies (example)

Add these (or similar) to your pubspec.yaml:

flutter_bloc

dio

dio_cookie_manager

cookie_jar

font_awesome_flutter

google_fonts

flutter_svg or vector_graphics (if using SVG assets)

lottie (optional for animations)

🚀 Getting Started
Prerequisites

Install Flutter SDK
.

Have an emulator or a physical device connected.

Clone the repository
git clone https://github.com/Ahmed-S-A-A/NutriMind.git
cd NutriMind

Install dependencies
flutter pub get

Run the app
flutter run

🧩 Notes & Best Practices

Ensure all assets (images, SVGs) are declared properly in pubspec.yaml and filenames are case-sensitive (Android/Linux).

Use full restart after adding new assets or changing pubspec.yaml (hot reload may not pick up new assets).

Protect network secrets (API keys) — do not hardcode them in the repository. Use environment variables or secure storage.

Consider adding unit/widget tests for critical logic and flows (survey processing, routine generation, auth flows).

📦 Useful Commands

flutter pub get — fetch dependencies

flutter clean — clean build artifacts

flutter run — run the app on connected device/emulator

flutter build apk / flutter build ios — build release artifacts

🤝 Contributing

Contributions, issues and feature requests are welcome. Feel free to open an issue or submit a pull request.

When contributing:

Fork the repository.

Create a new branch (git checkout -b feature/your-feature).

Make your changes and add tests if possible.

Submit a pull request describing your changes.

📄 License

This project is available under the MIT License. See the LICENSE file for details.

<p align="center"> Developed with 💚 by <a href="https://github.com/Ahmed-S-A-A">Ahmed S. A. A</a> </p>
