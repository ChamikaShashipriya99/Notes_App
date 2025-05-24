# Notes_App

Notes_App is a simple Android application for taking notes. It allows users to create, view, edit, and delete notes.

## Building and Running the Project

This is a standard Android Gradle project. To build and run the application:

1.  **Open in Android Studio:**
    *   Download and install [Android Studio](https://developer.android.com/studio) if you haven't already.
    *   Open Android Studio.
    *   Click on "Open" and navigate to the project's root directory.
    *   Select the project and click "OK".
2.  **Sync Gradle:**
    *   Android Studio should automatically start syncing Gradle. If not, click on the "Sync Project with Gradle Files" button (usually a small elephant icon) in the toolbar.
    *   Wait for the Gradle sync to complete.
3.  **Run the Application:**
    *   Once Gradle sync is successful, you can run the application on an Android emulator or a physical device.
    *   Select a run configuration (usually "app" by default).
    *   Click the "Run" button (green play icon) in the toolbar.

## Project Structure

The project follows a standard Android Gradle project structure:

*   `app/`: This directory contains the main application module.
    *   `src/main/java/`: Contains the Java/Kotlin source code for the application.
    *   `src/main/res/`: Contains all application resources like layouts (XML), drawables, strings, etc.
    *   `src/androidTest/`: Contains Android instrumentation tests.
    *   `src/test/`: Contains unit tests.
    *   `build.gradle.kts`: The build script for the `app` module.
*   `gradle/`: This directory contains the Gradle wrapper files, which allow the project to be built with a specific Gradle version.
*   `build.gradle.kts`: The top-level build script for the entire project. It defines build configurations that apply to all modules.
*   `settings.gradle.kts`: This file tells Gradle which modules to include when building the project.
*   `README.md`: (This file) Provides information about the project.

## Prerequisites and Dependencies

To build and run this project, you will need:

*   **Android Studio:** The official Integrated Development Environment (IDE) for Android app development. (Latest stable version recommended)
*   **Java Development Kit (JDK):** Android Studio usually comes with an embedded JDK. If not, or if you need a specific version, you'll need to install it separately (JDK 11 or higher is typically required for modern Android development).
*   **Android SDK:** Installed via Android Studio's SDK Manager. Ensure you have the necessary SDK platforms and build tools installed.

No external libraries are required beyond the standard Android and Jetpack libraries, which are managed by Gradle.
