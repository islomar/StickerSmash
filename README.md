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


## Notes
Creating a shared value using the `useSharedValue()` hook has many advantages. It helps to mutate a piece of data and allows running animations based on the current value. A shared value can be accessed and modified using the .value property. It will scale the initial value of scaleImage so that when a user double-taps the sticker, it scales to twice its original size. 