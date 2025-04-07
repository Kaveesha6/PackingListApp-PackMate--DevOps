# Packing List App (Pack Mate)

A mobile app designed to help users create personalized packing lists for their trips, with integrated budget management and weather-based item suggestions.

## Key Features

- Trip creation with location and dates
- Auto-suggested packing items based on weather
- Budget calculator per trip
- Category-based packing lists (hotel, rental, personal)
- Secure login via Firebase Authentication
- Real-time storage using Firebase Firestore

## Tech Stack

- Android Studio (Java + XML)
- Firebase (Auth, Firestore, Crashlytics)
- GitHub for version control
- CI/CD planned via GitHub Actions

## How to Run the App

1. Clone the repository:
   ```bash
   git clone https://github.com/Kaveesha6/PackingListApp-PackMate--DevOps.git
   
2. Open the project in Android Studio:
   - Launch Android Studio
   - Click on **File > Open** and select the folder where the app project is saved

3. Connect Firebase:
   - Go to [Firebase Console](https://console.firebase.google.com)
   - Create a new project (e.g., "PackingListAppFirebase")
   - Add an **Android app** to the project using your app's package name
   - Download the `google-services.json` file and place it inside your project's `app/` directory

4. Enable Firebase services:
   - **Authentication**: Enable Google Sign-In from the Authentication settings
   - **Firestore Database**: Create a Firestore Database in test mode
   - (Optional) **Crashlytics**: Enable crash reporting for error tracking

5. Run the app:
   - Either use an Android emulator from Android Studio
   - Or connect your physical Android phone via USB (with developer mode enabled)

   

