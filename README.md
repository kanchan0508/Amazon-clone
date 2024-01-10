# Getting Started with Create React App

This project was bootstrapped with [Create React App]https://github.com/kanchan0508/Amazon-using-mern-stack/tree/main

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting
Instead of downloading the entire app before users can use it, code splitting allows you to split your code into small chunks which you can then load on demand.

This project setup supports code splitting via dynamic import(). Its proposal is in stage 4. The import() function-like form takes the module name as an argument and returns a Promise which always resolves to the namespace object of the module.

Here is an example:

moduleA.js
const moduleA = 'Hello';

export { moduleA };
App.js
import React, { Component } from 'react';

class App extends Component {
  handleClick = () => {
    import('./moduleA')
      .then(({ moduleA }) => {
        // Use moduleA
      })
      .catch(err => {
        // Handle failure
      });
  };

  render() {
    return (
      <div>
        <button onClick={this.handleClick}>Load</button>
      </div>
    );
  }
}

export default App;
This will make moduleA.js and all its unique dependencies as a separate chunk that only loads after the user clicks the 'Load' button. For more information on the chunks that are created, see the production build section.

You can also use it with async / await syntax if you prefer it.
For in details you can go here-This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
### Here are some UI page Screenshots-
![signin](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/b54ffaf8-7cf5-4775-9249-fda7eb878be1)
![cart](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/0b07fb25-c316-4c0c-88c6-d366b87184d2)
![sign in page](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/8abda575-39c7-4540-99a2-4aa039515ae8)
![home](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/b094d0b4-4bef-4e55-9909-cc7da3f0e88c)
![amazon](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/294a5603-d104-46bc-b500-2c64f628249b)
![signup](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/315ac84f-7dfd-442
![cart1](https://github.com/kanchan0508/Amazon-using-mern-stack/assets/105898854/e0583c63-34e2-44ad-8efd-c7e5692e691c)
f-9282-7359013141f2)

