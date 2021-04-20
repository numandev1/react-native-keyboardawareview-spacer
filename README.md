# react-native-keyboardawareview-spacer

[![npm version](https://img.shields.io/npm/v/react-native-keyboardawareview-spacer.svg)](https://www.npmjs.com/package/react-native-keyboardawareview-spacer) [![npm total downloads](https://img.shields.io/npm/dt/react-native-keyboardawareview-spacer.svg)](https://www.npmjs.com/package/react-native-keyboardawareview-spacer.svg)

## Installation

```shell
npm install react-native-keyboardawareview-spacer --save
```

## Usage

```js
import KeyboardAwareViewSpacer from "react-native-keyboardawareview-spacer";

<KeyboardAwareViewSpacer>
  <View>
    <TextInput />
    <Button title="Send" />
  </View>
</KeyboardAwareViewSpacer>;
```

**Expo Snack Example**

https://snack.expo.io/@nomi9995/react-native-keyboardawareview-spacer

## Props

| **Prop**     | **Type**  | **Default** | **Description**                                 |
| ------------ | --------- | ----------- | ----------------------------------------------- |
| `extraSpace` | `number`  | 0           | Extra space between the keyboard and your View. |
| `disabled`   | `boolean` | false       | enable or disable.                              |
