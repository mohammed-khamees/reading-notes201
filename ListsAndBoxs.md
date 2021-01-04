# Lists And Boxes in the HTML and CSS

There are three types of HTML lists:

- ordered

ordered list example:
`<ol>`
`<li>content</li>`
`<li>content</li>`
`<li>content</li>`
`</ol>`

- unordered

unordered list example:
`<ul>`
`<li>content</li>`
`<li>content</li>`
`<li>content</li>`
`</ul>`

- definition
  `<dl>`
  `<dt>content</dt>`
  `<dd>content</dd>`
  `<dt>content</dt>`
  `<dd>content</dd>`
  `</dl>`

**Ordered lists** use => numbers.
**Unordered lists** use => bullets.
**Definition lists** are used to define terminology.

Also,Lists can be nested inside one another like this:
`<ul>`
`<li>content</li>`
`<li>`
`<ul>`
`<li>content</li>`
`<li>content</li>`
`</ul>`
`</li>`
`<li>content</li>`
`</ul>`

**CSS** treats each HTML element as if it has its own box. You can use **CSS** to control the dimensions of a box.
You can also control the borders, margin and padding for each box with **CSS**. It is possible to hide elements using the **display** and
_visibility_ properties. _Block-level_ boxes can be made into _inline boxes_, and **_inline boxes made into block-level boxes_**. Legibility can be improved by controlling the _width_ of boxes containing text and the leading. **CSS3** has introduced the ability to create image
_borders_ and _rounded borders_.
