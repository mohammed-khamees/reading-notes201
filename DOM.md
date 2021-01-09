# JS Object Literals; The DOM

An object is a series of variables and functions that represent something from the world around you.
In an object, _variables_ are known as **properties of the object**; _functions_ are known as **methods of the object**.
Web browsers implement objects that represent both the browser `window` and the `document` loaded into the
browser window. JavaScript also has several built-in objects such as

- String
- Number
- Math
- Date

Their _properties_ and _methods_ offer functionality that help you write scripts.
**Arrays** and **objects** can be used to create complex data sets (and both can contain the other).

The browser represents the page using a **DOM** tree. **DOM** trees have four types of nodes:

- document nodes
- element nodes
- attribute nodes
- text nodes

You can select element nodes by their `id` or `class` attributes, by _tag name_, or using _CSS selector syntax_.
Whenever a DOM query can return more than one node, it will always return a Nodelist.
From an element node, you can access and update its content using properties such as `textContent` and
`innerHTML` or using **DOM manipulation techniques**. An element node can contain multiple text nodes and
child elements that are siblings of each other. In older browsers, **_implementation of the DOM is
inconsistent (and is a popular reason for using jQuery)_**. Browsers offer tools for viewing the **DOM** tree .
