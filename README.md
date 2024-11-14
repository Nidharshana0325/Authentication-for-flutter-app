# Phone Authentication App

This is a Flutter application that provides phone authentication using Firebase. The app also includes a language selection screen to enhance the user experience by allowing users to choose their preferred language.

## Features

- **Phone Authentication**: Users can sign in with their phone numbers using Firebase Authentication.
- **Language Selection**: Users can select their preferred language upon launching the app.
- **Firebase Integration**: Firebase is used for backend services, primarily authentication in this app.
## Demo

[Click here to watch the demo on Google Drive](https://drive.google.com/file/d/1VBQqT_qgBObnRuks97mwueps6PKTFzfW/view?usp=sharing)

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Firebase account](https://firebase.google.com/) for Firebase configuration

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Nidharshana0325/Authentication-for-flutter-app.git
    cd Authentication-for-flutter-app
    ```

2. **Install dependencies**:
    ```bash
    flutter pub get
    ```

3. **Firebase Setup**:
    - Go to the [Firebase Console](https://console.firebase.google.com/).
    - Create a new project and add an iOS and/or Android app.
    - Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) files.
    - Place these files in your Flutter project:
      - `android/app` directory for `google-services.json`
      - `ios/Runner` directory for `GoogleService-Info.plist`
    - Configure Firebase options in `firebase_options.dart`.

4. **Run the App**:
    ```bash
    flutter run
    ```

## Project Structure

- `lib/main.dart`: The main entry point of the application.
- `lib/screens/language_selection.dart`: Language selection screen.
- `firebase_options.dart`: Firebase configuration options.

## Dependencies

- **firebase_core**: Core Firebase SDK for Flutter.
- **firebase_auth**: Firebase Authentication SDK for phone authentication.

## Troubleshooting

- Make sure Firebase is correctly initialized, and the necessary files (`google-services.json` or `GoogleService-Info.plist`) are in the correct directories.
- Ensure you have configured the `firebase_options.dart` file for platform-specific settings.

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository and make a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
