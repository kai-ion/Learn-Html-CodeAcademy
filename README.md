# ****Learn-HTML-CodeAcademy****
My Progress On learning HTML from CodeAcademy


## HTML Elements and Structure
__Learn about HTML elements and structure, the building blocks of websites.__

  ### [Cheat Sheet](https://www.codecademy.com/learn/learn-html/modules/learn-html-elements/cheatsheet)
  
  ### Tasks:
  - [x] Created a simple webpage about [Brown Bears](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Brown%20Bears). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Brown%20Bears/index.html)
  - [ ] Created a Fashion Blog

  ### video
  HTML Structure --- [Link to video](https://www.youtube.com/watch?v=uxmB8MlO3m8&ab_channel=Codecademy)
  
  HTML Doc Standards --- [Link to video](https://www.youtube.com/watch?v=B4tCt6elrU0&ab_channel=Codecademy)

  ### Introduction to HTML
  1.	HTML stands for HyperText Markup Language and is used to create the structure and content of a webpage.
  2.	Most HTML elements contain opening and closing tags with raw text or other HTML tags between them.
  3.	HTML elements can be nested inside other elements. The enclosed element is the child of the enclosing parent element.
  4.	Any visible content should be placed within the opening and closing <body> tags.
  5.	Headings and sub-headings, ``<h1>`` to ``<h6>`` tags, are used to enlarge text.
  6.	``<p>``, ``<span>`` and ``<div>`` tags specify text or blocks.
  7.	The ``<em>`` and ``<strong>`` tags are used to emphasize text.
  8.	Line breaks are created with the ``<br>`` tag.
  9.	Ordered lists ``<ol>`` are numbered and unordered lists ``<ul>`` are bulleted.
  10.	Images ``<img>`` and videos ``<video>`` can be added by linking to an existing source.
  
  ### HTML Document Standards
  1.	The ``<!DOCTYPE html>`` declaration should always be the first line of code in your HTML files. This lets the browser know what version of HTML to expect.
  2.	The ``<html>`` element will contain all of your HTML code.
  3.	Information about the web page, like the title, belongs within the ``<head>`` of the page.
  4.	You can add a title to your web page by using the ``<title>`` element, inside of the head.
  5.	A webpage’s title appears in a browser’s tab.
  6.	Anchor tags ``<a>`` are used to link to internal pages, external pages or content on the same page.
  7.	You can create sections on a webpage and jump to them using ``<a>`` tags and adding ids to the elements you wish to jump to.
  8.	Whitespace between HTML elements helps make code easier to read while not changing how elements appear in the browser.
  9.	Indentation also helps make code easier to read. It makes parent-child relationships visible.
  10.	Comments are written in HTML using the following syntax: <!-- comment -->.
 
  
  
## HTML Tables
__Learned how to create a table, add data to it, and section the table into smaller parts that make it easier to read.__

  ### [Cheat Sheet](https://www.codecademy.com/learn/learn-html/modules/learn-html-tables/cheatsheet)
  
  ### Tasks:
  - [x] Created a simple webpage about [Shipping Table](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Shipping%20Table). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Shipping%20Table/index.html)
  - [ ] Created a Wine Festival Schedule

  ### Tables
  1.	The ``<table>`` element creates a table.
  2.	The ``<tr>`` element adds rows to a table.
  3.	To add data to a row, you can use the ``<td>`` element.
  4.	Table headings clarify the meaning of data. Headings are added with the ``<th>`` element.
  5.	Table data can span columns using the ``colspan`` attribute.
  6.	Table data can span rows using the ``rowspan`` attribute.
  7.	Tables can be split into three main sections: a head, a body, and a footer.
  8.	A table’s head is created with the ``<thead>`` element.
  9.	A table’s body is created with the ``<tbody>`` element.
  10.	A table’s footer is created with the ``<tfoot>`` element.
  11.	All the CSS properties you learned about in this course can be applied to tables and their data.

  

## HTML Forms
__Learned how to create a form.__

  ### [Cheat Sheet](https://www.codecademy.com/learn/learn-html/modules/learn-html-forms/cheatsheet)
  
  ### Tasks:
  - [x] Created a simple webpage about [Burger Order Form](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Burger%20Order%20Form). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Burger%20Order%20Form/index.html)
  - [x] Created a simple webpage [Number Guessing Form](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Number%20Guessing%20Form). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Number%20Guessing%20Form/index.html)
  - [x] Created a simple webpage [Sign Up Form](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Sign%20Up%20Form). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Sign%20Up%20Form/inde.html)
  - [ ] Created a Form A Story

  ### Forms
  1.	The purpose of a <form> is to allow users to input information and send it.
  2.	The `<form>`‘s action attribute determines where the form’s information goes.
  3.	The `<form>`‘s method attribute determines how the information is sent and processed.
  4.	To add fields for users to input information we use the `<input>` element and set the type attribute to a field of our choosing:
  -	Setting type to "text" creates a single row field for text input.
  -	Setting type to "password" creates a single row field that censors text input.
  -	Setting type to "number" creates a single row field for number input.
  -	Setting type to "range" creates a slider to select from a range of numbers.
  -	Setting type to "checkbox" creates a single checkbox which can be paired with other checkboxes.
  -	Setting type to "radio" creates a radio button that can be paired with other radio buttons.
  -	Setting type to "list" will pair the `<input>` with a `<datalist>` element if the id of both are the same.
  -	Setting type to "submit" creates a submit button.
  5.	A `<select>` element is populated with `<option>` elements and renders a dropdown list selection.
  6.	A `<datalist>` element is populated with `<option>` elements and works with an `<input>` to search through choices.
  7.	A `<textarea>` element is a text input field that has a customizable area.
  8.	When a `<form>` is submitted, the name of the fields that accept input and the value of those fields are sent as name=value pairs.
  
  ### Form Validation
  1.	Client-side validations happen in the browser before information is sent to a server.
  2.	Adding the `required` attribute to an input related element will validate that the input field has information in it.
  3.	Assigning a value to the `min` attribute of a number input element will validate an acceptable minimum value.
  4.	Assigning a value to the `max` attribute of a number input element will validate an acceptable maximum value.
  5.	Assigning a value to the `minlength` attribute of a text input element will validate an acceptable minimum number of characters.
  6.	Assigning a value to the `maxlength` attribute of a text input element will validate an acceptable maximum number of characters.
  7.	Assigning a regex to `pattern` matches the input to the provided regex.
  8.	If validations on a `<form>` do not pass, the user gets a message explaining why and the `<form>` cannot be submitted.

## Semantic HTML
  
__Write clearer, more accessible HTML using Semantic HTML tags.__

   ### [Cheat Sheet](https://www.codecademy.com/learn/learn-html/modules/learn-semantic-html/cheatsheet)
  
  ### Tasks:
  - [x] Created a simple webpage about [Dog Fun Facts](https://github.com/kai-ion/Learn-HTML-CodeAcademy/tree/master/Fun%20Fact%20About%20Dogs). 
  A preview can be seen [here](https://htmlpreview.github.io/?https://github.com/kai-ion/Learn-HTML-CodeAcademy/blob/master/Fun%20Fact%20About%20Dogs/index.html)
  - [ ] New York City Blog

  ### Forms
  1.	Semantic HTML introduces meaning to a page through specific elements that provide context as to what is in between the tags.
  2.	Semantic HTML is a modern standard and makes a website accessible for people who use screen readers to translate the webpage and improves your website’s SEO.
  3.	`<header>`, `<nav>` , `<main>` and `<footer>` create the basic structure of the webpage.
  4.	`<section>` defines elements in a document, such as chapters, headings, or any other area of the document with the same theme.
  5.	`<article>` holds content that makes sense on its own such as articles, blogs, comments, etc.
  6.	`<aside>` contains information that is related to the main content, but not required in order to understand the dominant information.
  7.	`<figure>` encapsulates all types of media.
  8.	`<figcaption>` is used to describe the media in `<figure>`.
  9.	`<video>`, `<embed>`, and `<audio>` elements are used for media files.


