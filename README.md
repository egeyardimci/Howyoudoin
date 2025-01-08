# HowYouDoin - Real-Time Chat Application

A modern, secure real-time messaging platform built with Spring Boot and React Native (Expo), enabling seamless communication across mobile devices.

## Features

- Real-time messaging using WebSocket technology
- Group chat functionality
- Friend management system
- Secure authentication with JWT
- Cross-platform mobile support (iOS & Android)

## Tech Stack

### Backend

- Java Spring Boot
- SocketIO
- Spring Security with JWT
- MongoDB
- Gradle
- JUnit & Mockito for testing

### Frontend

- React Native with Expo
- SocketIO
- AsyncStorage
- Navigation
- Context API
- Axios

## Getting Started

### Prerequisites

- Node.js 16+
- Java 17+
- MongoDB
- Expo CLI
- Android Studio / Xcode (optional)

### Backend Setup

```bash
# Clone the repository
git clone https://github.com/egeyardimci/MessagesAPI

# Navigate to backend directory
cd MessagesAPI

# Build the project
./gradlew build

# Run the server
./gradlew bootRun
```

### Mobile App Setup

```bash
# Clone the repository
git clone https://github.com/egeyardimci/MessagesMobile

# Navigate to mobile directory
cd mobile

# Install dependencies
npm  install

# Start Expo development server
npx expo start

# Run on iOS Simulator
i
# Run on Android Emulator
a
```

## Testing

The backend includes test coverage:

```bash
# Run tests
./gradlew test jacocoTestReport
```

## Security

- JWT-based authentication
- Secured WebSocket connections

## API Documentation

API documentation is available at the repository of backend in the readme file.
