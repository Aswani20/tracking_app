# 🌸 Tracking App

A modern **Flutter e-commerce application** built with Clean Architecture.  
The app allows Drivers to deliver orders to users and user manage orders efficiently.

[![Flutter](https://img.shields.io/badge/Flutter-3.24-blue?logo=flutter)](https://flutter.dev)
[![Stars](https://img.shields.io/github/stars/CodKD/tracking_app?style=social)](https://github.com/CodKD/tracking_app/stargazers)
[![Issues](https://img.shields.io/github/issues/CodKD/tracking_app)](https://github.com/CodKD/tracking_app/issues)
[![License](https://img.shields.io/github/license/CodKD/tracking_app)](LICENSE)
[![Forks](https://img.shields.io/github/forks/CodKD/CodKD?style=social)](https://github.com/CodKD/tracking_app/network/members)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/CodKD/tracking_app/pulls)
[![Made with Love](https://img.shields.io/badge/Made%20with-%F0%9F%92%9F-pink)](https://github.com/CodKD/tracking_app)


## 📱 Features
- 🔑 User authentication (Aplly / Login / Forget Password)
- 🛒 Order details and tracking
- 🎨 Responsive UI with Material Design
- 🧱 Clean Architecture (API, Data, Domain, Presentation layers)


## 📡 API Documentation

This app communicates with a custom backend to manage products, carts, and orders.  
The base URL for all requests is: https://flower.elevateegy.com/api/v1


## Screenshots

Here are some screenshots of the app in action:

<p align="center">
  <img src="assets/screenshots/login.png" alt="Login Screen" width="20%" />
  <img src="assets/screenshots/register.png" alt="Register Screen" width="20%" />
  <img src="assets/screenshots/home_screen.png" alt="Home screen" width="20%" />
  <img src="assets/screenshots/setting_screen.png" alt="Setting Screen" width="20%" />
</p>


## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) (>= 3.x)
- Android Studio / VSCode
- Emulator or physical device

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/CodKD/tracking_app.git
    ```

2. Navigate to the project directory:
    ```bash
    cd tracking_app
    ```

3. Install dependencies:
    ```bash
    flutter pub get
    ```

4. Run the app:
    ```bash
    flutter run
    ```

### Testing

1. Run the app:

    ```bash
    flutter test
    ```

## 🤝 Contributing

- Fork the repo

- Create your feature branch (git checkout -b feature/YourFeature)

- Commit changes (git commit -m 'Add some feature')

- Push to branch (git push origin feature/YourFeature)

- Open a Pull Request

## 📜 License

Distributed under the MIT License. See LICENSE for more information.


## 👨‍💻 Author

1. Abdelrahman Youssef
2. Ali Mohamed
3. Marwan Elsokary
4. Lbar Sidati


## Folder Structure

```text
lib/
│
├── api_layer/          # Retrofit/Dio API setup
├── data_layer/         # Data sources & repositories
├── domain_layer/       # Use cases & entities
├── presentation_layer/ # UI & state management (Cubit/Bloc)
└── main.dart
