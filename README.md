
# Robinhood Ninja

A front-end web app built using [Polymer 2.0](https://www.polymer-project.org) components. It's hosted on Firebase Hosting and uses a NodeJS reverse proxy [CORS Anywhere](https://github.com/Rob--W/cors-anywhere) hosted on Amazon AWS EC2 NodeJS instance to redirect calls to api.robinhood.com. 

Unofficial Robinhood API documentation: https://github.com/sanko/Robinhood 

![screenshot](https://firebasestorage.googleapis.com/v0/b/robinhood-web.appspot.com/o/RobinhoodNinja_V1.jpg?alt=media&token=514cac95-3857-47cb-a202-5ad4db954d62)


### If you feel like setting this up locally;
### Clone

   $ git clone  https://github.com/eugv86/Robinhood-Ninja

### Setup

##### Prerequisites

First, install [Polymer CLI](https://github.com/Polymer/polymer-cli) using
[npm](https://www.npmjs.com) (we assume you have pre-installed [node.js](https://nodejs.org)).

    npm install -g polymer-cli

Second, install [Bower](https://bower.io/) using [npm](https://www.npmjs.com)

    npm install -g bower

### Start the development server

This command serves the app at `http://127.0.0.1:8081` and provides basic URL
routing for the app:

    polymer serve

### Build

The `polymer build` command builds your Polymer application for production, using build configuration options provided by the command line or in your project's `polymer.json` file.  
