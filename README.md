# React Native + Expo + TypeScript + Tamagui
This template provides a setup to get React Native working with web, Android, and iOS. Tamagui is set up as the UI library and design system.

To start the app for development (web, Android, iOS):
<pre>
yarn expo start
</pre>
If you encounter problems connecting through Expo Go, add ```--tunnel``` to the end of the command and manually connect

To send standalone app for Android/iOs:
<pre>
yarn expo run:[android/ios] --variant release
</pre>

To build and export final standalone apps:
<pre>
yarn expo export (--platform [<b>all</b>/web/android/ios])
</pre>

To update packages, etc:
<pre>
yarn add [package]
</pre>
