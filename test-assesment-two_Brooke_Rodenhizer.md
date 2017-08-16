1. Which HTML 5 tag would you use for semantically correctly wrap your page footer?
<footer></footer?
2. What is the difference between a class and an id in HTML and what is it used for?
Classes like .header can be used to style multiple sections of the page that have that same class.  If you have two classes that are the same then you need a specific id if you want one to be styled differently from the others.
3. What is wrong in the following HTML?
  ```
  <div class="some-class">
  <div class="some-class" id="someID"></div>
  ```
  There is no closing </div> tag for the first line of code.
4. How would you create a new file named `testFile` with the command line?
  touch testFile
5. How would you remove this file with the command line?
  rm testFile
6. Given you are in a folder that has git and a remote branch on github. How would you get the most current version on your machine?
  git pull
7. Which industry vertical are you interested in and why?
  I am interested in web design.  I have a background in graphic design and I would love to be able to know how to publish that content online by designing my own website and websites for existing clients.  I have clients that I produce content for already.  I would like to add to my skillset to be able to further assist my them.  
8. Using Javascript, please write a function testFunc, that takes two arguments, an array and a number, and returns a new array where each element has been multiplied with the second number? E.g. `testFunc([1, 2, 3], 2)` would return `[2, 4, 6]`.
```
function testFunc(){
  for(var i = 0; i < array.length; i++){
    return i * number;
  }
}
testFunc([1, 2, 3], 3)
```
9. Print all numbers from -10 up until 10 to the command line using a for loop in JS.
for(var number = -10; number <= 10; number++){
  console.log(number);
}
10. What would the console print in following example
```
function outer() {
  var x = 5;

  function inner(multiplier) {
    console.log(multiplier - x);
  }

  return inner;
}

var firstResult = outer();
firstResult(10);
```
5
11. What will be output to the terminal?
```
var someObject = {b : "some test", a : "this is A", c : function(input){ return input * 6;}}
console.log(someObject.c(6));
```
36
