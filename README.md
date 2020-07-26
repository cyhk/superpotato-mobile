# Superpotato (Mobile)

Manage your network and friends by letting superpotato do the job for you! It'll keep track and remind you of when you need to contact your friends and connections.

This project is work-in-progress. Currently, the sign-up and log-in flow is near completion and will be refactored when everything is functional and tested, as there as a great deal of overlap between the two branches. The next goal for this project is to build the user dashboard.

Please note that while this app has been tested on an iOS simulator, it has not yet been tested for Android.

## Setting up mobile development

Follow the instructions on [Getting Started](https://facebook.github.io/react-native/docs/getting-started) in the React Native docs.

## Technologies used

Typescript, React Native

## App Information

### Component Architecture

```
App
├── GetStarted
├─┬ SignUp
│ ├── FirstAndLastName
│ ├── Email
│ ├── PhoneNumber
│ └── OneTimeCode
├─┬ LogIn
│ ├── Email
│ ├── PhoneNumber
│ └── OneTimeCode
└─── Dashboard (to be implemented)
```
