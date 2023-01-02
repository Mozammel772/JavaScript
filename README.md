
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




