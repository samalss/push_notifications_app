# Push Notifications App

A Flutter app with Firebase Cloud Messaging (FCM) and local notifications.

## Features

- Push notifications using Firebase.
- Local notifications for foreground messages.
- Displays FCM token on the main screen.

## Setup

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/push_notifications_app.git
   cd push_notifications_app
   ```

2. **Install dependencies:**
   ```
   flutter pub get
   ```

3. **Add Firebase:**
   - Download `google-services.json` from Firebase Console.
   - Place it in `android/app/`.

4. **Run the app:**
   - For debug:
     ```
     flutter run
     ```
   - For release:
     ```
     flutter build apk --release
     ```

## License

This project is licensed under the MIT License.
