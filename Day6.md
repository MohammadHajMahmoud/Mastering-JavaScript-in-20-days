# API's & fetch
- api provide URLS that point at data we need for our program to code
- fetch is used to extract data from an api
  ```javascript
    fetch("http/catsApi")
  //returns json respone about cats 
  ```
## Promise
- is like a "waiting" status for the value that we get from an api request
- there is 3 types of a promise : fulfiled , rejected , pending
- await makes sure that JS stops executing till the await statment is done
- when the await statment is done executing the code contunies executing po
```javascript
console.log("i log before the api request)
const result = await fetch("http/catsApi")
console.log("i log after the api request)
```
## Destructor 
- usefull when giving more than a variable the an atterbuite of an object , could also be an array 
  ```javascript
  const mohammad= [{firstName : "moha" , lastName : "haj"}]
  let {firstName,lastName} = mohammad[0]
  //works the same way
  let [one ,two,three] = [1,2,3]
  ```
## 
