# codvid-app
## Step 1: Set up environment
following instructions on https://reactnative.dev/docs/environment-setup
* Development OS: macOS  
Target OS: iOS  
* Install dependencies: Node, Watchman
```
brew install node
brew install watchman
```
* Download Xcode from App Store and install command line tools and iOS Simulator in Xcode
* install CocaPods
```
sudo gem install cocoapods
```
## Step 2: Build HelloApp
following this tutorial https://reactnative.dev/docs/tutorial
* create a project called HelloApp using EXPO CLI command line
```
npm install -g expo-cli
npx react-native init HelloApp
```
* Modifying app  
open App.tsx and paste:
```
import React from 'react';
import { Text, View } from 'react-native';

function HelloWorldApp() {
  return (
    <View
      style={{p
        flex: 1,
        justifyContent: "center",
        alignItems: "center"
      }}>
      <Text>Hello, world!</Text>
    </View>
  )
}
export default HelloWorldApp;
```
* Run HelloApp
```
cd HelloApp
npm start
```
You can choose to run on iOS simulator or scan the QR code to run on phone(need to previously download Expo Client app on phone)
