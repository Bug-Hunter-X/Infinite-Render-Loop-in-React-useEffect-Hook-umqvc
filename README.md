# Infinite Render Loop in React useEffect Hook
This repository demonstrates a common React bug: an infinite render loop caused by a missing dependency in the `useEffect` hook.  The `MyComponent` renders infinitely because the effect function is always executed on every render, leading to an infinite loop.  The solution shows how to correctly include dependencies in the `useEffect` hook to prevent this issue.