#HTML DOM Nodes
In the HTML DOM (document object model), everything is a node:

- The document itself is a document node
- All HTML elements are element nodes
- All HTML attributes are attribute nodes
- Text inside HTML elements are text nodes
- Comments are comment nodes

#The Document Object
When an HTML element is loaded into a web browser, it becomes a document object. 

The document object is the root node of the HTML document and the "owner" of all other nodes: 
(elements nodes, text nodes, attributes nodes, and comment nodes).
The document object provides properties and methods to access all node objects, from within JavaScript.

Tip: The document is part of the window object and can be accessed as window.document.

#Document Object Properties and Methods

- document.activeElement Returns the currently focused element in the document
- document.addEventListener() Attaches an event handler to the document
- document.adoptNode() Adopts a node from another document
- document.anchors Returns a collection of all <a> elements in the document that have a name attribute
- document.applets Returns a collection of all <applet> elements in the document
- document.baseURI Returns the absolute base URI of the document
- document.body Sets or returns the document's body (the <body> element)
- document.close() Closes the output stream previously closed with document.open() 

