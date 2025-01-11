# React 19 useEffect Cleanup Function Bug

This repository demonstrates a common bug related to the `useEffect` hook's cleanup function in React 19.  The bug involves incorrect cleanup logic, which can lead to unexpected behavior, such as memory leaks, when a component unmounts.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version.  The issue centers around a misunderstanding or omission of the necessary cleanup function within the useEffect hook, which is required for properly handling side effects and preventing resource leaks when the component is removed from the DOM.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` to install the necessary dependencies.
4. Run `npm start` to start the development server.
5. Observe the console output and see the issues present in the buggy code.
6. Refer to `bugSolution.js` for the corrected implementation.