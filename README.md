# Randomcode

### How to install
To install Randomcode, you need to **execute this command** in your project's folder.
```bash
npm install Randomcode --save
```
### How to use
To start using Randomcode, you need to add the module to the file.
```js
var gen = require('randomcode');
```
To generate a basic code, call the function like this:
```js
gen(8);
// Output: Dk4CJl7D
```
> In this case, "8" is the length of the code.

Randomcode, have 3 diferent modes:
`0` => Normal, all the characters.
`1` => Only letters.
`2` => Only numbers

To set the mode for the code, you need to add it in the function like this:
```js
gen(8, 0);	// Output: ia8kfY4X
gen(8, 1);	// Output: liJqgUVi
gen(8, 2);	// Output: 29172567
```
