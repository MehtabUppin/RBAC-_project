# Role-Based Authentication System - Frontend
This is the frontend of the Role-Based Authentication System, built with React. It interacts with a Spring Boot backend to handle user authentication, registration, and role-based access control.

## Table of Contents
- Project Overview
- Features
- Prerequisites
- Installation
- Environment Variables
- Usage
- Testing
- Deployment
- Contributing
- License


## Project Overview
The frontend provides a user interface for the Role-Based Authentication System. Users can:

- Register for an account
- Log in to access protected areas of the app
- Access content based on their assigned roles (e.g., admin, user)
## Features
- User Registration and Login: Register a new account and log in to access the application.
- Role-Based Access: Access specific features or pages based on user roles.
- JWT Authentication: Secure authentication using JSON Web Tokens.
- Responsive Design: Optimized for both desktop and mobile devices.
  
## Prerequisites
Make sure you have the following installed:

- Node.js (v14 or later): Download here
- npm (comes with Node.js): Check with npm -v
- Installation
- Clone the Repository:

```
bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
git checkout frontend
```
Navigate to the Frontend Directory (if not in a separate branch):

```
bash
Copy code
cd rbac-frontend
```
### Install Dependencies:

```
bash
npm install
```
## Environment Variables
Set up environment variables in a .env file in the rbac-frontend root directory. The variables below are required:

```
env
REACT_APP_API_URL=http://localhost:8080/api
```
REACT_APP_API_URL: URL where the backend is hosted. For local development, this is typically http://localhost:8080/api.

Note: Ensure the .env file is included in .gitignore to prevent exposing sensitive information in version control.

## Usage
Run the Application:
```
bash

npm start
The application will start on http://localhost:3000.
```

Login/Register:

- Open http://localhost:3000 in your browser.
- Register a new user account or log in with an existing account to test the authentication system.
- Based on user roles, explore available features to verify role-based access.
  
## Testing
To run tests, use the following command:
```
bash
npm test
```
This project uses Jest and React Testing Library for unit and component tests.

## Deployment
To build the app for production, run:
```
bash
npm run build
```
This command will bundle your app into the build folder. You can then deploy it to a static site host like Netlify, Vercel, or GitHub Pages.

## Contributing
Contributions are welcome! Please follow these steps:

Fork the Repository
Create a New Branch:
```
bash
Copy code
git checkout -b feature-name
```
Make Changes and Commit:
```
bash
git commit -m "Add new feature"
```
Push to Your Branch:
```
bash

git push origin feature-name
```


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

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
