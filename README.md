# ApproovDemo App Template
 
## Prerequisites

* Node v16
* Cocoapods (for iOS)
* Xcode (for iOS)
* Android Studio (for Android)

## Setup

* Install node packages by running `npm i`
* Update the configuration by runningn `npm run configure`

## Test with Mendix Cloud

### Android

* Open `android/` in Android Studio
* Run gradle sync (do not upgrade the project or gradle version)
* Build & Run

### iOS

* Install Cocoapods by running `pod install` inside the folder `ios/`
* Open `ios/NativeTemplate.xcworkspace` in XCode
* Fix the signing configuration (you can enable automatic signing)
* Build & Run

## Test locally

* Check out the Mendix project in Studio Pro 9.18.4
* Run locally
* Verify that the runtime is running by opening `http://[RUNTIME_IP]:8080` in the webbrowser of your testphone
* Edit `config.json` and set `"runtimeUrl": "http://[RUNTIME_IP]:8080"` to the IP address of the machine running the runtime from Studio Pro.
* Upad the configuration by running `npm run configure`
* Continue by building & running the iOS or Android app as described above.
