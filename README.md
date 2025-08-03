# Vote Now - Android Voting App

A modern Android voting application built with Jetpack Compose that replicates the functionality shown in the provided screenshots.

## Features

### 🗳️ Core Voting Features
- **Voter Login**: Secure login with roll number or email
- **Elections List**: View available elections with status indicators
- **Cast Vote**: Select candidates and confirm votes
- **Admin Dashboard**: Administrative controls for election management

### 📱 User Interface
- **Modern Design**: Clean, minimalist interface with Material Design
- **Responsive Layout**: Optimized for various Android screen sizes
- **Intuitive Navigation**: Bottom navigation and back button support
- **Status Indicators**: Clear visual feedback for election status

### 🔧 Technical Features
- **Jetpack Compose**: Modern Android UI toolkit
- **Material Design**: Google's design system implementation
- **State Management**: Reactive UI with Compose state
- **Navigation**: Screen-to-screen navigation flow

## Screens

### 1. Voter Login Screen
- Input field for roll number or email
- Blue "LOG IN" button
- "Secure Voting Platform" branding

### 2. Elections Screen
- List of available elections
- Election cards showing:
  - Election title (e.g., "Student Council Election")
  - Date range (e.g., "Apr 20 – Apr 22")
  - Status buttons ("Vote Now" or countdown timers)
- Bottom navigation bar

### 3. Cast Vote Screen
- Election position title (e.g., "President")
- List of candidates with:
  - Candidate avatars
  - Candidate names
  - Radio button selection
- Blue "CONFIRM" button
- Visual selection highlighting

### 4. Admin Dashboard Screen
- Administrative functions:
  - "Create Election" button
  - "Upload Voter List" button
  - "Add Candidates" button
- Clean, button-based interface

## Technology Stack

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Design System**: Material Design
- **Architecture**: MVVM pattern ready
- **Minimum SDK**: Android 7.0 (API level 24)
- **Target SDK**: Android 14 (API level 34)

## Project Structure

```
android-app/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/votenow/
│   │   │   ├── MainActivity.kt              # Main activity with all screens
│   │   │   └── ui/theme/                    # Theme configuration
│   │   │       ├── Color.kt                 # Color definitions
│   │   │       ├── Theme.kt                 # Material theme setup
│   │   │       └── Type.kt                  # Typography settings
│   │   ├── res/
│   │   │   └── values/
│   │   │       ├── colors.xml               # XML color resources
│   │   │       └── themes.xml               # XML theme definitions
│   │   └── AndroidManifest.xml              # App manifest
│   └── build.gradle                         # App-level build configuration
├── build.gradle                             # Project-level build configuration
├── settings.gradle                          # Gradle settings
└── gradle.properties                        # Gradle properties
```

## Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- Android SDK 24 or higher
- Kotlin 1.9.10 or later

### Installation
1. Clone or download the project
2. Open the `android-app` folder in Android Studio
3. Wait for Gradle sync to complete
4. Run the app on an emulator or physical device

### Building the App
```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease
```

## Design Specifications

### Color Scheme
- **Primary Blue**: #2563EB (Blue 500)
- **Light Blue**: #90CAF9 (Blue 200)
- **Background**: White (#FFFFFF)
- **Text**: Black (#000000)
- **Gray Elements**: #9E9E9E

### Typography
- **Headers**: Bold, 24-28sp
- **Body Text**: Regular, 16-18sp
- **Buttons**: Medium weight, 14-16sp
- **Font Family**: System default (Sans Serif)

## Current Implementation Status

✅ **Completed Features:**
- All four main screens implemented
- Navigation between screens
- Material Design theming
- Candidate selection with visual feedback
- Election status indicators
- Admin dashboard layout

🔄 **Future Enhancements:**
- Backend integration for real voting
- User authentication system
- Database integration
- Vote encryption and security
- Real-time election results
- Push notifications
- Offline voting capability

## Usage

1. **Login**: Enter roll number or email on the login screen
2. **Browse Elections**: View available elections and their status
3. **Vote**: Select an active election, choose candidates, and confirm
4. **Admin Access**: Access admin dashboard for election management
