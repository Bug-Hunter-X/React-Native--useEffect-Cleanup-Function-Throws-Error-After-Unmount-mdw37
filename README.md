# React Native useEffect Cleanup Function Error

This repository demonstrates a common error in React Native applications related to the `useEffect` hook and its cleanup function.  The issue arises when the cleanup function attempts to access or modify state or props after the component has been unmounted, leading to unexpected errors and potential crashes.

The `useEffectCleanupBug.js` file showcases the buggy code.  The `useEffectCleanupSolution.js` demonstrates the corrected code and explains how to prevent this issue.

## Steps to Reproduce

1. Clone the repository.
2. Run the buggy example (`useEffectCleanupBug.js`): you'll see an error in the console.
3. Compare the buggy example to the corrected example (`useEffectCleanupSolution.js`)
4. Run the corrected example to see how the issue is resolved.