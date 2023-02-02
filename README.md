# anurag-maravi-vue

This project is deployed on firebase. Please read the steps to deploy it on firebase.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## Deployment setup
To install of the Firebase CLI (Command Line Interface) you should have Node.js and npm already installed on your machine.

Now, open you command prompt and install the Firebase CLI via npm:
```
npm install -g firebase-tools
```
This installs the firebase command globally, which we’ll make use of to deploy your Vue Application to Firebase Hosting.
### Update your firebase project name

Update your project on `.firebaserc` file which is located on the root directory.

It’s the time to use your project id. Just replace the `your-firebase-project-id` with your project id value.

### Deploying your Application

To deploy your application, you need first to connect your local machine to your Firebase account and obtain access to your Firebase projects. To do so, run:
```
firebase login
```
Once you successfully logged in, the following success message you’ll be displayed.

Now, from the root of your project directory, run the following command to deploy your application:
```
firebase deploy
```