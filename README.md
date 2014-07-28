This is a jQuery plugin which highlights the occurances of a text in the given web page.

It does not match the node names (<script>, <textarea>, etc) but does match the same if found in the text. 

Example usage: 

    $('body').highlight('text', 'className')

Here, `className` argument is optional. 

When a match occurs, the matching text is wrapped with a `span` element, and the `className` class attribute is added to the span. If no argument is specified, the classname applied is `highlight-class`


An example fiddle:

> http://jsfiddle.net/karthikr12/T3Tnu/
