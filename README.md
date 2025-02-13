## React Router DOM v6 Catch-All Route Issue

This repository demonstrates a common issue encountered when using catch-all routes (`path="*"`) in React Router DOM v6.  The catch-all route is unexpectedly not working as expected.

**Problem:**
The provided example shows a setup where a catch-all route is intended to handle any unmatched routes. However, in this case, it is not working correctly, and the unmatched routes are not correctly handled.

**Solution:**
The solution involves ensuring that the catch-all route is placed correctly within the `Routes` component and that there are no conflicts with other routes.