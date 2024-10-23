# Attendance Management App

This is a React Native application designed to manage attendance for both owners and students. The app allows users to log in and navigate through various screens based on their role (Owner or Student). Owners and students have access to different dashboards, attendance records, and profiles.

## Features

- **Owner View**: Owners can navigate between Home, Dashboard, Attendance, and Profile screens.
- **Student View**: Students can navigate between Home, Dashboard, Attendance, and Profile screens.
- **Login System**: Users are directed to the appropriate interface based on their role (Owner or Student).
- **Role-Based Navigation**: Owners and students have separate tab navigation based on their role.

## Technologies Used

- **React Native**: Mobile app framework.
- **React Navigation**: Navigation for routing and screen management.
- **Expo**: React Native toolchain.
- **Material Icons**: Icons for bottom tab navigation.

## Installation and Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/your-repo/attendance-management-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd attendance-management-app
    ```

3. Install the necessary dependencies:

    ```bash
    npm install
    ```

4. If you haven't already, install Expo CLI:

    ```bash
    npm install -g expo-cli
    ```

5. Run the project:

    ```bash
    expo start
    ```

6. Use a mobile device or an emulator to view the app using the Expo Go app.

## Project Structure

```plaintext
.
├── App.js                 # Main entry point for the application
├── screens/               # Folder for all the app screens
│   ├── LoginScreen.js     # Login screen for user authentication
│   ├── owners/            # Folder for owner-specific screens
│   │   ├── DashboardScreen.js
│   │   ├── AttendanceScreen.js
│   │   ├── ProfileScreen.js
│   │   └── HomeScreen.js
│   ├── students/          # Folder for student-specific screens
│   │   ├── DashboardScreen.js
│   │   ├── AttendanceScreen.js
│   │   ├── ProfileScreen.js
│   │   └── HomeScreen.js
├── assets/                # Folder for any image or media assets
└── README.md              # Project documentation

