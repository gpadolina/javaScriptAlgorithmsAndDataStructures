# Basic JavaScript

#### Write Reusable JavaScript with Functions
```
function reusableFunction() {
  console.log("Hi World")
}

reusableFunction()
```

#### Passing Values to Functions with Arguments
```
function functionWithArgs(a, b) {
  console.log(a + b)
}

functionWithArgs(1, 2)
```

#### Return a Value from a Function with Return
```
function timesFive(a) {
  return a * 5;
}

timesFive(5)
```

#### Global Scope and Functions
```
// Declare the myGlobal variable below this line
let myGlobal = 10;

function fun1() {
  oopsGlobal = 5 // Assign 5 to oopsGlobal Here

}

// Only change code above this line

function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```

#### Local Scope and Functions
```
