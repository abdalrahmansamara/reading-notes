# Object Literals
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.    
IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES   
If a variable is part of an object, it is called a
property. Properties te ll us about the object, such as
the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name
and a different number of rooms.   
IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS   
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms.   
In JavaScript:   
• Variables have a name and you can assign them a
value of a string, number, or Boolean.   
• Arrays have a name and a group of values. (Each
item in an array is a name/value pair because it
has an index number and a value.)   
• Named functions have a name and value that is a
set of statements to run if the function is called.   
• Objects consist of a set of name/value pairs
(but the names are referred to as keys).   
# Document Object Model
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.   
The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules.
It is implemented by all major browser makers, and covers two primary areas:   
* MAKING A MODEL OF THE HTML PAGE   
* ACCESSING AND CHANGING THE HTML PAGE    
## THE DOM TREE IS A MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.   
* ATTRIBUTE NODES   
The opening tags of HTML elements can carry
attributes and these are represented by attribute
nodes in the DOM tree.
Attribute nodes are not children of the element thar
carries them; they are part of that element. Once
you access an element, there are specific JavaScript
methods and properties to read or change that
element's attributes. For example, it is common to
change the values of cl ass attributes to trigger new
CSS rules that affect their presentation.   
* TEXT NODES
Once you have accessed an element node, you
can then reach the text within that element. This is
stored in its own text node.
Text nodes cannot have children. If an element
contains text and another child element, the child
element is not a child of the text node but rather
a child of the containing element. (See the `<em>`
element on the first `<li>` item.) This illustrates how
the text node is always a new branch of the DOM
tree, and no further branches come off of it.   
Accessing and updating the DOM tree involves two steps:   
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.   
### GROUPS OF ELEMENT NODES
If a method can return more than one node, it will
always return a Nodelist, which is a collection of
nodes (even if it only finds one matching element).
You then need to select the element you want from
this list using an index number (which means the
numbering starts at 0 like the items in an array).   
### FASTEST ROUTE
Finding the quickest way to access an element
within your web page will make the page seem
faster and/or more responsive. This usually means
evaluating the minimum number of nodes on the
way to the element you want to work with. For
example, getEl ementByld () will quickly return one
element (because no two elements on the same
page should have the same value for an id attribute),
but it can only be used when the element you want
to access has an id attribute.   
The Document Object Model (DOM) is a programming API for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated. In the DOM specification, the term "document" is used in the broad sense - increasingly, XML is being used as a way of representing many different kinds of information that may be stored in diverse systems, and much of this would traditionally be seen as data rather than as documents. Nevertheless, XML presents this data as documents, and the DOM may be used to manage this data.

With the Document Object Model, programmers can create and build documents, navigate their structure, and add, modify, or delete elements and content. Anything found in an HTML or XML document can be accessed, changed, deleted, or added using the Document Object Model, with a few exceptions - in particular, the DOM interfaces for the internal subset and external subset have not yet been specified.

As a W3C specification, one important objective for the Document Object Model is to provide a standard programming interface that can be used in a wide variety of environments and applications. The Document Object Model can be used with any programming language. In order to provide precise, language-independent specification of the Document Object Model interfaces, we have chosen to define the specifications in OMG IDL, as defined in the CORBA 2.2 specification. In addition to the OMG IDL specification, we provide language bindings for Java and ECMAScript (an industry-standard scripting language based on JavaScript and JScript). Note: OMG IDL is used only as a language-independent and implementation-neutral way to specify interfaces. Various other IDLs could have been used; the use of OMG IDL does not imply a requirement to use a specific object binding runtime.    
In the Document Object Model, documents have a logical structure which is very much like a tree; to be more precise, it is like a "forest" or "grove" which can contain more than one tree. However, the Document Object Model does not specify that documents be implemented as a tree or a grove , nor does it specify how the relationships among objects be implemented in any way. In other words, the object model specifies the logical model for the programming interface, and this logical model may be implemented in any way that a particular implementation finds convenient. In this specification, we use the term structure model to describe the tree-like representation of a document; we specifically avoid terms like "tree" or "grove" in order to avoid implying a particular implementation. One important property of DOM structure models is structural isomorphism: if any two Document Object Model implementations are used to create a representation of the same document, they will create the same structure model, with precisely the same objects and relationships.    
The name "Document Object Model" was chosen because it is an "object model" is used in the traditional object oriented design sense: documents are modeled using objects, and the model encompasses not only the structure of a document, but also the behavior of a document and the objects of which it is composed. In other words, the nodes in the above diagram do not represent a data structure, they represent objects, which have functions and identity. As an object model, the Document Object Model identifies:   
1. the interfaces and objects used to represent and manipulate a document
2. the semantics of these interfaces and objects - including both behavior and attributes
3. the relationships and collaborations among these interfaces and objects   
## Where the Document Object Model came from
The Document Object Model originated as a specification to allow JavaScript scripts and Java programs to be portable among web browsers. Dynamic HTML was the immediate ancestor of the Document Object Model, and it was originally thought of largely in terms of browsers. However, when the Document Object Model Working Group was formed, it was also joined by vendors in other domains, including HTML or XML editors and document repositories. Several of these vendors had worked with SGML before XML was developed; as a result, the Document Object Model has been influenced by SGML Groves and the HyTime standard. Some of these vendors had also developed their own object models for documents in order to provide programming APIs for SGML/XML editors or document repositories, and these object models have also influenced the Document Object Model.   
## DOM Interfaces and DOM Implementations
The DOM specifies interfaces which may be used to manage XML or HTML documents. It is important to realize that these interfaces are an abstraction - much like "abstract base classes" in C++, they are a means of specifying a way to access and manipulate an application's internal representation of a document. In particular, interfaces do not imply a particular concrete implementation. Each DOM application is free to maintain documents in any convenient representation, as long as the interfaces shown in this specification are supported. Some DOM implementations will be existing programs that use the DOM interfaces to access software written long before the DOM specification existed. Therefore, the DOM is designed to avoid implementation dependencies; in particular,   
1. Attributes defined in the IDL do not imply concrete objects which must have specific data members - in the language bindings, they are translated to a pair of get()/set() functions, not to a data member. (Read-only functions have only a get() function in the language bindings).
2. DOM applications may provide additional interfaces and objects not found in this specification and still be considered DOM compliant.
3. Because we specify interfaces and not the actual objects that are to be created, the DOM can not know what constructors to call for an implementation. In general, DOM users call the createXXX() methods on the Document class to create document structures, and DOM implementations create their own internal representations of these structures in their implementations of the createXXX() functions.   
# Limitations of Level One
1. A structure model for the internal subset and the external subset.
2. Validation against a schema.
3. Control for rendering documents via stylesheets.
4. Access control.
5. Thread-safety.
## DOM and JavaScript
The short example above, like nearly all of the examples in this reference, is JavaScript. That is to say, it's written in JavaScript, but it uses the DOM to access the document and its elements. The DOM is not a programming language, but without it, the JavaScript language wouldn't have any model or notion of web pages, HTML documents, XML documents, and their component parts (e.g. elements). Every element in a document—the document as a whole, the head, tables within the document, table headers, text within the table cells—is part of the document object model for that document, so they can all be accessed and manipulated using the DOM and a scripting language like JavaScript.   

In the beginning, JavaScript and the DOM were tightly intertwined, but eventually, they evolved into separate entities. The page content is stored in the DOM and may be accessed and manipulated via JavaScript.   
## Event Propagation
Suppose a page contained input button element contained within a p element, contained within a div element. If you clicked on the button element, which click handler(s) should fire: the click handler for the button, the p element or the div element? The answer is all of them.   
When you click on the button, the event handler on the button fires first. Next, the event handler on the parent p element is invoked. Finally, the event handlers on the parent div element is invoked.   
This behavior is known as event propagation or event bubbling. When an event is fired, the element’s event handlers are first fired. The element’s parent’s event handlers are fired. That element’s parent’s event handlers are fired, and so on, until the root Document object is reached. Most DOM events exhibit event propagation.   