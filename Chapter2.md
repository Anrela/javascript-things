<h2>Chapter 2</h2>
<p>
  I can declare the function, like this:<br>
  var divideByThree = function(number) {<br>
  var val = number / 3;<br>
  console.log(val);<br>
  };
</p>
<p>
  I can make a function that tells the world what i want to eat, like this:<br>
  var foodDemand = function(food) {<br>
  console.log("I want to eat" + " " + food);<br>
  }<br>
  foodDemand('apple');
</p>
<p>
  I can create a function called timesTwo() that takes in a number and returns the number multiplied by two, like this:<br>
  var timesTwo = function (number) {<br>
  return number * 2;<br>
  };
</p>
<p>
  I can write a function with two parameters, like this:<br>
  var perimeterBox = function(length, width) {<br>
  return length*2 + width*2;<br>
  }<br>
  perimeterBox(2, 2);
</p>
<p>
  I can define global and local variables, like this:<br>
  var globalVar = "hello";<br>
  var foo = function() {<br>
  console.log(globalVar);<br>
  }<br>
  var foo2 = function() {<br>
  var localVar = 2;<br>
  console.log(localVar);<br>
  }
</p>
</p>


