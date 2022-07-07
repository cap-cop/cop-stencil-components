# components

## cop-stencil

Stencil (https://stenciljs.com/) component library. 

To install dependencies: ``npm install``

To build: ``npm run build``

To run storybook: ``npm run storybook``

Will generate Angular components in project angular-workspace/projects/component-library.

## angular-workspace

Angular components that can be used directly in Angular project.

To install dependencies: ``npm install``

To build: ``npm run build``

## cop-project

Angular project using the Angular components from angular-workspace (generated from cop-stencil).

To install dependencies: ``npm install``

To build: ``npm run build``

To run: ``npm run start``

Includes CSS-Houdini implementation based on online tutorial (https://developer.mozilla.org/en-US/docs/Web/API/CSS_Painting_API)

- Javascript file with paint-logic added via src/assets/worklets/highlightWorklet.js
- Module (highlightWorklet) added via script tag in index.html
- Used in app.component.html/css
