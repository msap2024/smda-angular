## Angular development
# HelloWorld

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.2.

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


Tools needed -  NPM, MAven Gradle

NPM - Angular Application

This guide will help you to build Angular application through the Angular CLI

Pre requisites:
	1.	Node.js
	2.	GitBash or macOS Terminal
	3.	IDE - VS Code Common
	4.	DAA CLI
Local Development setup

Install NPM locally
$ brew install npm
npm verison 
{
  npm: '9.5.0',
  node: '19.7.0',
  acorn: '8.8.2'

Creating an App

$npm install -g @angular/cli

npm WARN deprecated @npmcli/move-file@2.0.1: This functionality has been moved to @npmcli/fs

added 233 packages in 7s

27 packages are looking for funding
  run `npm fund` for details
npm notice 
npm notice New minor version of npm available! 9.5.0 -> 9.6.1
npm notice Changelog: https://github.com/npm/cli/releases/tag/v9.6.1
npm notice Run npm install -g npm@9.6.1 to update!
npm notice

ng --version
Node.js version v19.7.0 detected


$ng new hello-world - this will generate an Angular application with necessary npm packages. Press enter to accept the default options.

Step2.
Change to the created folder. This should match whatever you name your bitbucket repository

Cd hello-world

See the app in your browser

Ng serve –open
