# React Native + Expo + TypeScript + Tamagui
This template provides a setup to get React Native working with web, Android, and iOS. Tamagui is set up as the UI library and design system.

To start the app for development (web, Android, iOS):
```
yarn expo start
```
If you encounter problems connecting through Expo Go, add ```--tunnel``` to the end of the command and manually connect

To send standalone app for Android/iOs:
```
yarn expo run:[android/ios] --variant release
```

To build and export final standalone apps:
```
npx expo export (--platform [**all**/web/android/ios])
```

To update packages, etc:
```
yarn add [package]
```
