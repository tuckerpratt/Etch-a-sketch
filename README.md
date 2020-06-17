# Etch-a-sketch

This project was to create something like an Etch-a-sketch. Through it, I learned
how to manipulate objects in the DOM, how to use CSS Grid, and how to use event 
handlers. One of the most difficult things was to be able to target the specific 
properties of certain objects, and getting the squares to change color. This lead me 
to learn the difference between an attribute and a property. As I understand it, an
attribute is something that is initialized with and object and doesn't really change, 
whereas a property can be changed and has an effect on the current state of the object
to which it belongs. Also, I'm not sure why, but using QuerySelectorAll seems to be a 
better move than selectobjectsbyclassname. The latter did not allow me to change 
properties of the objects in the list, but query selector did. Maybe queryselector 
creates a reference to each object, and selectobjects creates an array of them that
would need to be iterated over??