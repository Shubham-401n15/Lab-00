# LAB - 00

## Proof of Life Server

### Author: Shubham Majumdar

### Links and Resources
* [submission PR](https://github.com/Shubham-401n15/Lab-00/pull/1)
* [travis](https://travis-ci.com/Shubham-401n15/Lab-00)
* [front-end](https://shubham-lab00-401n15.herokuapp.com/)

#### Documentation
* [jsdoc](https://shubham-lab00-401n15.herokuapp.com/docs/)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a boolean based on the arg sent in.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns true or false
* Endpoint: `/docs`
  * Renders Developer Documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`
* Assertions Made
  * Assert that isAlive() properly returns a boolean
* Assertions Remaining
  * ... Things I want to tests, but didn't yet.

#### UML

![UML Diagram](whiteboard.jpg)
