
# JavaScript Best Source Google

 - [W3 schools](https://www.w3schools.com/js/)
 - [Developer.mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 - [Tutorialspoint](https://www.tutorialspoint.com/javascript/index.htm)
 - [Javatpoint](https://www.javatpoint.com/javascript-tutorial)
 - [javascript](https://javascript.info/)

#          Javascript DOM

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


