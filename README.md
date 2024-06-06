# StickerSmash
- [Expo tutorial](https://docs.expo.dev/tutorial/create-your-first-app/)
- https://snack.expo.dev/@expo-team-snacks/image-app?platform=android


## Commands to execute
- `npx create-expo-app StickerSmash --template blank`
- `npx expo install react-dom react-native-web @expo/metro-runtime`
- `npx expo install @expo/vector-icons`
  - After installing any library, restart the development server by running the `npx expo start` command.
- `npx expo install expo-image-picker` 
- `npx expo install react-native-gesture-handler react-native-reanimated`
- `npx expo install react-native-view-shot expo-media-library`
- `npm install dom-to-image`
  - It allows taking a screenshot of any DOM node and turning it into a vector (SVG) or raster (PNG or JPEG) image.


## Notes
- Learn more: https://docs.expo.dev/tutorial/follow-up/
- Creating a shared value using the `useSharedValue()` hook has many advantages. It helps to mutate a piece of data and allows running animations based on the current value. A shared value can be accessed and modified using the .value property. It will scale the initial value of scaleImage so that when a user double-taps the sticker, it scales to twice its original size.
- **Splash screen**:
  - The splash screen is configured by defining a path to the "splash.image" property in the `app.json` file.
  - You can make the splash screen stick around for longer by manually controlling when it is hidden, rather than the default of automatically hiding it as soon as the app is ready.
- Eventually, when you build the app for the app stores, Expo Application Services (EAS) will take the App icon image and create optimized icon for every device. 