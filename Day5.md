# Conditionals 
if,else & else if 
- if the **if** condition is met then it block of code is executed
- if not then the **else** code block is exectued
- sometimes we get extra condtions with their own block of code using **else if**
  ```javascript
  function compareNumbers(x, y) {
    if (x > y) {
        return "x is greater than y.";
    } else if (x < y) {
        return "x is less than y.";
    } else {
        return "x is equal to y.";
    }
  }
   ```
## Exercise
- Write a conditional that logs a message saying whether your first name or last name is longer
  ```javascript
  let firstName = "mohammad";
  let lastName = "mahmoud";

  if (firstName.length > lastName.length) {
    console.log("First name is longer.");
  } else if (firstName.length < lastName.length) {
    console.log("Last name is longer.");
  } else {
    console.log("First name and last name have the same length.");
  } ```
- check wether an array is empty
```javascript
function isEmpty(array) {
    return array.length === 0;
}
```
- truthy or falsy array
``` javascript
      let testArray = [];
      if (testArray) {
        console.log("The array is truthy.");
      } else {
      console.log("The array is falsy.");
  }
  ```