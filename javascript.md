# Javascript styleguide

## Commenting

I use Douglas Crockford style, only `//` comments;
no indenting. This makes code look like a text, and gives you more space to write.

Comments are as important as code, they should introduce what is being done without paraphrasing what your code said.

Write comments as if you were writing a book that explains what your code is doing.

## Variable declaration

All variables should be declared at the top of the function
within one `var` statement.

````
function myFunction() {
  var myVariable,
      myOtherVariable,
      someOtherVar;
}
````

## Functions

### Declaration
Top level function should be declared using the function statement, while inner-functions should be declared with a function expression.

````
function topLevelFunction() {
  var innerFunction = function() {
    return 'foo';
  };
}
````

### Naming

No space between name and first parenthesis.