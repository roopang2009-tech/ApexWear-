# ApexWear

A basic Android application project.

## Prerequisites
- Java 21 (OpenJDK)
- Kotlin Compiler
- Android SDK (with platform tools and build tools)
- ADB

Install these offline as per the provided guide.

## Build Instructions
1. Ensure ANDROID_HOME and JAVA_HOME are set.
2. Run `./gradlew build` to build the app.
3. Run `./gradlew installDebug` to install on a connected device/emulator.

## Project Structure
- `app/`: Main application module
- `build.gradle`: Root build file
- `gradlew`: Gradle wrapper