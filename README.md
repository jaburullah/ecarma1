# ecarma
Apartment mobile app IOS/Android 

## Getting Started
clone this repo then do npm install

```
npm install
```
under android folder create a file called local.properties and add the following line. Basically point android sdk folder. 

```
sdk.dir =/Users/{username}/Library/Android/sdk
```

## keystore files
Keep debug.keystore and ercama-key.keystore files under android/app folder



### Android virtual devices
* [virtual devices setup](https://developer.android.com/studio/run/managing-avds) - Create and manage virtual devices



## Run app on Android virtual devices
Virtual device is up and running. Run the following command. This command will install the app on virtual devices

```
react-native run-android
```
