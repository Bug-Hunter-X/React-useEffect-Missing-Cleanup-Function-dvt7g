# React useEffect Missing Cleanup Function

This repository demonstrates a common error in React's `useEffect` hook: omitting the cleanup function.  The example showcases an effect that should log a message only once upon component mount, but due to the missing cleanup function, it behaves unexpectedly.  This can lead to memory leaks and performance issues.