# HTML Lists, Control Flow with JS, and the CSS Box Model

## Learn HTML

### Ordered and Unordered lists

#### When should you use an unordered list in your HTML document?

When you need to group a collection of items that do not need to be organized in any certain way.

#### How do you change the bullet style of unordered list items?

Change the bullet type to circle, disc, square and in some browsers triangle.

#### When should you use an ordered list vs an unorder list in your HTML document?

Use an ordered list when the collection of items in the list benefit from being in a certain order such as order of importance, like a food recipe, or alphabetical order for a roster.

#### Describe two ways you can change the numbers on list items provided by an ordered list?

You can change the numbers from standard to roman numerals. You can also use nested lists to make lists within a list. Finally you can start a list with a number besides 1.

##### Roman Numerals

<ol type="i">
  <li>Introduction</li>
  <li>List of Grievances</li>
  <li>Conclusion</li>
</ol>

##### Nested List

<ol>
  <li>first item</li>
  <li>second item  <!-- closing </li> tag not here! -->
    <ol>
      <li>second item first subitem</li>
      <li>second item second subitem</li>
      <li>second item third subitem</li>
    </ol>
  </li>            <!-- Here's the closing </li> tag -->
  <li>third item</li>
</ol>

##### Staring a list with a number other than 1

<p>Finishing places of contestants not in the winners' circle:</p>

<ol start="4">
  <li>Speedwalk Stu</li>
  <li>Saunterin' Sam</li>
  <li>Slowpoke Rodriguez</li>
</ol>

## Learn CSS

### The Box Model

### Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

### List and describe the four parts of an HTML elements box as referred to by the box model

## Learn JS

### Arrays. Operators and Expressions. Conditionals. Loops

#### What data types can you store inside of an Array?

#### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

#### List five shorthand operators for assignment in javascript and describe what they do

#### Read the code below and evaluate the last expression and explain what the result would be and why

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

#### Describe a real world example of when a conditional statement should be used in a JavaScript program

#### Give an example of when a Loop is useful in JavaScript
