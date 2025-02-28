# flutter_exam

## 📌 Overview
This Flutter project is a simple yet efficient application that retrieves and displays persons from FakeAPI with infinite scrolling and pagination. The app is designed with an eye-pleasing dark theme and supports Android, iOS, and Web platforms.

## 🚀 Features
- **Infinite Scrolling & Pagination**: Initially loads 10 persons and fetches 20 more on scroll, up to 4 attempts.
- **Snackbar Notification**: Informs users when no more data is available.
- **Custom UI Enhancement**: Instead of using images from the API, we display an account icon to ensure consistency and avoid potential issues with missing or broken images.
- **State Management**: Refactored to use **BLoC** for better scalability and maintainability.
- **Cross-Platform Compatibility**: Works on Android, iOS, and Web.

## 🛠️ Installation & Running the App

### 1️⃣ Prerequisites
Ensure you have the following installed:
- Flutter SDK (latest stable version)
- Dart
- Android Studio / Xcode (for emulators)
- Git

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/flutter_exam.git
cd flutter_exam
```

### 3️⃣ Install Dependencies
```sh
flutter pub get
```

### 4️⃣ Run the App
- **Android / iOS:**
  ```sh
  flutter run
  ```
- **Web:**
  ```sh
  flutter run -d chrome
  ```

## 🔧 Troubleshooting
**Common Issues & Fixes**

1. **Gradle Build Failure:** Ensure you run:
   ```sh
   flutter clean
   flutter pub get
   ```
2. **ADB Install Failure (Insufficient Storage):**
   ```sh
   adb uninstall com.example.flutter_exam
   flutter run
   ```
3. **iOS Simulator Not Running:** Accept Xcode license:
   ```sh
   sudo xcodebuild -license
   ```

## 💡 Why We Used Icons Instead of API Images
- **FakeAPI Does Not Provide Working Images**: The API used in this project retrieves images, but they do not display properly, appearing as broken links.
- **Consistency**: Some API images may be missing, incorrect, or of low quality.
- **Performance**: Icons load faster, improving UI responsiveness.
- **Better User Experience**: A uniform appearance across the app.

## 🤝 Contributing
Feel free to submit issues or pull requests to improve this project!

## 📜 License
This project is open-source and available under the MIT License.

---
**Maintained by: Mary Margarette Mariano**

