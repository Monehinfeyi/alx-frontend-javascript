## 0x01. ES6 Promises

### Resources
Read or watch:

> Promise https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise

> JavaScript Promise: An introduction https://web.dev/promises/

> Await https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await

> Async https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function

> Throw / Try https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw

### Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

. Promises (how, why, and what)

. How to use the then, resolve, catch methods

. How to use every method of the Promise object

. Throw / Try

. The await operator

. How to use an async function

### Setup
Install NodeJS 12.11.x

> curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh

> sudo bash nodesource_setup.sh

> sudo apt install nodejs -y

### Install Jest, Babel, and ESLint
in your project directory:

. Install Jest using: npm install --save-dev jest

. Install Babel using: npm install --save-dev babel-jest @babel/core @babel/preset-env @babel/cli

. Install ESLint using: npm install --save-dev eslint

### Files

package.json

> Click to show/hide file contents

babel.config.js

> Click to show/hide file contents

utils.js

> Use when you get to tasks requiring uploadPhoto and createUser.

Click to show/hide file contents

.eslintrc.js

> Click to show/hide file contents
and…
Don’t forget to run $ npm install when you have the "package.json"

### Response Data Format
uploadPhoto returns a response with the format

{
  status: 200,
  body: 'photo-profile-1',
}

. createUser returns a response with the format

{
  firstName: 'Guillaume',
  lastName: 'Salva',
}

### AUTHOR:
Monehin Feyisara
