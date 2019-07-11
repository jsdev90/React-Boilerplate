# React Boilerplate

React front-end app.

## Guidelines

- Keep all file/folder names lowercase. For multiple words in a name, use-hyphens.
- Use the `.jsx` file extension for all files which contain JSX code.
- Prefer functional components over class components.
- Avoid using state in small components. Never use state in basic UI components - take props instead.
- Always use clear self-documenting variable names instead of short names, i.e. use "frameNumber" instead of "fnum", and use "activeColumn" instead of "col".
- Do not extract code into a separate function unless it will be used more than once.

## Scripts

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.