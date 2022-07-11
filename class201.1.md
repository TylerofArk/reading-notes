# Getting Started

This reading assignment reviews some fundamentals of HTMLS, CSS and JavaScript and dives deeper into some of the important features and nuances of each of the languages and website building.

## How HTTP works

The client requests data from a server aka page, site, or app.
The server sends the data back to the client in a snap.
The client now has what they requested sitting right in there lap.

## How the Browser Parses HTML, CSS and Javascript

The browser parses HTML first. This is because the HTML file contains the reference files for the CSS and JS in the script tags.

Then the browser creates an in-memory DOM (Document Object Model) tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

A visual representation of the structures from the previous step are built and the user eventually sees all of the content on the page and can interact with it.

## Finding images for your website

There are a variety of places you can find images for your website. The most important thing, though, is you make sure that you do not violate any copyright laws associated with the use of whichever image / source you choose.

## String vs Number

To create a string in JS you put the text or value in either single or double quotations.

To create a number simple type the numeral with no quotations.

## Variables in JS

Variables store values that you can then use in subsequent code throughout your development. You can declare variables using let or const.

## What is an HTML attribute?

Attributes contain extra information about the element that won't appear in the content.

An attribute should have:

- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
- The attribute name, followed by an equal sign.
- An attribute value, wrapped with opening and closing quote marks.

## Anatomy of an HTML Element

The main parts of an html element are:

The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

The content: This is the content of the element, which in this case, is just text.

The element: The opening tag, the closing tag, and the content together comprise the element.

## Article vs Section tag

Both are semantic tags meaning there is functionality and purpose built into each of them.

### Article

This tag contains independent content that doesn’t require any other context. So the article tag can be placed inside the main content. But each of the articles will contain independent content within it.

### Section

This tag is used to split a page into sections like Introduction, Contact Information, Details, etc and each of these sections can be in a different section tag. The section tag is introduced to wrap-up the things in a particular section. The section tag divides the content into sections and subsections. The section tag is used when requirements of two headers or footers or any other section of documents needed. Section tag grouped the generic block of related content.

Source: <https://www.geeksforgeeks.org/difference-between-article-tag-and-section-tag/>

## Typical HTML Elements

head
body
header: <header>.
navigation bar: <nav>.
main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
sidebar: <aside>; often placed inside <main>.
footer: <footer>.

## Metadata and SEO

Meta tags are snippets of code that tell search engines important information about your web page, such as how they should display it in search results. They also tell web browsers how to display it to visitors.

## How is the meta HTML tag used?

Meta tags are snippets of code that tell search engines important information about your web page, such as how they should display it in search results. They also tell web browsers how to display it to visitors.
Every web page has meta tags, but they’re only visible in the HTML code.

Important meta tags:

Meta title
Meta description
Meta robots
Meta refresh redirect
Meta charset
Meta viewport

Source: <https://ahrefs.com/blog/seo-meta-tags/>

## What is the first step to designing a website?

Wireframing

## Most important question to answer when designing a website?

1. What exactly do I want to accomplish?
2. How will a website help me reach my goals?
3. What needs to be done, and in what order, to reach my goals?

Source: <https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding>

## h1 vs span for top level heading

The h1 tag should always be used as the top level heading vs the span tag because the span tag has no semantic value. The h1 tag contains semantics that make it function best in it's intended position ie the h1.

## Why use semantics in html tags?

Semantics refers to the meaning of a piece of code.

For example, the h1 element gives the text within it the meaning of the top level heading on a page. You wouldn't use the h1 element on body text for this reason.

Generally, if there is an application for using symantic elements in your code you should use it over a non-symantic element. For example, you wouldn't bold and increase the size of the top line of your website, you would just use the h1 element because the semantics of that element give the h1 tag the basic styling it needs to fulfill its role in the structure of your webpage.

## Two things that require JS in the browser?

Timely content updates, interactive maps, animated 2d/3d graphics, scrolling video jukeboxes. Basically anything on the page that doesn't just sit there and anything on the page that the user can interact with.

## How to add JS to an HTML document?

You can add JS to an HTML document via external, internal and inline methods.

Inline is generally discouraged as it pollutes your HTML and makes it harder to read.

External JS is added to html via a script tag that references a .js file in the directory as your index.html.

Internal JS is added to html via adding JS code directly inbetween a script tag.
