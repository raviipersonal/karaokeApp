# All Senoria Karaoke App

A React Native karaoke app that allows users to sing along with the "All Senoria" track.

## Features

- Real-time audio recording from device microphone
- Background music playback
- Volume control for background track
- Modern and intuitive UI
- Permission handling for microphone access

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Add the background track:
- Place your 'all_senoria.mp3' file in the android/app/src/main/res/raw directory

3. For Android:
```bash
npx react-native run-android
```

4. For iOS:
```bash
cd ios
pod install
cd ..
npx react-native run-ios
```

## Required Permissions

- Android: RECORD_AUDIO permission
- iOS: Microphone permission

## Dependencies

- react-native-sound: For audio playback
- react-native-audio-record: For microphone recording
- @react-native-community/slider: For volume control
- react-native-permissions: For permission handling

## Usage

1. Launch the app
2. Grant microphone permissions when prompted
3. Press "Start Karaoke" to begin recording and playing the background track
4. Adjust the background music volume using the slider
5. Press "Stop Karaoke" to stop recording and save your performance

## Troubleshooting

If you encounter any issues:

1. Ensure all permissions are granted
2. Check that the background track file is properly placed in the resources directory
3. Make sure all dependencies are properly installed
4. Clean and rebuild the project if necessary
#   k a r a o k e A p p  
 