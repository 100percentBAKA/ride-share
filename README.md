# Ride Share

## Tech Stack Used

### Client-Side:
- **React Native**: For building the cross-platform mobile application.
- **Expo**: For managing the development workflow.
- **TypeScript**: For type safety and cleaner code.

### Server-Side:
- **Node.js**: For building the backend API.
- **Express.js**: For creating RESTful endpoints.
- **MongoDB**: As the primary database to store application data.
- **Socket.IO**: For real-time communication between the app and the server.

---

## Overview

The Ride Share app connects captains (drivers) and customers seamlessly through a simple and intuitive interface. Customers can book rides, track their captains in real-time, and enjoy a hassle-free ride-sharing experience. Captains can accept rides, manage their schedules, and track customer locations for efficient pickups.

Key features:
- Real-time ride tracking.
- Role-based functionalities for captains and customers.
- Draggable map interface for selecting pickup and drop locations.
- Secure authentication and error handling.

---

## Installation

### Prerequisites:
1. Ensure **Node.js** and **npm** (Node Package Manager) are installed on your system.
2. Install **MongoDB** and start the database server.

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/100percentBAKA/ride-share.git
   cd ride-share
   ```

2. Extract the `server.rar` file into the `server` directory:
   ```bash
   cd server
   ```

3. Install server dependencies:
   ```bash
   npm install
   ```

4. Start the backend server:
   ```bash
   npm run start
   ```

5. Navigate to the `client` directory:
   ```bash
   cd ../client
   ```

6. Install client dependencies:
   ```bash
   npm install
   ```

7. Start the client application:
   ```bash
   npx expo start
   ```

---

## Usage

### Running the App:

1. Download the build APK from the [expo build](https://expo.dev/accounts/adarshgs/projects/ridesharingapp/builds/de3a1a24-f8a4-4ac4-873f-ccf9a43396cf). 

2. Install the APK on your Android device.

3. Run the application using Expo:
   ```bash
   npx expo run
   ```
   
4. The APK will automatically detect the Expo instance and load the application.

---
