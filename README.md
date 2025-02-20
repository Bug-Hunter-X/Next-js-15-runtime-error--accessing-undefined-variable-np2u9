# Next.js 15 Runtime Error: Accessing Undefined Variable

This repository demonstrates a runtime error that can occur in Next.js 15 when accessing an undefined variable within a page component.  The error occurs because the variable `undefinedVariable` is used in `pages/about.js` without being declared or assigned a value.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory: `cd nextjs-undefined-variable`
3. Install dependencies: `npm install`
4. Run the development server: `npm run dev`
5. Visit the About page: `localhost:3000/about`

You'll observe a runtime error in your browser's console.

## Solution

The solution is to ensure that all variables are properly defined and assigned values before being accessed.  See `aboutSolution.js` for a corrected version of the code.