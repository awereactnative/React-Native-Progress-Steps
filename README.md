# React-Native-Progress-Steps
# Introduction

A simple and fully customizable React Native component that implements a progress stepper UI. Each steps content is displayed inside of a customizable ScrollView.
Fully customizable buttons are displayed at the bottom of the component to move between steps.

# Demo

![video__3_](https://user-images.githubusercontent.com/86215353/181424261-fbce4cd7-e153-4d65-a696-eaad997dd7d0.gif)


# Installation
```
npm install --save react-native-country-picker-modal
```

# Example
```js

import * as React from 'react';
import { View, StyleSheet } from 'react-native';
import Constants from 'expo-constants';
import CountryPicker from 'react-native-country-picker-modal';

export default class App extends React.Component {
  render() {
    return (
      <View style={styles.container}>
        <CountryPicker 
          withEmoji
        />
      </View>
    );
  }
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
    paddingTop: Constants.statusBarHeight,
    backgroundColor: '#ecf0f1',
    padding: 8,
  },
});

```

# Tutorial

Coming Soon...
