# HelloWorld

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.4.

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

## Notes
### Dependencies:
Prereq: Install Brew (download pkg from official site)
1. Install Node: brew install node
3. Install Typescript: npm install -g @angular/cli

### To create a new project:
Terminal: ng new <project_name>

### To run instance of created Angular project:
ng new hello-world
cd hello-world
ng serve

After running, spin up the application on the browser by navigating to http://localhost:4200/

### How to resolve:
Problem: "Error: This command is not available when running the Angular CLI outside a workspace."
Solution: navigate to root folder where project files are defined then re-run command