![CF](http://i.imgur.com/7v5ASc8.png) LAB 38
=================================================

## Lab 38: Socket io

### Author: Ryan Gallaway

### Links and Resources

[![Build Status](https://www.travis-ci.com/rkgallaway/38-socket.io.svg?branch=master)](https://www.travis-ci.com/rkgallaway/38-socket.io)

* [repo](https://github.com/rkgallaway/38-socket.io)
* [travis](https://www.travis-ci.com/rkgallaway/38-socket.io)
* [back-end](http://xyz.com) (when applicable)
* [front-end](http://xyz.com) (when applicable)

#### Documentation
* [swagger](http://xyz.com) (API assignments only)
* [jsdoc](http://xyz.com) (All assignments)

### Modules
#### `modulename.js`
##### Exported Values and Methods

## Assignment
Extend the functionality of the base **Yakker** application

### Requirements - Client
* Add message history to the display
  * Only the last 15
  * Allow a user to bookmark, like, or un-like a message
* STYLING
* Animate incoming messages

### Requirements - Server
* Add support for additional events
  * What else should you consider supporting?
    * Flag? Like? Delete?
  * Hold onto history
    * Up to 1000?
    * Persist on server stop, Load on start
### Setup
#### `.env` requirements
* `PORT` - Port Number
* `MONGODB_URI` - URL to the running mongo instance/db

#### Running the app
* `npm start`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### Tests
* How do you run tests?
* What assertions were made?
* What assertions need to be / should be made?

#### UML
![Socket io UML](./assets/uml.jpg)