# React Native FlatList Performance Bug

This repository demonstrates a common performance issue in React Native's `FlatList` component when dealing with complex item renderers and large datasets. The bug manifests as slow scrolling, dropped frames, and potential data inconsistencies due to improper state management and network requests within the `renderItem` function.  The solution focuses on optimizing the item renderer to improve performance and address data inconsistencies.  See the `bug.js` file for the problematic code and `bugSolution.js` for the optimized version.

## Setup

1. Clone the repository.
2. Run `npm install` or `yarn install`.
3. Run the app using a React Native simulator or device.