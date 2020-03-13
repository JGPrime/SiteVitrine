# SiteVitrine

Requirements
Node and npm (see NodeJS
Install grunt-cli globally: npm install -g grunt-cli
Once you have installed the requirements, checkout this repository and run npm install:

git clone git@github.com:JGPrime/SiteVitrine.git
npm install
Included tasks
Workflows
These are high level tasks that build up common work flows in development.

Package.json

{
  "name": "sv",
  "version": "1.0.0",
  "description": "",
  "main": "index.html",
  "scripts": {
    "test": "test"
  },
  "author": "JG",
  "license": "ISC",
  "devDependencies": {
    "grunt": "^1.0.4",
    "grunt-contrib-concat": "^1.0.1",
    "grunt-contrib-jshint": "^2.1.0",
    "grunt-contrib-uglify": "^4.0.1",
    "grunt-contrib-watch": "^1.1.0",
    "grunt-html": "^12.2.1",
    "grunt-html-build": "^0.7.1",
    "grunt-vnuserver": "^1.0.3"
  },
  "dependencies": {
    "animate.css": "^3.7.2",
    "bootstrap": "^4.4.1"
  }
}
