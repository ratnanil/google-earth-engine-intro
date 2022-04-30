
## Demo in the browser Console


Creating string variables: 

```js
// just like in R, but not correct
myname = "Nils Ratnaweera" 

// use var to create a new variable 
var myname = "Nils Ratnaweera" 

// end statement with a semi colon
var myname = "Nils Ratnaweera"; 
```

Checking the `type`

```js
type(myname)
```


Creating numeric varibles

```js
// create a number in quotes
var myage = "34";

// check the type of this number
type(myage);
// why is this not a number, but a string?

// you can't do maths
myage+1;

```

```js
// number are not in quotes (just like in R)
var myage = 34;

type(myage);

// now, you can do math
myage+1

myage*365; 

// you can also create variables "on the fly"
var myage_days = myage*365; 

```
You can create variables first and fill them later

```js
var myage_days;

myage_days = myage*365;
```

You can print to the console my calling the variable (just like in R).
But this only works from the interactive console.

```js
myage_days;
```



`let` and `const` are other ways to create variables  with subtle differences, but we will ignore these in our lesson.

```js
let myname = "Nils Ratnaweera";
const myname = "Nils Ratnaweera";
```