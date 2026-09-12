# চাকরি লাগবে! (Chakri Lagbe!)

An Android job portal application built with Java and Firebase.

## Features

- **User Registration & Authentication** — Firebase Auth based login/registration
- **Browse Jobs** — View all available job listings (`AllJobActivity`)
- **Job Details** — See full details of any job posting (`JobDetailsActivity`)
- **Post a Job** — Employers can post new job listings (`PostJobActivity`, `InsertJobPostActivity`)
- **Home Dashboard** — Central navigation hub (`HomeActivity`)
- **Firebase Realtime Database** — All job data synced in real-time

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Java |
| Platform | Android (minSdk 21, targetSdk 33) |
| Database | Firebase Realtime Database |
| Auth | Firebase Authentication |
| UI | Material Design Components |
| Build | Gradle 7.0.4 |

## Getting Started

### Prerequisites
- Android Studio (Arctic Fox or newer)
- JDK 8+
- A Firebase project with Realtime Database and Authentication enabled

### Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/MubaswiraIbnatZidney/Chakri-Lagbe.git
   cd Chakri-Lagbe
   ```

2. **Configure Firebase**
   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a project (or use existing one)
   - Add an Android app with package name `com.example.chakrilagbe`
   - Download `google-services.json` and place it in the `app/` directory

3. **Open in Android Studio**
   - Open Android Studio → Open → select this directory
   - Let Gradle sync complete

4. **Run**
   - Connect an Android device or start an emulator
   - Click **Run ▶** or use `Shift+F10`

## Project Structure

```
Chakri-Lagbe/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/chakrilagbe/
│   │       │   ├── MainActivity.java        # Entry point / Login
│   │       │   ├── RegistrationActivity.java
│   │       │   ├── HomeActivity.java
│   │       │   ├── AllJobActivity.java
│   │       │   ├── JobDetailsActivity.java
│   │       │   ├── PostJobActivity.java
│   │       │   ├── InsertJobPostActivity.java
│   │       │   └── model/
│   │       │       └── Data.java            # Job data model
│   │       ├── res/                         # Layouts, drawables, strings
│   │       └── AndroidManifest.xml
│   ├── build.gradle
│   └── google-services.json
├── build.gradle
├── settings.gradle
├── gradle.properties
└── gradlew / gradlew.bat
```

## License

This project was developed as an academic project.
