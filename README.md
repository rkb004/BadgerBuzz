# BadgerBuzz

### UW–Madison Campus Event Discovery App

BadgerBuzz is an Android application designed to help University of Wisconsin–Madison students discover, share, and explore events happening around campus and the greater Madison area.

Developed as a collaborative mobile application project, BadgerBuzz brings campus events into one platform, making it easier for students to find activities, connect with their community, and stay informed about local happenings.

## Overview

University campuses host hundreds of student organization events, social gatherings, and community activities, but information about these events is often scattered across different platforms.

BadgerBuzz addresses this problem by providing a centralized event-discovery experience where students can browse upcoming events, explore their locations, and contribute events for others to discover.

## Tech Stack

| Component | Technology |
|---|---|
| Mobile Development | Kotlin, Android SDK |
| Backend Services | Firebase |
| Cloud Functions | JavaScript, TypeScript |
| Maps | Google Maps integration |
| Build System | Gradle |
| Development Environment | Android Studio |

## Features

### Event Discovery

Browse events happening around UW–Madison through an event-listing interface designed for convenient access to campus activities.

### Interactive Event Map

Explore event locations through an interactive map with markers corresponding to posted events.

### Event Posting

Create and share events, allowing students to contribute activities and opportunities to the campus community.

### Firebase Integration

Firebase supports the application's backend functionality and event-related data operations.

### Automated Event Management

Cloud Functions provide backend logic for scheduled event cleanup and removal, helping maintain relevant event listings.

## Project Architecture

The application uses a Kotlin-based Android frontend integrated with Firebase services.

The Android application handles the user interface, event listings, and map interactions, while Firebase provides supporting backend functionality.

The repository also includes cloud function code for event-management operations.

## Repository Structure

```text
BadgerBuzz/
├── app/                  Android application source
├── functions/            Firebase Cloud Functions
├── gradle/               Gradle wrapper configuration
├── build.gradle.kts      Build configuration
├── settings.gradle.kts   Project settings
├── firebase.json         Firebase configuration
└── .firebaserc           Firebase project configuration
```

## Development

BadgerBuzz was developed as a collaborative software engineering project.

The project provided hands-on experience with Android application development, Kotlin, Firebase integration, map-based interfaces, and team-based software development using GitHub.

## Getting Started

To explore the Android project locally:

1. Clone the repository.
2. Open the project in Android Studio.
3. Configure the required Firebase project and Google Maps credentials.
4. Sync the Gradle dependencies.
5. Build and run the application using an Android emulator or compatible device.

The application depends on external service configuration and has not been independently verified against current Android and Firebase versions.

## Contributors

Original repository: [PatterJLP/BadgerBuzz](https://github.com/PatterJLP/BadgerBuzz)

This repository is a fork maintained under my personal GitHub profile to showcase the collaborative project.

## Project Status

Academic mobile application project. Not currently maintained or deployed as a production application.
