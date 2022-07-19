# Object-Oriented Programming, HTML Tables

## Domain Modeling

### Explain why we need domain modeling

Domain modeling allows us to custom create a solution based on an individual problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

## HTML Table Basics

### Why should tables not be used for page layouts?

1. Layout tables reduce accessibility for visually impaired users: Screenreaders, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screenreaders' output will be confusing to their users.

2. Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

3. Tables are not automatically responsive: When you use proper layout containers (such as header, section, article, or div), their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

Source [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

### List and describe 3 different semantic HTML elements used in an HTML table

th - table header: bolds the column and row headings
td - table data: goes inbetween table row tags and holds the data of each cell
tr - table row: starts a new row

## Introducing Constructors

### What is a constructor and what are some advantages to using it?

A constructor is just a function called using the new keyword. When you call a constructor, it will:

1. create a new object
2. bind this to the new object, so you can refer to this in your constructor code
3. run the code in the constructor
4. return the new object.

### How does the term this differ when used in an object literal versus when used in a constructor?

this doesn't have to have a value in a constructor because the constructor is going to assign it a name based on the input where as in an object this refers to a predetermined name.

## Object Prototypes Using A Constructor

### Explain prototypes and inheritance via an analogy from your previous work experience

* NOTE: This is a very common front end developer interview question
