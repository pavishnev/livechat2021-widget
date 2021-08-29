# Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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

# Gh pages deploy angular app

## First install special package
npm install -g angular-cli-ghpages

## Second build your priject with parameter
ng build --prod --base-href "https://(username).github.io/(repository_name)"
Example for my project:
ng build --prod --base-href "https://pavishnev.github.io/livechat2021-pages/#/"

## Third deploy your project from the directory, where you built the prod version

 ngh --dir dist/(your_dist_folder_name)
Example for my project:
  ngh --dir dist/frontend