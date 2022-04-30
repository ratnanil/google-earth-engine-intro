
## Demo in an html file

As per instructions in the slides, create an html file and open this file in a browser window. Create opening and closing  `<script>` tags.

```html
<script>
</script>
```

Now, start developping javascript code in between the `<script>` tags.

```js
// create a var, have a look at the browser.
var myname = "Nils Ratnaweera";

// where is this var?
// show that the variable exists
```

Demonstrate `console.log`.


```js
var myname = "Nils Ratnaweera";

// this wont show in the console
var myname = "Nils Ratnaweera";
```


```js
// adding this will:
console.log(myage_days);
```

Demonstrate creating numeric values

```js
var myage = 34;
console.log("I am "+myage_days+" years old");

```

Demonstrate doing math

```js
var myage_days = myage*365;

console.log("I am "+myage_days+" days old");
```

In the console, demonstrate checking the type with `typeof()`

```js
typeof(myage);
typeof(myname);
```

Now, demonstrate comments by adding comments to the code

```js
// I'm declaring my variables here:
var myage = 34;
var myage_days = myage*365;

console.log("I am "+myage_days+" days old");
```

Demonstrate creating arrays

```js
var myFriends = ["John","Peter", "Mary"];
```

In the console, demonstrate calling items from an array in the console. 
**Note** that the first value is index as `0`

```js
myFriends[0];
```

What if we want to store information on each friend, e.g. the age? 
Demonstrate this with a dictionary.

```js
var myFriends = {John: 23, Peter: 33, Mary: 40};
```

Show that indexing does not work with numbers in a dictionary
```js
myFriends[0];

// it works with string
myFriends["John"];

// or with a dot
myFriends.John;
```

Demonstrate functions. 

Question: what are functions good for?

```js
// write this function in the html file, 
// then run it in the console
function say_hello(){
    console.log("hello")
};
```

```js
// write this function in the html file, 
// and call it within the script
function say_hello(){
    console.log("hello")
};

say_hello();
```

The previous function did not take an input. 

Let's create a function that takes an input:

```js
// write this function in the html file, 
// then run it in the console
function say_something(what){
    console.log(what)
};
```

Task: create a function that converts a number of years to a number of days.

```js
// create this function in the html file, 
// demonstrate it in the console. 
function years2days(years){
    console.log(years*365)
}; 
// Show how the result cannot be assigned to a variable
// in the console:

var myage_days;
myage_days = years2days(34);
myage_days;
```

Show how the function should `return` something rather than printing to the console.

```js
function years2days(years){
    return years*365
};
```



