# This keyword

- We know that inside GEC `this` refers to the global window object.
- But what does `this` refers to inside of a function?
- `this` refers to whatever is on the left of the . (dot) when calling a method.
- When we do obj.someFn(), `this` will refer to the obj. It's like who called me.
- If we use `use script` inside a function, `this` will be undefined.
- Provinding some additional data to our function in the form of this.


## Why do we need this keyword

 - Suppose we have an object with some properties and methods.
 - To get access of the object from within a method, we use `this`.
 - Execute same code for multiple objects without taking object as argument.

## Lexical and dynamic scope

- Lexical means where it is written that determinses it's scope.
- Dynamic means where it is invoked from.
- `this` keyword follows dynamic scope. It doesn't matter where the function is written but how it is invoked that will determine it's value.

