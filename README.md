# BusyBee

A React Native app built with [Expo](https://expo.dev).

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Expo Go](https://expo.dev/go) app on your iOS or Android device (for development)

### Installation

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm start
   ```

## Running the App

| Platform | Command |
|----------|---------|
| Android  | `npm run android` |
| iOS      | `npm run ios` |
| Web      | `npm run web` |

After running `npm start`, you can:
- Scan the QR code with the **Expo Go** app on your device
- Press `a` to open on an Android emulator
- Press `i` to open on an iOS simulator (macOS only)
- Press `w` to open in the browser

## Project Structure

```
BusyBee/
├── assets/          # Images, icons, and other static assets
├── App.tsx          # Root application component
├── index.ts         # Entry point
├── app.json         # Expo configuration
├── tsconfig.json    # TypeScript configuration
└── package.json     # Dependencies and scripts
```

## Tech Stack

- [Expo](https://expo.dev) ~57
- [React Native](https://reactnative.dev) 0.86
- [React](https://react.dev) 19
- [TypeScript](https://www.typescriptlang.org/)

## Learn More

- [Expo documentation](https://docs.expo.dev/)
- [React Native documentation](https://reactnative.dev/docs/getting-started)
- [Expo Router](https://docs.expo.dev/router/introduction/)