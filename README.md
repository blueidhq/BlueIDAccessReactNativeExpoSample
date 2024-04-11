# BlueID Access React Native (Expo) Sample App

This is a sample app that demonstrate the basic usage of BlueID's Access React Native SDK

For more information check our [documentation](https://community.blue-id.com/documentation)

## Getting Started

### Installation

Install NPM packages
   ```sh
   npm install
   ```
   
### Running the app on iOS
To be able to run the app on an iOS device, first you need to install the pods, to do so run `pod install` inside the `/ios` folder

Once pods are installed run to start Metro:
   ```sh
   npm run start
   ```

Then open `/ios/BlueIDAccessRNExpoSample.xcworkspace` with XCode and run the app on your device.

**Important:** To be able to run on a **real device** you'll need to select a developer team on XCode. To change the team open `/ios/BlueIDAccessRNExpoSample.xcworkspace` with XCode and change it on the *Signing & Capabilities* tab.
 
### Running the app on Android
To start Metro run
   ```sh
   npm run start
   ```

// TODO: run android app
