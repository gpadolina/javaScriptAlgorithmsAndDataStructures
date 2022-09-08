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
function myLocalScope() {
  // Only change code below this line
  const myVar = 5
  console.log('inside myLocalScope', myVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);
```

#### Global vs. Local Scope in Functions
```
// Setup
const outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  const outerWear = "sweater";
  // Only change code above this line
  return outerWear;
}

console.log(myOutfit());
```

### Understanding Undefined Value returned from a Function
```
// Setup
let sum = 0;

function addThree() {
  sum = sum + 3;
}

// Only change code below this line
function addFive() {
  sum += 5;
}

// Only change code above this line

addThree();
addFive();
```

#### Assignment with a Returned Value
```
// Setup
let processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7);
```

#### Stand in Line
```
function nextInLine(arr, item) {
  // Only change code below this line
  arr.push(item);


  return arr.shift();
  // Only change code above this line
}

// Setup
const testArr = [1, 2, 3, 4, 5];

// Display code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6));
console.log("After: " + JSON.stringify(testArr));
```

#### Understanding Boolean Values
```
function welcomeToBooleans() {
  // Only change code below this line

  return true; // Change this line

  // Only change code above this line
}
```

#### Use Conditional Logic with If Statements
```
function trueOrFalse(wasThatTrue) {
  // Only change code below this line
  if (wasThatTrue) {
    return "Yes, that was true";
  }
    return "No, that was false";
  // Only change code above this line

}
```

#### Comparison with the Equality Operator
```
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testEqual(10);
```

#### Comparison with the Strict Equality Operator
```
// Setup
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

testStrict(10);
```

#### Practice comparing different values
```
