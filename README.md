# Pottypal
PottyPal is a mobile application designed to help users find and review restrooms based on cleanliness, amenities, and overall quality. Using real-time location data and user-generated reviews, PottyPal aims to provide a convenient and reliable way to locate the best restrooms nearby.

# Features
- User Registration and Authentication: Sign up and log in using email or social media accounts (Google, Facebook).
- Location-Based Restroom Search: View nearby restrooms on a map based on your current location.
- Restroom Details: Access detailed information about each restroom, including name, address, distance, and key amenities.
- User Reviews and Ratings: Submit and view ratings and reviews for cleanliness, amenities, and overall quality.
- Map Navigation: Navigate to selected restrooms using integrated map services.
- Favorites: Save your favorite restrooms for quick access in the future.
- Issue Reporting: Report issues with restrooms (e.g., cleanliness, closure) to inform other users and facility managers.
- User Feedback and Support: Provide feedback on the app and access support options if needed.

# Tech Stack
- Frontend: React Native
- Backend: Firebase (Authentication, Firestore, Storage)
- Maps Integration: Google Maps API or Mapbox
- State Management: Redux Toolkit

# Getting Started
- Prerequisites
- Node.js and npm
- React Native CLI
- Git

# Installation
1. Clone the Repository:
   git clone https://github.com/your-username/pottypal.git
   cd pottypal
2. Install Dependencies:
  npm install
3. Set Up Firebase:
- Create a new project in the Firebase Console.
- Follow the instructions to add Firebase to your iOS and Android apps.
- Download google-services.json (Android) and GoogleService-Info.plist (iOS) and place them in the appropriate directories.
4. Configure Firebase in Your Project:
- For Android, modify android/build.gradle and android/app/build.gradle to include Firebase configurations.
- For iOS, modify ios/Podfile and run pod install.

# Running the App
- iOS
  npx react-native run-ios
- Android
  npx react-native run-android

# Contributing
We welcome contributions to enhance PottyPal! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit them (git commit -m 'Add some feature').+
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgements
- React Native
- Firebase
- Redux Toolkit
- Google Maps API
   
   
