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

Add tailwind.config.js and screens, components folders to projects., [More Info]([https://www.nativewind.dev/guides/babel](https://www.nativewind.dev/quick-starts/expo)).
```
npm i nativewind
npm i --dev tailwindcss
npx tailwindcss init

// tailwind.config.js
module.exports = {
- content: [],
+ content: ["./App.{js,jsx,ts,tsx}", "./screens/**/*.{js,jsx,ts,tsx}", "./components/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

// babel.config.js
module.exports = function (api) {
  api.cache(true);
  return {
    presets: ["babel-preset-expo"],
+   plugins: ["nativewind/babel"],
  };
};
```

## Install React Navigation , [More Info]([https://www.nativewind.dev/guides/babel](https://reactnavigation.org/docs/getting-started)).
```
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack
```

## Heroicons in React Native
```
npm i react-native-heroicons
```
