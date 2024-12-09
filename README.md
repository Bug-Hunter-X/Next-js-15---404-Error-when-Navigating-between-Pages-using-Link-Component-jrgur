# Next.js 15 - Routing Issue

This repository demonstrates a routing issue encountered in a Next.js 15 application.  When navigating from the home page to the about page using the built-in Link component, a 404 error occurs. 

The issue seems to stem from a problem with Next.js resolving the route to '/about'. The '/about' page is correctly defined in the `/pages` directory. 

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the home page (http://localhost:3000/).
5. Click the link to navigate to the '/about' page.

**Expected Result:** The about page should be displayed.

**Actual Result:** A 404 error is displayed. 

## Potential Causes:

* Incorrect page configuration
* Issues with Next.js routing in version 15
* Missing configuration or plugins

This repository provides a minimal reproducible example to help identify and fix the root cause of the issue. 