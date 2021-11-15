# Task Tracker app (Angular)

Angular Crash Course 2021 from [Traversy Media](https://www.youtube.com/watch?v=3dHNOWTI7H8&list=WL&index=41&t=3673s).
It includes the Angular ui as well as JSON-server for our mock backend


## Getting Started
To set up a local development-environment:

- Install Node.js: <https://nodejs.org/en/download/>

  Install the version specified in the [`.node-version`](.node-version)-file.  
  To prevent conflicts it is recommended to use a 'version manager'.

  - [`fnm`](https://github.com/Schniz/fnm#readme) (for Windows/macOS/Linux) After installing, run in this directory:

        fnm use

  - [NVM - Node Version Manager](http://nvm.sh/) (for macOS/Linux) After installing, run in this directory:

        nvm install && nvm install-latest-npm

  - After installing, run in this directory:

        nvm use

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Local Development

After this initial set-up, you can start with:

- `npm start` - for client
- `npm run sserver` - for the server

The front-end client should be running at: <http://localhost:4200/>.  
The back-end JSON server at: <http://localhost:3000/>, <http://localhost:3000/api/> .

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
