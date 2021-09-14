# ToDo

"To Do" web app created using Angular.js generated with Angular CLI](https://github.com/angular/angular-cli) version 12.0.4.
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Overview

Simple web app for managing tasks & chores.

## Getting started

This project requires Node.js

Run `npm install` to install node dependencies.

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Project hierarchy

Root folder:

- Contains project initialization files, .gitignore, src folder & .json folder for dependencies.

E2E folder:

-  e2e tests of the website. It is used to track user behavior on the website while testing.

Src folder:

- Contains files & scripts that make up the app such as index.html, styles.scss, main.ts.

App folder:

- Contains all the components & shared services of the app.

Components:

- edit-todo-dialog: Creating a task (item).
- todo-item: Task item
- todos: List of all task items.
