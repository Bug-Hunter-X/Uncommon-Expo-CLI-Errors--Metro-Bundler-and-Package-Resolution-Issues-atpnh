# Uncommon Expo CLI Errors: Metro Bundler and Package Resolution

This repository demonstrates an uncommon issue encountered while using Expo CLI, specifically problems with the Metro bundler's ability to resolve modules correctly.  Even with seemingly correctly installed packages, dependency conflicts or misconfigurations can lead to frustrating build failures.

The `expoBug.js` file showcases a simplified example of the problem, while `expoBugSolution.js` provides solutions.

## Reproducing the Bug

1. Clone this repository.
2. `npm install` or `yarn install`
3. Attempt to start the Expo project using `expo start` (You may need to make adjustments to the code in expoBug.js to trigger the specific error).  Observe the bundler errors.

## Solutions

The `expoBugSolution.js` file illustrates how to fix this, focusing on techniques to resolve dependency conflicts, ensuring correct package versions, and confirming proper import paths.  Read through the comments in the solution file for detailed explanations.

## Contributing

Contributions are welcome!