# Firebase Dashboard Apps

This repository contains **two apps** connected to the same Firebase project:

- **Angular Web App** (`angular-web`)
- **Flutter Mobile App** (`flutter-mobile`)

---

## Setup

### Angular Web App

1. Navigate to the Angular folder:

```bash
cd angular-web
Install dependencies:

bash
Copy code
npm install
Start the development server:

bash
Copy code
ng serve
Open http://localhost:4200 in your browser.

### Flutter Mobile App

Navigate to the Flutter folder:

cd flutter-mobile


Install dependencies:

flutter pub get


Run the app on an emulator or connected device:

flutter run


###Firebase Setup

Enable Authentication → Email/Password.

Create Firestore collection products with documents:

{
  "name": "string",
  "price": 0,
  "imageUrl": "string"
}

---

Angular: update firebaseConfig in environment.ts

Flutter: add google-services.json (Android) and GoogleService-Info.plist (iOS)

Both apps are independent but use the same Firebase backend.
