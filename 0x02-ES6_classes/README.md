### This directory contains files with code in it on `ES6 classes`(javascript) project.

### Resources:

* [classes](/https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
* [Metaprogramming](/https://www.keithcirkel.co.uk/metaprogramming-in-es6-symbols/#symbolspecies)

### Requirements
* All your files will be executed on `Ubuntu 18.04 LTS using NodeJS 12.11.x`
* Allowed editors: `vi, vim, emacs, Visual Studio Code`
* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project, is mandatory
* Your code should use the js extension
* Your code will be tested using `Jest` and the command `npm run test`
* Your code will be verified against `lint` using `ESLint`
* Your code needs to pass all the tests and lint. You can verify the entire project running `npm run full-test`

### Setup

Install NodeJS 12.11.x

`curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh`

`sudo bash nodesource_setup.sh`

`sudo apt install nodejs -y`

### Install Jest, Babel, and ESLint

in your project directory:

* Install Jest using: `npm install --save-dev jest`
* Install Babel using: `npm install --save-dev babel-jest @babel/core @babel/preset-env`
* Install ESLint using: `npm install --save-dev eslint`

 ###  Configuration files

`package.json`

Click to show/hide file contents

`babel.config.js`

Click to show/hide file contents

## Tasks

> 0. Implement a class named ClassRoom:

 * Prototype: export default class ClassRoom
 * 
 * It should accept one attribute named maxStudentsSize (Number) and assigned to _maxStudentsSize

> 1. Import the ClassRoom class from 0-classroom.js.

* Implement a function named initializeRooms. It should return an array of 3 ClassRoom objects with the sizes 19, 20, and 34 (in this order).

> 2. Implement a class named `HolbertonCourse`:

Constructor attributes:

`name` (String)

`length` (Number)

`students` (array of Strings)

* Make sure to verify the type of attributes during object creation
* Each attribute must be stored in an “underscore” attribute version (ex: `name` is stored in `_name`)
* Implement a getter and setter for each attribute.


   ## AUTHOR:

  > MONEHIN FEYISARA



  
