# Expo Camera API Intermittent Freeze Bug

This repository demonstrates a bug encountered while using the Expo Camera API. The camera preview intermittently freezes without any console errors, making debugging challenging. This issue affects different devices inconsistently and the app remains responsive despite the frozen preview.

## Bug Reproduction

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app using Expo Go or EAS Build.
4. Observe the camera preview for intermittent freezing.  The frequency of the freeze may vary.

## Solution

The solution involves adjusting the camera's frame rate and potentially exploring alternative camera libraries if the problem persists. The solution file provides a possible fix.  Further investigation may be needed depending on the device and environment.