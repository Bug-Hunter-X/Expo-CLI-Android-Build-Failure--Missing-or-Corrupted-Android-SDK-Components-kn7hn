# Expo CLI Android Build Failure: Missing or Corrupted Android SDK Components

This repository demonstrates a bug encountered when building an Android APK using the Expo CLI. The build process fails due to issues with missing or corrupted Android SDK components, specifically related to build-tools or platform-tools.

## Bug Description

The Expo CLI build process terminates with an error indicating problems with the Android SDK.  The error is not consistently reproducible and can vary across different development environments.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `expo prebuild` (or run your usual build command).
4. Observe the build failure. 

## Solution

The solution involves verifying and repairing the Android SDK installation.  This can include:

* Updating the Android SDK Build-Tools to the latest version.
* Updating the Android SDK Platform-Tools to the latest version.
* Reinstalling or repairing the entire Android SDK.
* Checking for issues with environment variables related to the Android SDK.

See the `bugSolution.js` file for a more detailed description of this process.