PyPocket — Android Python Editor & Runner

PyPocket is an Android application project designed to let users write and execute Python programs on a mobile device.

Project Overview

The project explores native Android development, Python runtime integration, AI-assisted software development, and automated APK generation using GitHub Actions.

Features

- Python code entry and execution
- Output and error display
- Saved Python programs and starter examples
- Android-focused user interface
- Automated debug APK build workflow

Note: Confirm each feature against the current source and installed app before describing it as complete.

Technology Stack

- Google AI Studio: AI-assisted application development
- ChatGPT: Prompt engineering, development planning and troubleshooting
- Kotlin: Android application logic
- Jetpack Compose: Android user interface
- Chaquopy: Python integration for Android
- Gradle: Android build system
- GitHub: Source control and version history
- GitHub Actions: Automated build and artifact publishing

Build Automation

The project includes a GitHub Actions workflow at:

".github/workflows/build-apk.yml"

The intended workflow checks out the source, configures the Java and Android build environment, runs the Gradle build, and publishes a debug APK artifact.

Development Journey

The project began with a basic Python editor and runner. Development then focused on improving the native app and establishing a repeatable GitHub Actions build process.

Troubleshooting covered project structure, Android SDK setup, Gradle wrapper and JVM configuration, AndroidX settings, Kotlin/D8 compilation, and build-memory configuration.

Current Status

The basic app was observed executing a simple Python program. A GitHub Actions run also produced a debug APK artifact.

The upgraded APK installation and all intended new features have not yet been fully verified. Further work is required to confirm that the latest native source is committed to the correct branch, build that source, and test the resulting APK on a physical Android device.

What I Learned

- AI-assisted application development and prompt engineering
- Native Android project structure
- Python runtime integration
- GitHub branches and commits
- GitHub Actions and CI build troubleshooting
- APK artifacts, installation compatibility, and device testing

Repository

Source code and build workflow: https://github.com/

Disclaimer

This is a learning and portfolio project. Build status and feature availability should be confirmed against the latest source and tested application.
