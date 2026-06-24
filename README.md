# Essential Space

Essential Space is a React Native app built with the React Native Community CLI. It includes navigation, file/document handling, image picking, clipboard access, networking, and local state management.

## Features

- React Native 0.85 + TypeScript
- Navigation with React Navigation
- Clipboard support
- Document and image picking
- File system access
- SVG support
- Local state management with Zustand
- API requests with Axios

## Prerequisites

Before running the app, make sure you have completed the official React Native environment setup:

- [React Native Environment Setup](https://reactnative.dev/docs/set-up-your-environment)

You will also need:

- Node.js `>= 22.11.0`
- npm or Yarn
- Xcode for iOS development
- Android Studio for Android development
- CocoaPods for iOS dependencies

## Installation

Install dependencies from the project root:

```sh
npm install
```

If you use Yarn:

```sh
yarn install
```

For iOS, install Pods after dependency updates:

```sh
bundle install
bundle exec pod install
```

## Running the app

Start the Metro bundler:

```sh
npm start
```

Or with Yarn:

```sh
yarn start
```

### Android

In a second terminal, run:

```sh
npm run android
```

Or with Yarn:

```sh
yarn android
```

### iOS

In a second terminal, run:

```sh
npm run ios
```

Or with Yarn:

```sh
yarn ios
```

## Available scripts

- `npm start` — start the Metro bundler
- `npm run android` — build and run the Android app
- `npm run ios` — build and run the iOS app
- `npm run lint` — run ESLint
- `npm test` — run the test suite

## Project structure

The app follows the standard React Native project layout. The main entry point is typically `App.tsx`.

## Development tips

- Save changes to use Fast Refresh during development.
- If the app behaves unexpectedly, try reloading the simulator/emulator.
- For native dependency changes, reinstall CocoaPods on iOS.

## Troubleshooting

If you run into issues:

- Confirm your environment matches the React Native setup guide
- Make sure Metro is running
- Reinstall dependencies if native modules fail to build
- Run CocoaPods again for iOS if native dependencies changed

## Learn more

- [React Native Documentation](https://reactnative.dev/docs/getting-started)
- [React Native Blog](https://reactnative.dev/blog)
- [CocoaPods Getting Started](https://guides.cocoapods.org/using/getting-started.html)
