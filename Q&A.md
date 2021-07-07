## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)

--> The `.forEach` is a shorter method of writing a `for loop` which simply calls the provided function of the element of a given array.

--> Meanwhile, `.map` method also calls the provided function in an element but it create and returns a new array.

2. Explain the difference between a callback and a higher order function.

--> `Callback` are just like normal functions that  are passed into other functions to be called a later stage and executed after a particular event occurs.

--> Meanwhile `higher order functions` are functions that uses notations and reuses it inside the given stage witout having to use loops of code to mimic its functionality.

3. What is closure?

--> Closure is one feature in Javascript giving the inside function the ability to access the outside function of a given variable.

4. Describe the four rules of the 'this' keyword.

    * The four rules of the `this` keyword:

    --> Window Binding - if none of the other rules apply, the `this` keyword defaults to the window object(global object in node) - unless you used strict in which case it defaults to undefined. 

    --> Implicit Binding - when a function is invoked `this` refers to what's left of the dot.

    --> Explicit Binding - is when we can explicitly tell the JS engine to set the  `this` keyword to point to specific value using call, apply, or bind. 

    --> New Binding - uses the `new` keyword to construct a new object, and `this` points to the new object.

5. Why do we need super() in an extended class?

    --> We need `super` keyword to call or access the function of the parent properties to avoid duplicating the constructor part of the class function.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 