# Apple Sign In

A Flutter demo app showing how to integrate **Sign in with Apple** using the [`sign_in_with_apple`](https://pub.dev/packages/sign_in_with_apple) package.

## Features

- Native "Sign in with Apple" button (`SignInWithAppleButton`)
- Requests `email` and `fullName` scopes
- Prints the returned `userIdentifier`, `email`, and full credential to the console in debug mode

## Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (Dart `>=3.4.4 <4.0.0`)
- An Apple Developer account with the **Sign in with Apple** capability enabled
- Xcode (for iOS/macOS) with the `Sign in with Apple` entitlement configured in `Runner.entitlements`

### Setup

1. Install dependencies:

   ```bash
   flutter pub get
   ```

2. Run the app on a connected device or simulator:

   ```bash
   flutter run
   ```

> **Note:** Sign in with Apple requires a real iOS/macOS device or simulator signed in with an Apple ID for full functionality, and proper entitlements/capabilities configured in the Apple Developer portal.

## Project Structure

- [lib/main.dart](lib/main.dart) — app entry point and the Sign in with Apple button implementation

## Resources

- [sign_in_with_apple package](https://pub.dev/packages/sign_in_with_apple)
- [Apple: Sign in with Apple](https://developer.apple.com/sign-in-with-apple/)
- [Flutter documentation](https://docs.flutter.dev/)
