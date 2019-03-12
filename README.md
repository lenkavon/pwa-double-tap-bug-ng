# Double tap bug 

## Steps to reproduce  
 - on iPhone iOS11.*, iOS12.*  
 - install the PWA app to homescreen [add pwa to homescreen](https://superpwa.com/doc/test-pwa-ios-devices/)  
 - open the app from home - standalone mode  
 - tap the input to open the keyboard  
 - close keyboard  
 - double tap on any free space  

### Behaviour: white panel arives from bottom of the display (probably the 'space' for keyboard)  
### Expected behaviour: zoom or nothing depending on meta tags.  

Repository is deployed on [firebase](https://pwa-double-tap-bug-ng.firebaseapp.com)

# DoubleTapBugNg

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.5.

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
