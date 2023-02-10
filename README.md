# ApproovDemo App Template
 
## Prerequisites

* Node v16
* Cocoapods (for iOS)
* Xcode (for iOS)
* Android Studio (for Android)

## Setup

* Install node packages by running `npm i`

## Dev Build

* Edit `config.json` and set `"runtimeUrl": "http://[RUNTIME_IP]:8080"` to the IP address of the machine running the runtime from Studio Pro.
* Upad the configuration by running `npm run configure`

### Android

* Open `android/` in Android Studio
* Run gradle sync (do not upgrade the project or gradle version)
* Build & Run

### iOS

* Install Cocoapods by running `pod install` inside the folder `ios/`
* Open `ios/NativeTemplate.xcworkspace` in XCode
* Fix the signing configuration (you can enable automatic signing)
* Build & Run
