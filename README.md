# React Router Dom v6 - Unexpected Route Matching

This repository demonstrates an uncommon bug in React Router Dom v6 related to unexpected route matching and rendering issues.  The issue is that routes sometimes don't match correctly and render the wrong components. This is often seen when dealing with nested routes or complex route patterns.  The bug is highlighted and a solution is provided.

## Bug Description:

Routes are not matching as expected leading to incorrect component rendering. The provided example shows a simple setup where the 'About' component should only render when the URL is '/about', but it may render in other cases, or the 'NotFound' may be incorrectly displayed.

## Solution:

The solution provided addresses the route matching issue by ensuring that the routes are defined with the correct path patterns and priorities, using exact matching when needed.