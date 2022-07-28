# Angular Practice

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.0.

## Pre-commit hooks

Install husky to orchestrate pre-commit actions.

`npm install -D husky`

add prepare script to set up husky directory

`npm set-script prepare "husky install"`

run `npm run prepare` to setup husky.

To add a new hook run `npx husky add .husky/pre-commit "your npm run script goes here"`

For example, to add unit tests before each commit you write the command will go as follow

`npx husky add .husky/pre-commit "npm test"`

now before any commit `npm test` will run.

Additionally if you take a look at `package.json` line 10, the `setup_app` will install the needed dependencies and will setup husky.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

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
