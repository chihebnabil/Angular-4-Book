Angular 4 : The Little Book
=
<!-- TOC -->

- [Your First Angular 4 Web Application](#your-first-angular-4-web-application)
    - [Getting started](#getting-started)
    - [Angular-cli](#angular-cli)
        - [Prerequisites](#prerequisites)
        - [Installation](#installation)
        - [Usage](#usage)
- [Quiz Application](#quiz-application)
- [Typescript](#typescript)
- [Components](#components)
    - [Ng-If](#ng-if)
    - [NgSwitch](#ngswitch)
    - [NgClass](#ngclass)
    - [NgFor](#ngfor)
- [Forms](#forms)
- [HTTP](#http)
- [Routing](#routing)
- [Testing](#testing)
- [Hybrid Application with Ionic 3](#hybrid-application-with-ionic-3)
    - [Prerequisites](#prerequisites-1)
    - [Sample Project](#sample-project)
- [Links](#links)

<!-- /TOC -->

## Your First Angular 4 Web Application
In this chapter we’re going to build an application that allows the user  generate a quiz from a json file
### Getting started
### Angular-cli
[Angular-cli](https://github.com/angular/angular-cli#usage) is a command line tool for creating Angular applicaions ,generate components, routes, services and pipes 
#### Prerequisites
- Make Sure that you have  Node 6.9.0 or higher,  with NPM 3 or higher installed
```bash
node --version
```
#### Installation
**BEFORE YOU INSTALL:** please read the [prerequisites](#prerequisites)
```bash
npm install -g @angular/cli
```
#### Usage

```bash
ng new
```
this command creates a new angular application ,it takes one parameter [name] , it will be created in the current location in [name] directory , 
you can also pass other [parameters](https://github.com/angular/angular-cli/wiki/new) such as  -dir  , --style 

```bash
ng generate
```
it takes the blueprint as parameter (class , component , directive ....) , you can check the list of all available blueprints 
[here](https://github.com/angular/angular-cli/wiki/generate#available-blueprints)

```bash
ng serve
```
Builds the application and starts a web server ,buy default it uses the port 4000,  you can change it by adding this paramater --port (aliases: -p) , 
additional options are  [here](https://github.com/angular/angular-cli/wiki/serve#options)

- **NOTE**  When running ng serve, the compiled output is served from memory, not from disk. This means that the application being served is not located on disk in the dist folder.

## Quiz Application
## Typescript
## Components
### Ng-If
### NgSwitch
### NgClass
### NgFor
## Forms
## HTTP 
## Routing
## Testing
## Hybrid Application with Ionic 3
### Prerequisites
### Sample Project
## Links
 - [AngularJS 4 Trivia Quiz-App](https://github.com/chihebnabil/AngularJS-4-Quiz-App)

