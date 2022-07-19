# Problem Domain, Objects, and the DOM

## How would you describe an object to a non-technical friend you grew up with?

An object is a collection of data that is all related to one source. For example, I could have an object called "Your Name" and all of the data in the object would be related to you.

## What are some advantages to creating object literals?

Sending an object literal is more efficient than sending several items individually and is easier to work with than an array when you want to identiry individual objects by name.

## How do objects differ from arrays?

Objects are used to represent a “thing” in your code. That could be a person, a car, a building, a book, a character in a game — basically anything that is made up or can be defined by a set of characteristics.

We use arrays whenever we want to create and store a list of multiple items in a single variable. Arrays are especially useful when creating ordered collections where items in the collection can be accessed by their numerical position in the list.

Source: [Medium](https://medium.com/@zac_heisey/objects-vs-arrays-42601ff79421)

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

Dot notation is generally preferred over bracket notation because it is more succinct and easier to read. However there are some cases where you have to use brackets. For example, if an object property name is defined at runtime then you can't use dot notation to access the value, but you can pass the name as a variable inside brackets.

const person = {
  name: ['Bob', 'Smith'],
  age: 32
}
const input = prompt('Get name or age?')
console.log(person[input])

## Setting object members

So far we've only looked at retrieving (or **getting**) object members — you can also **set** (update) the value of object members by declaring the member you want to set (using dot or bracket notation), like this:

```js
person.age = 45;
person['name']['last'] = 'Cratchit';


## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

this.name refers to 'Spot' and this.age refers to 2. .this is easy to read and you know it referrences a variable within the object you are working in. 

<!-- const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
} -->

## What is the DOM?

DOM stand for the Document Object Model and it is the data representation of the objects that comprise the structure and content of a document on the web. 

## Briefly describe the relationship between the DOM and JavaScript

The previous short example, like nearly all examples, is JavaScript. That is to say, it is written in JavaScript, but uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language would not have any model or notion of web pages, HTML documents, SVG documents, and their component parts. The document as a whole, the head, tables within the document, table headers, text within the table cells, and all other elements in a document are parts of the document object model for that document. They can all be accessed and manipulated using the DOM and a scripting language like JavaScript.

The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node.js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node.js runtime.

The DOM was designed to be independent of any particular programming language, making the structural representation of the document available from a single, consistent API.

Source: [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
