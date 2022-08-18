# [PersonalWebsite](https://tomfurlong.github.io/)

Personal website built with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.0.
Can be visited at https://tomfurlong.github.io/
test
## To Start

* Development
`npm ci`
Run `ng serve -o` for a dev server. Navigate to `http://localhost:4200/`. 
The application will automatically reload if you change any of the source files.
* Production using lite-server
`npm install -g lite-server`
`ng build --watch`
`lite-server --baseDir="dist/<project-name>"`
--baseDir="docs" either.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, 
you need to first add a package that implements end-to-end testing capabilities.

## Deployment
[deploy.yml](https://github.com/tomfurlong/tomfurlong.github.io/blob/main/.github/workflows/deploy.yml)
 with help from [Raj](https://github.com/rajitbanerjee) who I constantly annoy with questions.