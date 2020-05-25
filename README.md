# Get Started

init

```
npx react-native init AwesomeTSProject --template react-native-template-typescript
```

For iOS
```
cd ./AwesomeTSProject/ios && pod install

Analyzing dependencies
Fetching podspec for `DoubleConversion` from `../node_modules/react-native/third-party-podspecs/DoubleConversion.podspec`
Fetching podspec for `Folly` from `../node_modules/react-native/third-party-podspecs/Folly.podspec`
Fetching podspec for `glog` from `../node_modules/react-native/third-party-podspecs/glog.podspec`
Downloading dependencies
Installing CocoaAsyncSocket (7.6.4)
Installing CocoaLibEvent (1.0.0)
Installing DoubleConversion (1.1.6)
Installing FBLazyVector (0.62.2)
Installing FBReactNativeSpec (0.62.2)
Installing Flipper (0.33.1)
Installing Flipper-DoubleConversion (1.1.7)
Installing Flipper-Folly (2.2.0)
Installing Flipper-Glog (0.3.6)
Installing Flipper-PeerTalk (0.0.4)
Installing Flipper-RSocket (1.1.0)
Installing FlipperKit (0.33.1)
Installing Folly (2018.10.22.00)
Installing OpenSSL-Universal (1.0.2.19)
Installing RCTRequired (0.62.2)
Installing RCTTypeSafety (0.62.2)
Installing React (0.62.2)
Installing React-Core (0.62.2)
Installing React-CoreModules (0.62.2)
Installing React-RCTActionSheet (0.62.2)
Installing React-RCTAnimation (0.62.2)
Installing React-RCTBlob (0.62.2)
Installing React-RCTImage (0.62.2)
Installing React-RCTLinking (0.62.2)
Installing React-RCTNetwork (0.62.2)
Installing React-RCTSettings (0.62.2)
Installing React-RCTText (0.62.2)
Installing React-RCTVibration (0.62.2)
Installing React-cxxreact (0.62.2)
Installing React-jsi (0.62.2)
Installing React-jsiexecutor (0.62.2)
Installing React-jsinspector (0.62.2)
Installing ReactCommon (0.62.2)
Installing Yoga (1.14.0)
Installing YogaKit (1.18.1)
Installing boost-for-react-native (1.63.0)
Installing glog (0.3.5)
Generating Pods project
Integrating client project

[!] Please close any current Xcode sessions and use `AwesomeTSProject.xcworkspace` for this project from now on.
Pod installation complete! There are 47 dependencies from the Podfile and 37 total pods installed.
```

Then

```
yarn start

yarn run ios --simulator='iPhone SE (2nd generation)

```

Simulator name get be get from `xcrun simctl list devices`



# ThroubleShooting

## “Invariant Violation: Application AwesomeProject has not been registered” When building for iOS device with static jsbundle

https://stackoverflow.com/questions/29287987/invariant-violation-application-awesomeproject-has-not-been-registered-when-b