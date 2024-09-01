# Aeria

Welcome to **Aeria!** This repository contains code for the video-sharing platform, built using React Native and Expo, and other technologies, with backend services managed by Appwrite.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [Project Structure](#project-structure)
5. [Technologies Used](#technologies-used)
6. [Appwrite Integration](#appwrite-integration)
7. [Support](#support)
8. [Badges](#badges)

## Introduction

Aeria is a video-sharing app where users can upload videos for everyone to watch and manage their uploaded content through their profiles. This application uses React Native and Expo, with backend services such as authentication, database, and file storage managed by Appwrite.
## Features

- Video upload and playback.

- User profile management.

- Authentication and authorization using Appwrite.

- Integration with Appwrite's database and file storage services.

- Smooth and responsive user interface with React Native and Expo.

- Utility-first styling with NativeWind.
## Getting Started
To get started with the Aeria frontend, follow these steps:

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/rr789451/Aeria.git

2. Install the required dependencies:

    ```bash
    npm install

3. Start the server:

    ```bash
    expo start

4. The application will be accessible through the **QR Code** provided in the terminal.
    
## Project Structure

The project follows a common Expo project structure:

- **app/index.jsx**: Entry point to the app with an onboarding screen.

- **app/_layout.jsx**: Creates a layout for the application.

- **app/(auth)**: Contains the authentication screens for the application.

- **app/(tabs)**: Individual screens of the app (e.g., Home, Profile, Upload).

- **assets/**: Images, videos, and other static assets.

- **components/**: Reusable UI components used throughout the app.

- **constants/**: For global usage of static assets.

- **context/**: Enabling data sharing and functions across components using React's Context API.

- **lib/**: Route definitions for API endpoints.
## Technologies Used

- ***React Native***:  Framework for building native apps using React.

- ***Expo***: Platform for developing, building, and deploying React Native apps.

- ***Appwrite***: Open-source backend server for managing authentication, database, and file storage.

- ***Expo-Router***: Handles navigation and routing in the app, offering a file-based system that simplifies defining and managing routes in Expo projects.

- ***NativeWind***: Utility-first CSS for React Native, making it easy to style components.

## Appwrite Integration

**Aeria** integrates with Appwrite for the following functionalities:

- ***Authentication***: User registration, login, and session management.

- ***Database***: Storing user and video metadata.

- ***File Storage***: Uploading and retrieving video files.
## Support

For support, email rr789451@gmail.com.


## Badges

[![Apache License 2.0](https://img.shields.io/badge/License-ApacheLicense2.0-green.svg)](https://choosealicense.com/licenses/apache-2.0/)

[![Expo](https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white)](https://docs.expo.dev/)

[![React Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactnative.dev/docs/getting-started)

[![NativeWind](https://img.shields.io/badge/NativeWind-000000?style=for-the-badge&logo=wind&logoColor=white)](https://nativewind.dev/)

[![Appwrite](https://img.shields.io/badge/Appwrite-F02E65?style=for-the-badge&logo=appwrite&logoColor=white)](https://appwrite.io/docs)
