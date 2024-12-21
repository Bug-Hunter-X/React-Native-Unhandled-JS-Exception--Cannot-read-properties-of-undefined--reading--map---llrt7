# React Native Unhandled JS Exception: Cannot read properties of undefined (reading 'map')

This repository demonstrates a common error in React Native applications: attempting to access a property of an undefined object.  Specifically, the error "Cannot read properties of undefined (reading 'map')" occurs when trying to use the `.map()` method on an array that hasn't been loaded yet or is undefined.

The `bug.js` file showcases the problematic code.  The `bugSolution.js` demonstrates how to fix this using optional chaining and nullish coalescing.