# AngularReactiveFormsCcpayment

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


### Needs to happen

      Forms need validations
      Forms need messaging to help the user along
      Forms frequently need to change rapidly without having to rewrite a ton of app logic
      Angular has 2 separate and different systems for building Forms
      We can technically implement forms with just what we've covered in this course so far(property binding even handlers)

### Reactive Forms

      Most of the form logic is driven by configuration in a component class file
      More appropriate for complex forms
      Exposes some aspects of the form to us as RxJS Observables
      We have to wire up the ReactiveFormsModule to our App Module to use them

### Template Forms

      Most of the form logic is driven by config in our component template file
      More appropriate for simple forms
      Harder to deal with dynamic forms (adding/removing form elements)
      We have to wire up FormsModule to our App Module to use them


