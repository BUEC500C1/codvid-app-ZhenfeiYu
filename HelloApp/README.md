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
expo init HelloApp
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
expo start
```
You can choose to run on iOS simulator or scan the QR code to run on phone(need to previously download Expo Client app on phone)  
<div align=center><img src="https://github.com/BUEC500C1/codvid-app-ZhenfeiYu/blob/master/pictures/hello_simulator.png"></div>
<div align=center><img src="https://github.com/BUEC500C1/codvid-app-ZhenfeiYu/blob/master/pictures/server.png"></div>
