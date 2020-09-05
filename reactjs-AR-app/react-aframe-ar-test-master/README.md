This demo is a basic approach to implement AR.js with aframe.js into a React app.

## Basic setup

The aframe.js and aframe-ar.js must be in the public folder and should be imported in the `<head></head>` section of the `index.html` file in this way:

```html
<script src="%PUBLIC_URL%/js/aframe.js"></script>
<script src="%PUBLIC_URL%/js/aframe-ar.js"></script>
```

alternatively you can import them from the CDN network:

```html
<script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.6.2/aframe/build/aframe-ar.js"></script>

```

Minified version of the libs are in place too.
Used **1.6.2** version of aframe-ar.js.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

### Before starting
You need to install the node modules on the project in a console run:

`npm install`

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

