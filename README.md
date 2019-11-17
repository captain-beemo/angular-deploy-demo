# DeployDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.4.

## deploy on github pages

```text
1.ng build --prod --base-href https://<profile_name>.github.io/<repo_name>/ --deploy-url=https://<profile_name>.github.io/<repo_name>/

2.ngh --dir=dist/<repo_name>

3. .angular-cli.json project name should be the same as <repo_name>

4.  git remote repo should be marked as public too, otherwise, it won't be able to post the project.

```

## this app deploy apps

```Text
1.ng build --prod --base-href https://captain-beemo.github.io/angular-deploy-demo/ --deploy-url=https://captain-beemo.github.io/angular-deploy-demo/

2.ngh --dir=dist/angular-deploy-demo/
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
