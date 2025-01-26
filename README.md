# Tailwind CSS Classes Not Applied in Component
This repository demonstrates an uncommon bug in Tailwind CSS where styles are not applied to components due to a missing import.

## Bug Description
When using Tailwind CSS classes within a component, make sure to import the necessary Tailwind directives.  Forgetting to do so will result in the classes having no effect.

## How to Reproduce
1. Clone this repository.
2. Navigate to the `bug` directory.
3. Run `npm install` to install dependencies.
4. Run `npm start` to start the development server.
5. Observe that the component does not have the expected styling (red background, padding).

## Solution
The solution is simply to import Tailwind directives. See the `bugSolution` directory for a working example.
