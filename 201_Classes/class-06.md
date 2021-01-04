# **03/01/2021**

*FUNCTION DECLARATION*

A function declaration creates a function that you
can ca ll later in your code. It is the type of function
you have seen so far in this book.
In order to call the function later in your code, you
must give it a name, so these are known as named
functions. Below, a function called area() is
declared, which can then be called using its name.

function area (width, height)
return width * height;
};
var size= area(3, 4) ;

*FUNCTION EXPRESSION*

If you put a function where the interpreter would
expect to see an expression, then it is treated as an
expression, and it is known as a function expression.
In function expressions, the name is usually omitted.
A function with no name is called an anonymous
function. Below, the function is stored in a variable
called area. It can be called like any function created
with a function declaration.

var ar ea = f unction(width, height) {
r eturn width * height;
} ;
var size = area(3, 4) ;

*IMMEDIATELY INVOKED FUNCTION EXPRESSIONS (llFE)*

Pronounced "iffy," these functions are not given
a name. Instead, they are executed once as the
interpreter comes across them.
Below, the variable called area will hold the value
returned from the function (rather than storing the
function itself so that it can be called later).

var area = (function() {
var wi dth = 3;
var height = 2;
return widt h * height;
})();

*IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES*

If a variable is part of an object, it is called a
property. Properties te ll us about the object, such as
the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name
and a different number of rooms.

*IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS*

If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms.

var hotel = {
name: 'Quay',
rooms : 40,
booked: 25,
checkAvailability: function() {
    return this.rooms - this.booked;
}
};

The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

*MAKING A MODEL OF THE HTML PAGE*
When the browser loads a web page, it
creates a model of the page in memory.
The DOM specifies the way in which the
browser should structure this model using
a DOM tree.
The DOM is called an object model
because the model (the DOM tree) is
made of objects.

ACCESSING AND CHANGING
THE HTML PAGE
The DOM also defines methods and
properties to access and update each
object in this model, which in turn updates
what the user sees in the browser.
You will hear people call the DOM an
Application Programming Interface (API).
User interfaces let humans interact with
programs; APls let programs (and scripts)
talk to each other. The DOM states what
your script can "ask the browser about the
current page, and how to tell the browser
to update what is being shown to the user.

As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.
THE DOCUMENT NODE
ELEMENT NODES
ATTRIBUTE NODES
TEXT NODES

Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes.

document.getElementByid('one');