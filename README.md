# Firebase Realtime Database - Null Pointer Exception on Nested Data Access

This repository demonstrates a common error when working with nested data in Firebase Realtime Database snapshots.  The `bug.js` file shows code that attempts to access deeply nested properties without proper null checks, leading to a null pointer exception (or similar error depending on the environment). The `bugSolution.js` file provides a corrected version that includes robust null checks to prevent the error.

This is a crucial issue to address to prevent unexpected crashes in your application.  The solution involves progressively checking for null values at each level of the nested data before attempting to access deeper properties.
