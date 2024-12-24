# React useEffect Hook Memory Leak

This repository demonstrates a common error in React applications involving the `useEffect` hook: forgetting to include a cleanup function to prevent memory leaks.  The example shows a component that uses `setInterval` to update a counter every second.  Without a cleanup function, the interval continues to run even after the component is unmounted, leading to memory leaks.

The solution demonstrates the correct way to use `useEffect` with cleanup function.