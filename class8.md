# Operators and Loops

## Comparison Operators

### Operator | Desciption

==         equal to
===        equal value and equal type
!=         not equal
!==        not equal value or not equal type
>          greater than
<          less than
>=         greater than or equal to
<=         less than or equal to
?          ternary operator

## Loops

Loops offer a quick and easy way to do something repeatedly.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

### For Loop

A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:

for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

### While Loop

The while loop loops through a block of code as long as a specified condition is true.

In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10:

Example
while (i < 10) {
  text += "The number is " + i;
  i++;
}
