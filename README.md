# Clubhouse App

A sleek IPTV streaming app built with Flutter, featuring live TV channels, movies, and series. This app uses `flutter_bloc` for state management, `dio` for networking, and `shared_preferences` for local storage.

## Features
- 📺 Watch live TV channels
- 🎬 Browse movies and series
- ❤️ Favorite channels and content
- 🔍 Search and filter functionality
- Smooth navigation with bottom navigation bar
- Bloc architecture for clean state management

## Getting Started

### Prerequisites
- Flutter SDK: [Install Flutter](https://flutter.dev/docs/get-started/install)
- Dart: Comes with Flutter
- IDE: (Optional) Visual Studio Code or Android Studio

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/rewannashat/clubhouseApp.git
    cd clubhouseApp
    ```
2. Install dependencies:
    ```bash
    flutter pub get
    ```
3. Run the app:
    ```bash
    flutter run
    ```

## Project Structure
```
lib/
├── main.dart
├── blocs/               # BLoC (Business Logic Component)
├── models/              # Data models
├── repositories/        # Network requests (Dio)
├── screens/             # UI screens
├── widgets/             # Reusable UI components
└── utils/               # Helpers & constants
```

## Dependencies
- flutter_bloc
- dio
- shared_preferences

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

## License
This project is licensed under the MIT License.

---
Made with ❤️ by [rewannashat](https://github.com/rewannashat)

