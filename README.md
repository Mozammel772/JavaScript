
# JavaScript Best Source Google

 - [W3 schools](https://www.w3schools.com/js/)
 - [Developer.mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 - [Tutorialspoint](https://www.tutorialspoint.com/javascript/index.htm)
 - [Javatpoint](https://www.javatpoint.com/javascript-tutorial)
 - [javascript](https://javascript.info/)












# Javascript String Search

### 1. Javascript String Search IndexOf

```bash
const products = [
  "Hp EliteBook Laptop",
  "HTC Laptop",
  "Walton Laptop",
  "Hp EliteBook Rifle",
  "Samsung laptop",
  "Laptop",
];
const searching = "Laptop";
const output = [];
for (const product of products) {
   if (product.toLowerCase().indexOf(searching.toLowerCase()) != -1) {
     output.push(product);
  } else {
     console.log("Not Found");
   }
 }

 console.log(output);
```
### 2. Javascript String Search includes

```bash
const products = [
  "Hp EliteBook Laptop",
  "HTC Laptop",
  "Walton Laptop",
  "Hp EliteBook Rifle",
  "Samsung laptop",
  "Laptop",
];
const searching = "Laptop";
const output = [];
for (const product of products) {
  if (product.toLowerCase().includes(searching.toLowerCase())) {
     output.push(product);
   } else {
     console.log("Not Found");   
    }
 }

 console.log(output);
```
### 2. Javascript String Search startsWith

```bash
const products = [
  "Hp EliteBook Laptop",
  "HTC Laptop",
  "Walton Laptop",
  "Hp EliteBook Rifle",
  "Samsung laptop",
  "Laptop",
];
const searching = "Laptop";
const output = [];
for (const product of products) {
   if (product.toLowerCase().startsWith(searching.toLowerCase())) {
     output.push(product);
  } else {
     console.log("Not Found");
   }
 }
 console.log(output);
```
### 2. Javascript String Search endsWith

```bash
const products = [
  "Hp EliteBook Laptop",
  "HTC Laptop",
  "Walton Laptop",
  "Hp EliteBook Rifle",
  "Samsung laptop",
  "Laptop",
];
const searching = "Laptop";
const output = [];
for (const product of products) {
  if (product.toLowerCase().endsWith(searching.toLowerCase()))  {
     output.push(product);
  } else {
     console.log("Not Found");
   }
 }
 console.log(output);
```






#          Javascript DOM

## Google Source

 - [JS Common Event](https://www.w3schools.com/js/js_events.asp)




## OnClick Handle Four Way

```bash
  1. Onclick = "Function Name ()"
```
## 2. ID Diye Call

```bash
   2.1. const blues = document.getElementById("blueColor");
         blues.onclick = makeBlue;
         function makeBlue() { 
         document.body.style.backgroundColor = "blue";
         }
```
##  3. ID Diye Function Call

```bash
   3.1. const greenBtn = document.getElementById("greenColor");
         greenBtn.onclick= function () {
         document.body.style.backgroundColor="green"
          }
```
##   4. Best Popular Event Handle 

```bash
   4.1. const purpleBtn = document.getElementById("purpleColor");
         purpleBtn.addEventListener("click", purpleColor);
         function purpleColor() {
         document.body.style.backgroundColor = "purple";
          }
```

# Javascript ES-6

### 1. Javascript Function ES-6

```bash
function addNumber(num1, num2 = 10) {
  // Option 1
  //   num2 = num2 || 0;

  // Option 2
  //   if (num2 == undefined) {
  //     num2 = 0;
  //   }
  const result = num1 + num2;
  return result;
}
const number = addNumber(10);
console.log(number);
```

# Javascript ES-6

### 1. Array Function ES-6

```bash
// Simple Function Declariyar
function add(num1, num2) {
  const sum = num1 + num2;
  return sum;
}
const number = add(12, 15);
console.log(number);

// Function Expression
function add2(num1, num2) {
  return num1 + num2;
}
const number2 = add2(12, 234);
console.log(number2);

// Function Expression (anonymous)
const add3 = function (num1, num2) {
  return num1 + num2;
};

const number3 = add3(22, 23);
console.log(number3);

// Array-Function
const add4 = (num1, num2) => num1 + num2;
const number4 = add4(26, 30);
console.log(number4);
```


# Javascript ES-6
## Today : 2-21-2023


## 1. let const and var

```bash
 1. let 
 2. const 
 3. var Not Allow es-6
```
## 2. template string 

```bash
const first = "Mozammel";
const second = "Hosen";
const full = `${first} ${second}`;
console.log(full);
```
### Output : 

```bash
Mozammel Hosen
```
## 3. Default Parameter in function

```bash
function number(num1, num2 = 10) {
  const result = num1 * num2;
  return result;
}
const numbers = number(12);
console.log(numbers);
```
### Output : 

```bash
120
```


## 4. Arrow function

```bash
const number = (num1, num2) => {
  const result = num1 * num2;
  return result;
};
const number = number1(12,10);
console.log(number);
```
### Output : 

```bash
120
```
## 4.1. Default Parameter Arrow function

```bash
const number = (num1, num2 = 10) => {
  const result = num1 * num2;
  return result;
};
const number = number1(12);
console.log(number);
```
### Output : 

```bash
120
```
## 5. Spread Operator

```bash
const number = [12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22];
console.log(...number);
```
### Output : 

```bash
12 13 14 15 16 17 18 19 20 21 22
```
## 5.1. Spread Operator Example

```bash
const max = Math.max(12, 14, 145, 165, 16, 165, 1554, 5655);
console.log(max);
const maxArray = [12, 13, 145, 15, 15, 215, 14, 250, 140, 1424];
console.log(maxArray);
const maxNumber = Math.max(...maxArray)
console.log(maxNumber);


const numbers = [...maxArray];
numbers.push(465);
console.log(numbers);

const number = [3663,43,34,44,443,...maxArray,364,643,473,347,43747,478347];
console.log(number);
```
### Output : 

```bash
5655
[
   12,   13, 145,  15,
   15,  215,  14, 250,
  140, 1424
]
1424
[
  478347
]
```

# Javascript API

## Json Place Holder Source With Google

 - [Jsonplaceholder](https://jsonplaceholder.typicode.com/)
 
### 2/23/2023

## Stringify

### 1. Converts a JavaScript value to a JavaScript Object Notation (JSON) string.

```bash
const data = {
  id: 1,
  name: "Mozammel",
  address: "Faridpur Sadar Faridpur",
};
const result = JSON.stringify(data);
console.log(result);
```
## OutPut :

```bash
{"id":1,"name":"Mozammel","address":"Faridpur Sadar Faridpur"}
```

## Parse

## 2. Converts a JavaScript Object Notation (JSON) string into an object.

```bash
 const data = {
  "id": 1,
  "name": "Mozammel",
  "address": "Faridpur Sadar Faridpur",
};
const result = JSON.parse(data)
console.log(result);
```
## OutPut :

```bash
{ id: 1, name: 'Mozammel', address: 'Faridpur Sadar Faridpur' }
```


# Javascript Error Handle :

 JavaScript Error Handle Total 4 Way...

 1. console.log("Hello World")
 2. Vs code Break Point Handle
 3. Vs code dubugger KeyWord

```bash
console.log("Hello");
console.log("World");
debugger;
console.log("Hello World");
```
 4. Backtracking error handling







## 1. Javascript SyntaxError

The Javascript SyntaxError is caused by the incorrect use of a pre-defined syntax. Syntax errors are detected while interpreting or parsing source code. For example, a SyntaxError can occur if a closing brace (}) is left off when defining a Javascript function.

জাভাস্ক্রিপ্ট সিনট্যাক্স ত্রুটি একটি পূর্ব-সংজ্ঞায়িত সিনট্যাক্সের ভুল ব্যবহারের কারণে ঘটে। সোর্স কোড ব্যাখ্যা বা পার্স করার সময় সিনট্যাক্স ত্রুটি সনাক্ত করা হয়। উদাহরণস্বরূপ, একটি সিনট্যাক্স ত্রুটি ঘটতে পারে যদি একটি জাভাস্ক্রিপ্ট ফাংশন সংজ্ঞায়িত করার সময় একটি বন্ধ বন্ধনী (}) ছেড়ে দেওয়া হয়।

```bash
function num(num1, num2) {
  //   if (num > 5) {
  if (num1 > 5) {
    return true;
  } else {
    return false;
  }
}
// }
const result = num(12, 12);
console.log(result);

```
## 2. Javascript TypeError


A TypeError may be thrown when: an operand or argument passed to a function is incompatible with the type expected by that operator or function; or. when attempting to modify a value that cannot be changed; or. when attempting to use a value in an inappropriate way.



একটি TypeError নিক্ষিপ্ত হতে পারে যখন: একটি ফাংশনে পাস করা একটি অপারেন্ড বা আর্গুমেন্ট সেই অপারেটর বা ফাংশন দ্বারা প্রত্যাশিত প্রকারের সাথে সামঞ্জস্যপূর্ণ নয়; বা পরিবর্তন করা যাবে না এমন একটি মান পরিবর্তন করার চেষ্টা করার সময়; বা একটি অনুপযুক্ত উপায়ে একটি মান ব্যবহার করার চেষ্টা করার সময়।


```bash
const num = 5;
// num.push(12);
console.log(num);

let address
console.log(address.home);

```
### OutPut Errors :

```bash
TypeError: Cannot read properties of undefined (reading 'home')
    at Object.<anonymous> (D:\WEB-7\common-error-javascript-40\type-error.js:6:21)
    at Module.load (node:internal/modules/cjs/loader:1037:32)
    at Module._load (node:internal/modules/cjs/loader:878:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)      
    at node:internal/main/run_main_module:23:47

```
## 3. Javascript Reference Error


A reference error occurs when JavaScript tries to access a variable that doesn't exist, hasn't been defined, or doesn't exist in the current scope from which you are trying to access it



একটি রেফারেন্স ত্রুটি ঘটে যখন জাভাস্ক্রিপ্ট এমন একটি ভেরিয়েবল অ্যাক্সেস করার চেষ্টা করে যা বিদ্যমান নেই, সংজ্ঞায়িত করা হয়নি বা বর্তমান সুযোগে বিদ্যমান নেই যেখান থেকে আপনি এটি অ্যাক্সেস করার চেষ্টা করছেন



```bash
// console.log(name)
const name = "Abul"

const a = 5;
const b = 5;
console.log(c)

```
### OutPut Errors : 

```bash
D:\WEB-7\common-error-javascript-40\Reference-error.js:6
console.log(c)
            ^

ReferenceError: c is not defined
    at Object.<anonymous> (D:\WEB-7\common-error-javascript-40\Reference-error.js:6:13)       
    at Module._compile (node:internal/modules/cjs/loader:1159:14)
    at Module._extensions..js (node:internal/modules/cjs/loader:1213:10)
    at Module.load (node:internal/modules/cjs/loader:1037:32)
    at Module._load (node:internal/modules/cjs/loader:878:12)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:81:12)     
    at node:internal/main/run_main_module:23:47
```





