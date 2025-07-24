# 🛍️ Shopping_APP

A beautifully designed Shopping App built with **Flutter**, now enhanced with **Firebase** backend integration to provide real-time data and persistent user experience. This application is a great foundation for a full-fledged e-commerce platform.

## 🚀 Features

- 🧾 Product listing with image, title, and price
- 🛒 Add to Cart functionality with real-time updates
- 🧺 Cart screen with quantity management and total price calculation
- 🔐 User Authentication with Firebase Auth (Email/Password)
- ☁️ Real-time database using Firebase Firestore
- 🧭 Bottom navigation for seamless navigation
- 🎨 Clean, modern, and responsive UI
- 🔁 Stateful and stateless widget integration


## 🛠️ Technologies Used

- **Flutter** (Dart)
- **Firebase Auth** – User login/signup
- **Firebase Firestore** – Product and cart data
- **Firebase Core**
- **Material Design**
- **Provider** – State management

## 🏁 Getting Started

### Prerequisites

- Flutter SDK installed (version >= 3.0.0)
- Android Studio or VS Code
- Firebase project with configuration files added
- Emulator or physical device

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/Paaaarth1909/Shopping_APP.git
```

2. **Navigate to the project directory**
```bash
cd Shopping_APP
```

3. **Install dependencies**
```bash
flutter pub get
```

4. **Set up Firebase**

- Create a project on [Firebase Console](https://console.firebase.google.com/)
- Add Android/iOS app and download the `google-services.json` or `GoogleService-Info.plist`
- Place them in the appropriate directory:
  - `android/app/google-services.json`
  - `ios/Runner/GoogleService-Info.plist`
- Enable **Authentication** and **Firestore Database**

5. **Run the app**
```bash
flutter run
```

## 📂 Folder Structure

```
Shopping_APP/
├── lib/
│   ├── main.dart
│   ├── models/
│   ├── screens/
│   ├── widgets/
│   ├── services/
│   └── firebase_options.dart
├── android/app/google-services.json
├── ios/Runner/GoogleService-Info.plist
├── assets/
│   └── images/
├── pubspec.yaml
└── README.md
```

## 🤝 Contributing

Feel free to fork this project and submit a pull request if you'd like to contribute!

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

### 📬 Contact

Developed by [Parthsaarthie Sharma](https://github.com/Paaaarth1909)  
📧 For suggestions or queries: *open an issue on this repo*