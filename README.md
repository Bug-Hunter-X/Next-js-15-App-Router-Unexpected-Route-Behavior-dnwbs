# Next.js 15 App Router Unexpected Route Behavior

This repository demonstrates a bug encountered in Next.js 15's App Router.  The issue involves unexpected routing behavior, potentially resulting in 404 errors or incorrect page rendering. The example showcases a basic setup, but the issue can manifest in more complex applications.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Observe unexpected behavior in the routing or 404 errors on certain routes.  Detailed explanation in `bug.js` and the solution in `bugSolution.js`.

## Solution

A potential solution is discussed in `bugSolution.js` and might involve adjusting the folder structure or configuring route matching rules to address the routing conflict.  This is a common issue when migrating from older Next.js versions or with more complex routing structures.
