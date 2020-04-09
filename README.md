# Athena

## Overview
Tool for note-taking, progress tracking, and practicing.
Learned material is practiced via re-exposure to taken notes and quiz-like drills.
Current learning apps are focused on explaining material. Athena app is focused on maintaining long term fluency of on both pre-defined learning tracks and on custom user notes.

## Development tools
 - node.js and npm downloadable jointly at nodejs.org
 - firebase CLI via `npm install -g firebase-tools`
 - git downloadable at git-scm.com

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Deployment
 - login to Firebase CLI `firebase login --interactive`
		- the `interactive` option might be required on bash on windows, see https://github.com/firebase/firebase-tools/issues/149
 - make a production build via `ng build --prod`
 - deploy via `firebase deploy`

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Project origins

'Athena' was chosen as placeholder name, until better name and domain is found.

Protote developed in Visual Studio Code on Windows with MinTTY terminal environment.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.0.

The first steps taken:
 - generated new angular project with Angular CLI command `ng new athena`
 - coded sample home page to replace template content
 - setup the project folder as a Visual Studio Code workspace
 - created new GitHub repository `athena`
 - added remote origin `git remote add origin https://github.com/tetourdavid/athena.git`
 - pushed and checked initial commit to verify versioning operations
 - created Firebase project `athena` on a free spark plan
 - added Firebase deploy configuration to codebase via `ng add @angular/fire`
 - checked the new firebase project can be seen in CLI via `firebase projects:list`
 - connected the project folder to Firebase project via `firebase init`
	- see step 5. of https://angular.io/start/start-deployment#hosting-an-angular-app-on-firebase
  - configured as single-page app, all urls directed to `index.html`
 - deployed to firebase
