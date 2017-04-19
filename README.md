# Adding a Service Worker with sw-precache

Implementation of [Adding a Service Worker with sw-precache codelab](https://codelabs.developers.google.com/codelabs/sw-precache/index.html), a tutorial for add a Service Worker in a web app, for cache control.

## How to Setup

First you need:

* [Web Server for Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)
* Chrome 52 or above
* [Node.js with npm](https://nodejs.org/en/)

After you clone this code, you need to install some packages, so select the project folder in the cmd prompt (this can take some time):

```
$ npm install
$ npm install --save-dev sw-precache
$ npm install -g gulp
$ gulp
$ gulp generate-service-worker
```

After the setup, open the Web Server and set the folder to the "app" folder. You will recieve the Web Server URL that you will need to see the updates, but first, check the box "Automatically show index.html" and don't close this window.

The code used for the test was the [Airhorn ](https://github.com/GoogleChrome/airhorn.git), so if you open the Server URL and click on the screen, you will hear the airhorn sound.
You can check if the Service Worker is working by stopping the Web Server and refreshing the page, this will simulate a offline situation. If you still seeing the airhorn, everything is right.


## Built with

* [WebStorm 2017.1.1](https://www.jetbrains.com/webstorm/)

## Also see

* [Sample Code (Airhorn)](https://github.com/GoogleChrome/airhorn.git)