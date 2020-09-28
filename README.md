
Click in the link to see a 
[<strong>Live demo</strong>](https://covid-c41af.firebaseapp.com/)


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## How to deploy this app in firebase?

1- Go to https://firebase.google.com/ and access to the console.

2- Create a new project, choose a name and go on!.

3- Install firebase-tool globaly

### `npm install -g firebase-tools`

4- Login to firebase

### `firebase login`

5- Init firebase

### `firebase init`

#### choose hosting option!

This will create two files firebase.json and .firebaserc

6- If you do not build the app run

### `npm run build`

7- Deploy to firebase!

### `firebase deploy`
