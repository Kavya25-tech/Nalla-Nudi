# ನಲ್ಲ-ನುಡಿ (Nalla-Nudi)
### Bridge Dictionary for Technical Terms

An offline-first Android application designed to help 
Kannada-medium students overcome the English technical 
vocabulary barrier when transitioning to English-medium 
higher education.

## Features
- Instant offline search in under 200ms
- English to Kannada bilingual technical terms
- TTS Pronunciation (works offline)
- Subject filters — Science, Mathematics, Commerce
- Sub-subject filters — Physics, Chemistry, Biology etc.
- My List — save up to 500 terms
- Flashcard Revision with Learnt / Revise Again tracking
- Word of the Day on home screen
- 100% Offline — no internet required

## Screens
- Splash Screen
- Home Screen
- Search Screen
- Subject Screen
- Term Detail Screen
- My List Screen
- Flashcard Revision Screen

## Tech Stack
- Language: Kotlin
- UI: Jetpack Compose + Material Design 3
- Architecture: MVVM + Clean Architecture
- Database: Room DB (SQLite + FTS4)
- DI: Hilt (Dagger)
- Navigation: Navigation Compose
- TTS: Android TextToSpeech API
- Async: Kotlin Coroutines + Flow

## How to Run
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle
4. Run on emulator or Android device (API 21+)

## Project Structure
app/src/main/java/com/example/nalla_nudi/
├── data/
│   ├── local/         # Room Database, DAO
│   └── repository/    # Repository
├── di/                # Hilt Modules
├── model/             # Data Models
├── ui/
│   ├── screens/       # All Screens
│   ├── theme/         # App Theme
│   └── viewmodel/     # ViewModel
└── MainActivity.kt

## Developer
- Name: Kavya
- Roll No: 4SN22CS045
- College: Srinivas Institute of Technology, Mangaluru
- Internship: MindMatrix.io, Bangalore
