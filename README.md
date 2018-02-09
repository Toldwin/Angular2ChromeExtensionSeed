# Angular2ChromeExtensionSeed
Seed of a Chrome extension using typescript Angular (09/02/2018, v5.2.0) with angular cli 1.6.8

This project is based on the Google tutorial: https://angular.io/docs/ts/latest/quickstart.html, adds Angular-CLI typical project NPM managment and the extension CSP rights to allow Angular 2 execution. 

# Requirement
Install NPM (with node) for your platform: https://nodejs.org/download/release/latest/

Get the project localy: git clone https://github.com/Toldwin/Angular2ChromeExtensionSeed.git

Install the project module dependencies, go in the project folder : npm install

# Use
To launch/use the extension directly in your browser as a standard web page, in the project folder use: ng serve

To use project as an extension in Chrome: 
- Build de project : ng build
- Open Chrome preferences
- Choose "Parameters"
- Select "Extensions" on the left
- Activate "developer mode" on the top right
- Select "Load none packaged extension"
- Select the .../Angular2ChromeExtensionSeed/dist folder

The extension shown with a little angular 2.0 icon. If you click on it it should show you "loading..." and next "App working".

You are now free to modify this seed project to make the wonderful extension you like.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Deploying to Github Pages

Run `ng github-pages:deploy` to deploy to Github Pages.

## Further help

To get more help on the `angular-cli` use `ng --help` or go check out the [Angular-CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
