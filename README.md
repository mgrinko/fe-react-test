# TASK

```
Create a React application for displaying and storing data using https://swapi.dev/ 
and any image searching API (Google, Bing or whatever you want). 
Please, read this document all the way to the end.
```

## _Tech requirements_

0. You may use `create-react-app` (_recommended_) or any other React setup you like. App has to be written using React Hooks API.
1. App must display four tabs that you can switch between: `Planets`, `Persons`, `Starships` and `Saved`.
2. Clicking any of the following tabs [ `Planets`, `Persons`, `Starships` ] displays a list with all items that are provided by Swapi.
3. Clicking any item from the list displays a gallery with unequal rows / columns (a.k.a. "Masonry grid") with images representing chosen item (images are fetched via an image searching API you've chosen).
4. Double-clicking an image saves it to the `Saved` and show a toaster telling about the result of an operation.
5. Clicking the `Saved` tab moves us to the page with all the saved images, which also contains an input field that allows us to filter images by the name.
6. As a result we'd like having a link for a git repository with a task.

## _Data management_

1. For global state management use Redux.
2. For asynchronous operations you may use whatever tool you like (like `redux-thunk`). Using `redux-saga` will be a plus.
3. For connecting Redux you may use `react-redux's "connect"` or hooks or whatever approach you like.
4. Redux store MUST NOT be accessible via `Redux devtools` extension in a production mode.

## _Styling and layouts_

1. Usage of SCSS modules is a MUST. Using SCSS tools like mixins, variables etc will be a plus.
2. All layout should be done using either CSS Grid or CSS Flexbox (using CSS Grid will be a plus).
3. Every image must have an appear transition on mount (we suggest going with _opacity + bottom-to-top slide in_ transition).
4. Adding hover effects will be a plus.
5. Having fancy styling will be a plus.

### _Useful hints_:

1. Use a library or toasters - this will save you a bit of time and efforts.
2. Save not only the image itself, but also some additional data about it (at least a name) - this will help you in filtering.
3. Using some memoization strategies will be a plus.
4. Try making your code clean, readable and maintainable - this will be a HUGE plus.
5. Creating a transition where images appear smoothly one by one (not all at the same time) will be a plus, cuz it looks fancy :)
6. Responsiveness will be a plus
7. Including light and darks theme will be a plus.
8. Creating some functionality which was not stated in a spec but shows your skills may be considered as a plus.
9. Prepare before starting a test work and find a good balance between time spent and a result, as it also may be reviewed.
10. Try making commit messages nice and informative.
