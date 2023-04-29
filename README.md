# react-native-delivery
create delivery application using react native.

## Creating a project
```
npm i -g expo-cli      
npx create-expo-app delivery
```

use "sudo" to access the root.

## Install Tailwindcss
```
npm install react-native-tailwindcss
```

Add tailwind.config.js, [More Info](https://www.nativewind.dev/guides/babel).
```
// tailwind.config.js
module.exports = {
  content: [
    "./screens/**/*.{js,ts,jsx,tsx}",
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  // ...
};
```
## Install React Navigation
```
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
```

## Heroicons in React Native
```
npm i react-native-heroicons
```
