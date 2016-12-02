# Selfystic

[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/alertbox/selfystic)
[![Join the chat at https://gitter.im/alertbox/ionic-selfystic](https://badges.gitter.im/alertbox/ionic-selfystic.svg)](https://gitter.im/alertbox/ionic-selfystic?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Stories in Ready](https://badge.waffle.io/alertbox/ionic-selfystic.svg?label=ready&title=ready)](http://waffle.io/alertbox/ionic-selfystic)
[![license](https://img.shields.io/npm/l/serverless-dynamodb-local.svg)](https://opensource.org/licenses/MIT)

"Selfystic" is an app to capture and share selfies/groupies with your social networks. A hybrid app using Cordova + AngularJS and Ionic. The app uses the [Swipeable Cards](http://market.ionic.io/plugins/swipeable-cards) plugin in the [Ionic Market](http://market.ionic.io/).

## Table of Contents
 - [Requirements](#requirements)
 - [Getting Started](#getting-started)
 - [File Structure of App](#file-structure-of-app)

## Requirements
1. node.js
2. Cordova and Ionic - npm install cordova ionic
4. Gulp - npm install gulp
5. Bower - npm install bower

## Getting Started

With VS Code:
* Clone this repository.
* Run `npm install` from the project root.
* Run `bower install` from the project root.
* Add android / iOS / windows platform to your project by running `ionic platform add <platform name>@latest` in a terminal from your project root.
* Build the project by running gulp tsc and then `ionic build <platform name>`
* Deploy to device or emulator by running `ionic run <platform name>` or `ionic emulate <platform name>`
* Success

## File Structure of App

```
ionic-selfystic/
├── merges/                           * Contains all platform specific files
|
├── node_modules/                      * Node dependencies
|
├── platforms/                         * Cordova generated native platform code
|
├── plugins/                           * Cordova native plugins go
|
├── resources/                         * Images for splash screens and icons
|
├── www/                               * Folder that is copied over to platforms www directory
│   │   
│   ├── js/                            * Working directory for the main application
│   │    └── app.js                 
│   │
│   ├── css/                           * Compiled CSS
│   │
│   ├── img/                           * App images
│   │
│   ├── lib/                           * Dependencies from bower install 
│   │
│   └── index.html                     * Main entry point
|
├── .editorconfig                      * Defines coding styles between editors
├── .gitignore                         * Example git ignore file
├── config.xml                         * Cordova configuration file
├── gulpfile.js                        * Contains gulp tasks for compiling ts files, scss files and more..
├── ionic.config.json                  * Ionic configuration file
├── package.json                       * Our javascript dependencies
├── ionic-selfystic-starter.sln         * VS solution
├── ionic-selfystic-starter.jsproj        
└── README.md                          * This file
```

