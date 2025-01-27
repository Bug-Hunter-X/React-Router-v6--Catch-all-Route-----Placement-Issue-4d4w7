# React Router v6 Catch-all Route Placement

This repo demonstrates a common issue in React Router v6 related to the placement of the catch-all route (`*`).  When the catch-all route is not placed last, it can prevent other routes from being matched correctly. This leads to unexpected 404 errors or incorrect component rendering.  The solution shows the proper placement of the catch-all route to resolve the issue.