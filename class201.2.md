# Basics of HTML, CSS & JS

This topic is important to for continuing to build on my understanding of each of these languages and web development in general.

## Learn HTML

### Why is it important to use semantic elements in our HTML?

Semantic elements have built in styling and function that make them suitable for certain purposes and positions within the HTML document.

### How many levels of headings are there in HTML?

There are six levels of headings in HTML.

### What are some uses for the <sup> and <sub> elements?

These tags define superscipt and subscript text. Generally these elements are used to change the position of text to comply with typographical conventions such as in writing chemical formulas. The numbers in chemical formulas are typically written in subscript next to the element abbreviations to specify how many parts of that element are present within the greater chemical.

Superscript might be used to show the power of a certain number in mathmatical formulas.

### When using the <abbr> element, what attribute must be added to provide the full expansion of the term?

Typically the abbr element is used to denote an abbreviation or acronym such as USA or CSS or USMC.

## Learn CSS

### How CSS Is Structured?

CSS uses a selector to tell the browser which element the following property or value applies to. You can then select a property of that element which to change the value of. In the following example the selector is the p tag. The property is color and the value of that property is red.

p {
  color: red;
}

### What are ways we can apply CSS to our HTML?

You can add CSS to an HTML document via external, internal and inline methods.

### Why should we avoid using inline styles?

Inline style much up your HTML, making it harder to identify different elements within your text editor.

### Review the block of code below and answer the following questions

   h2 {
     color: black;
     padding: 5px;
   }

#### What is representing the selector?

h2

#### Which components are the CSS declarations?

When a property is paired with a value, this pairing is called a CSS declaration. color: black; and padding: 5px; are the declarations.

#### Which components are considered properties?

The properties are the color and padding identifiers that specify the stylistic feature we are going to modify.

## Learn JS

### What data type is a sequence of text enclosed in single quote marks?

A string

### List 4 types of JavaScript operators

Addition  +
Stict Equality ===
Not !
Does-not-equal !==
Subtraction -
Multiplication *
Division /

### Describe a real world Problem you could solve with a Function

You could use a function to convert celsius to farenheit.

## Making Decisions In Your Code – Conditionals

An if statement checks a *condition* and if it evaluates to *true*, then the code block will execute.

### What is the use of an else if?

Else if statements give an alternative to the if statement coming back false and give us multiple alternatives to choose from a prompt.

## List 3 different types of comparison operators

Stict Equality ===
Not !
Does-not-equal !==
Greater than >
Less than <
Greater than or equal to >=
Less than or equal to <=

## What is the difference between the logical operator && and ||?

&& — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
|| — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.

if (choice === 'sunny' && temperature < 86) {
  para.textContent = `It is ${temperature} degrees outside — nice and sunny. Let\'s go out to the beach, or the park, and get an ice cream.`;
} else if (choice === 'sunny' && temperature >= 86) {
  para.textContent = `It is ${temperature} degrees outside — REALLY HOT! If you want to go outside, make sure to put some sunscreen on.`;
}

Section quoted from source: <https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals#if...else_statements>
