
- You should use class binding to toggle some class or bind to hidden attribute when there's a toggle that will happen in the runtime as it's not manipulating the DOM unlike `@if` which changes the DOM structure so you shouldn't use it when it will be toggled a lot in the runtime as it will effect the performance badly.
***
- We can't use two structural directive on the same HTML element .. to work around that you might consider using `ng-container`.
***
