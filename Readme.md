## Callback Functions
a function passed into another function as a parameter.
a function that are called by the runtime at a specifi time and the function will do a certain job at that case.

```javascript
function callbackFunction(){
    // Do something
}

function executeCallbackFunction(){
    // Do something
}
```
`executeCallbackFunction(callbackFunction)`
We simply pass the name of the function. In order to pass a function as a parameter to an other function.
We are not calling the function the computer is calling the function. 
Here the call back function is `callbackFunction`.

`readFile('essay.txt', checkForPlagiarism);` In this example call back is the second argument `checkForPlagiarism`.

When we declared the function with name `callbackFunction` practically we did the following: this is functionally identical with the callback function name
```javascript
const callbackFunction = function (){
     // Do something
}
```


Function is set of instruction that are run several time in the application upon on call. You are asking for those 
lines of codes to be executed each time immediately this is also know asynchronous programming.

Asynchronous Programming allow computer to do other task while waiting for a certain task. 

## Callback Uses
    -One off and repeating timers (a clock need to update each second)
    -Triggered by a user interaction (after submitting a form)
    -Loading data from a server using AJAX
    -Reading a file in Node.js

Callback can be place anywhere in the function.



