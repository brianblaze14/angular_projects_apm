# APM

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.2.

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


Overview

1) Components
2) Templates, data binding & Directives
3) Services & Dependency Injection
4) HTTP and observables
5) Navigation and routing
6) Angular CLI

Angular is a javascript framework for building client-side applications using HTML, CSS and Javascript

Why?
1) Expressive HTML
2) Powerful Data Binding
3) Modular By Design
4) Built-in Back-End Integration

New Angular,
1) Built for speed
2) Modern
3) Simplified API
4) Enhances Productivity

Anatomy
1) Consist of Components and a Service Layer
2) Each Components consist of Template which is the HTML for the user interface, Then a class which consist of the Properties of the data elements for use in the view and also the Methods which performs the actions for the views with the button click, Then the MetaData additional information of the component to the angular
3) Root Angular Module makes a cohesive bonds of functionalities using the components
4) Feature Angular Module for specific functionalities

Assitance: https://blogs.msmvps.com/deborahk/
https://github.com/DeborahK?tab=repositories


Architecture of the ACME Product Management

index.html--> APP Component,Product Data Service --> Welcome Component,Product List Component, Product Detail Component --> Star Component


Selecting a language
1) JS or the ECMAScripts, ES3, ES5, ES2015(It must be transpiled)
2) TypeScript-Superset of Javascript, Strong typing , Great IDE tooling, Strong typed

Typescript
1) Superset of the javascript
2) Extension *.d.ts
3) Class based object orientation is implemented

Type Script more practicing: https://www.typescriptlang.org/play/

Editor: Visual Studio Code

Setting up the environment: Download the npm in the system(Node Package Manager), NPM is basically a command line utility, It helps in installing the libraries, packages and applications/Download from the node.js website

Setting up the angular application: 
1) Create an application folder
2) Add package definition and configuration files
3) Install the packages
4) Create the app's Angular Module
5) create the main.ts file
6) create the host Web page (index.html)

Angular CLI commands repository:https://github.com/angular/angular-cli

1) Install the app from the github repo:https://github.com/DeborahK/Angular-GettingStarted/tree/master/APM-Start
2) After the installation import the code in the VS Code editor
3) Open the terminal by using the command CTRL+`
4) Run the command npm -v and the version should be above 6.9.0
5) Run the command npm install to import the packages from the package.json to the node-modules folder(Note npm install @angular/cli for the ng commands to work
Path to set in the env are:
C:\Users\144273\AppData\Local\Programs\node-v12.13.1-win-x64
C:\Users\144273\AppData\Roaming\npm\node_modules\@angular\cli\bin
C:\Users\144273\AppData\Roaming\npm\node_modules\.bin)
6) Run the command 'npm start'

Module

Angular JS modules helps in resolving the namespaces and the code organisation issue
Module is a file and it is standard set by the typeScript Modules and the ES 2015 Module
Angular also has the feature for the angular modules

ES2015 implementation
Create a product.ts file with the syntax
extract class Product{
}

import the package the syntax is
import { Product } from './product'