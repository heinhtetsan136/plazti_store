# Plazti Store

Plazti Store is a cross-platform mobile application developed with Flutter (Dart). It demonstrates modern app development patterns, integration with cloud authentication, and consumption of external RESTful APIs.

## Features

- **User Authentication:** Sign up and log in with Firebase Authentication for secure access management.
- **Product Catalog:** Browse a collection of products fetched dynamically from the [Platzi Fake Store API](https://fakeapi.platzi.com/).
- **Modern UI:** Responsive and attractive user interface built with Flutter widgets and Material Design principles.
- **Platform Support:** Designed to run on multiple platforms, including Android and iOS.

## Tech Stack

- **Frontend:** Flutter (Dart)
- **Backend as a Service:** [Firebase Authentication](https://firebase.google.com/products/auth)
- **API:** [Platzi Fake Store API](https://fakeapi.platzi.com/)
- **Other Languages:** C++, CMake, Swift, HTML, C

## Getting Started

1. **Clone this repository:**
   ```sh
   git clone https://github.com/heinhtetsan136/plazti_store.git
   cd plazti_store
   ```

2. **Set up Firebase:**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
   - Add your app to the Firebase project (Android/iOS).
   - Download the necessary configuration files (`google-services.json` for Android, `GoogleService-Info.plist` for iOS).
   - Follow the [FlutterFire documentation](https://firebase.flutter.dev/docs/overview/) to complete the integration.

3. **Install dependencies:**
   ```sh
   flutter pub get
   ```

4. **Run the app:**
   ```sh
   flutter run
   ```

## Firebase Authentication

The application allows users to register and log in using email and password authentication powered by Firebase Auth. This can be easily expanded to support additional providers such as Google and Facebook.

## Fetching Products from Platzi Fake API

Products are loaded by making HTTP requests to the [Platzi Fake API](https://fakeapi.platzi.com/). Responses are parsed and rendered in the product catalog view.

## License

