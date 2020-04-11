# wrap-with-shouts
### package wraps two exclamation points in the beginning and end of strings

# Installation
```
npm install wrap-with-shouts
```
### app.js
```
const shout = require('wrap-with-shouts');
const saying = 'Stop in the name of love';
const res = shout(saying);
console.log(res);
```
navigate to project directory
### run file
```
node app.js
```
### output
```
!! Stop in the name of love !!
```
