# React Native Expo Project Setup

This guide will help you set up and run the project using Expo, a framework that makes building React Native apps easier. Follow these steps to get the project installed and running on your device or simulator.

## Prerequisites

### 1. Install the Latest Version of Node.js

To ensure compatibility, you should have the latest version of Node.js installed. 

- **Recommended:** Use `nvm` (Node Version Manager) to install and manage Node.js versions. If `nvm` is not installed, follow these steps:
  - **Install nvm** (macOS/Linux):
    ```bash
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
    source ~/.bashrc
    ```
  - **Install the latest Node.js**:
    ```bash
    nvm install node
    nvm use node  # Activate the latest version
    ```

- **Verify Node.js and npm Installation**:
    ```bash
    node -v
    npm -v
    ```

### 2. Install Expo CLI

To create and run Expo projects, install the Expo CLI globally:
```bash
npm install -g expo-cli
```

Verify the installation:
```bash
expo --version
```

### 3. Install Expo Go on Your Mobile Device

To preview your project on a mobile device, install **Expo Go** from the App Store (iOS) or Google Play (Android).

- [Download Expo Go for iOS](https://apps.apple.com/us/app/expo-go/id982107779)
- [Download Expo Go for Android](https://play.google.com/store/apps/details?id=host.exp.exponent)

### Note for iOS Users:
If you're using an iPhone, ensure:
- Your Mac and iPhone are connected to the **same Wi-Fi network**.
- This allows Expo to communicate with your phone and deliver the app preview.

## Project Setup

### 1. Clone the Repository

Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Project Dependencies

In the project directory, install the required dependencies:
```bash
npm install
```

### 3. Start the Project

To start the development server, run:
```bash
expo start
```

This command will open Expo Dev Tools in your browser, displaying a QR code.

## Running the App on Your Device

### 1. Using Expo Go (iOS & Android)

- **iOS:** Open the **Expo Go** app on your iPhone and scan the QR code shown in the Expo Dev Tools (browser window).
- **Android:** Open the **Expo Go** app on your Android device and scan the QR code.

### 2. Using iOS Simulator (macOS Only)

If you’re using macOS, you can open the app on an iOS simulator:

- Run the following command in the terminal:
  ```bash
  expo start --ios
  ```
- This will open the project in the iOS simulator if you have Xcode installed.

## Troubleshooting

- **Same Wi-Fi Network:** Ensure that both your computer and mobile device are on the same Wi-Fi network if you are running the app on Expo Go.
- **Connection Issues:** Restart Expo Go on your device or the development server if you encounter connection issues.

## Additional Resources

For more detailed information, visit the official Expo documentation:
- [Getting Started with Expo](https://docs.expo.dev/get-started/installation/)
