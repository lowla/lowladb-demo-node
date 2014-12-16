
## LowlaDB Demo for Node ##

> A simple TODO app demonstrating LowlaDB sync and offline data.

### Prerequisites ###

This example assumes that `git`, `npm` and `bower` are present and available from the command line.  It uses LowlaDB's
included NEDB datastore to store documents needed by the LowlaDB server and the TODO application itself.

### Installing and Running ###

To install and run this example, perform the following steps:

1. Create a local clone of this repository
  * `git clone https://github.com/lowla/lowladb-demo-node`
2. Install NPM modules
  * `npm install`
3. Install Bower components in the web app folder
  * `cd todomvc`
  * `bower install`
  * `cd ..`
4. Start the Node server
  * `node app.js`
5. Open the TodoMVC page
  * `http://localhost:3000/index.html`
