# React Native + Expo + TypeScript + Tamagui
This template provides a setup to get React Native working with web, Android, and iOS. Tamagui is set up as the UI library and design system.

To start the app for development (web, Android, iOS):
<pre>
yarn expo start
</pre>
If you encounter problems connecting through Expo Go, add ```--tunnel``` to the end of the command and manually connect

To send standalone app for Android/iOS:
<pre>
yarn expo run:[android/ios] --variant release
</pre>
If you encounter an error saying "not able to find file" or something along the lines, shorten the path to the project because smth goes over Windows' path char limit

To build and export final standalone apps (for example to build for website):
<pre>
yarn expo export (--platform [<b>all</b>/web/android/ios])
</pre>
If you encounter an error saying "not able to find file" or something along the lines, shorten the path to the project because smth goes over Windows' path char limit

To update packages, etc:
<pre>
yarn add [package]
</pre>
