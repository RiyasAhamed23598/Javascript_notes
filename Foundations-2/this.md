# This keyword

- We know that inside GEC `this` refers to the global window object.
- But what does `this` refers to inside of a function?
- `this` refers to whatever is on the left of the . (dot) when calling a method.
- When we do obj.someFn(), `this` will refer to the obj.
- If we use `use script` inside a function, `this` will be undefined.
- Provinding some additional data to our function in the form of this.


## Why do we need this keyword

 - Suppose we have an object with some properties and methods.
 - To get access of the object from within a method, we use `this`.
 - Execute same code for multiple objects without taking object as argument.
