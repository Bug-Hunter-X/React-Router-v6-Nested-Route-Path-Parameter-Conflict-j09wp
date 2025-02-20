# React Router v6 Nested Route Path Parameter Conflict

This repository demonstrates a subtle bug in React Router v6 related to nested routes and path parameters.  Specifically, a nested route with a path parameter will not function as expected if it's a child of another route that also uses a path parameter.  This leads to unexpected routing behavior, often resulting in the nested route never matching.

The issue is explained and solved in the included files. The `bug.js` file shows the problem, and `bugSolution.js` provides a corrected version.