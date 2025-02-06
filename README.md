# Dart/Flutter Development Environment

This is my simple flutter development for creating mobile cross platform applications.
Originally this is part of my college requirement since we will be working with cross
platform application using Flutter.

## How to create a emulator?

- Install the Emulator Package:
`sdkmanager --install "emulator"`

- Verify the Installation:
`sdkmanager --list`

- Create a New AVD (Android Virtual Device):
`avdmanager create avd --name AndroidDevice01 --package "system-images;android-21;default;x86_64"`

- Start the Emulator:
`emulator -avd AndroidDevice01`