# React Native Deprecated componentWillMount

This repository demonstrates a common error in React Native applications: the use of the deprecated `componentWillMount` lifecycle method.

## Problem

The `componentWillMount` lifecycle method is deprecated in React 16+. Using it can lead to unexpected behavior and errors.  The code in `bug.js` exemplifies this incorrect usage.

## Solution

The recommended approach is to use the `componentDidMount` lifecycle method instead. `bugSolution.js` provides the corrected implementation.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` (or `npx react-native run-ios`) to run the application on an emulator or device.

## Note

Always refer to the official React Native documentation for the most up-to-date best practices and lifecycle method usage.