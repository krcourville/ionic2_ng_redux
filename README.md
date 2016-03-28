# ionic2_ng_redux

A simple (yet slightly complex) sample CRM application that uses Ionic 2 
and Redux.

## Dev Diary

### Project Setup

Created and cloned [ionic2_ng_redux](https://github.com/krcourville/ionic2_ng_redux) repo

Used instructions from [Getting Started](http://ionicframework.com/docs/v2/getting-started/)

    npm install -g ionic2beta cordova

Ran into issue described [here](https://forum.ionicframework.com/t/enoent-spawn-error-with-ionic-start/47531)
and applied fix of downgrading for now.

    npm install -g ionic@2.0.0-beta.22

Created `src` folder. This will contain all actual code.

From the `src` folder, created the new project based on tutorial tempalte with 
typscript:

    ionic start --v2 --ts --appname "CRM" -s crm tutorial
	
Directory `app` is for app source.

Typescript appears to be debuggable in chrome.

*Deferring Development*: No Virtual Scroll component is yet complete for Angular 2 or Ionic 2.