# Project Passport
An extensible framework for interactive presentation of unit reviews.

## Contents
This default implementation of this project covers U.S. History from its birth 
to the modern day, per AP US History content guidelines.

## Usage
To see a live sample, go to the [Project Passport site](https://project-passport.firebaseapp.com).

## Installing from source
```bash
$ git clone https://github.com/TheCraftKid/project-passport
```

### Building
This project uses the Yarn package manager to manage most dependencies excluding
Polymer web components (for now). To initialize the environment, run:
```bash
$ yarn
```
This initializes the dependencies for this project's web components

### Testing
To start the local development server that automatically builds upon execution,
run:
```bash
$ yarn start
```
The local server defaults to `localhost:5000`.

It's recommded to use npm-watch in another terminal to automatically build 
after editing a file:
```bash
$ yarn run watch
```

To launch the linter, run:
```bash
$ yarn run lint
```
### Deploying
This performs a build and deploys it to Firebase Hosting using the Firebase 
CLI tools.
```bash
$ yarn run deploy 
```
