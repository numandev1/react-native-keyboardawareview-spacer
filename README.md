# react-native-keyboardawareview

[![npm version](https://img.shields.io/npm/v/react-native-keyboardawareview.svg)](https://www.npmjs.com/package/react-native-keyboardawareview) [![npm total downloads](https://img.shields.io/npm/dt/react-native-keyboardawareview.svg)](https://www.npmjs.com/package/react-native-keyboardawareview.svg)

## Installation

```shell
npm install react-native-keyboardawareview --save
```

## Usage

```js
import KeyboardAwareView from "react-native-keyboardawareview";

<KeyboardAwareView>
  <View>
    <TextInput />
    <Button title="Send" />
  </View>
</KeyboardAwareView>;
```

**Expo Snack Example**

https://snack.expo.io/@nomi9995/react-native-keyboardawareview

## Props

| **Prop**     | **Type**  | **Default** | **Description**                                 |
| ------------ | --------- | ----------- | ----------------------------------------------- |
| `extraSpace` | `number`  | 0           | Extra space between the keyboard and your View. |
| `disabled`   | `boolean` | false       | enable or disable.                              |
