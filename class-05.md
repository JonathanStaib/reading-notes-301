# Class 05 Reading Notes

## React Docs - Thinking in React

1. A single responsibility principle is the idea that a component should only ideally do one thing. If it grows too much then decompress it.

2. A static app would be building components that reuse other components and pass data using props. These should not use state at all. 

3. Once you have a static app you need to make it interactive with the user!

4. The three questions are :
       1. Is it passed in from a parent via props? If so, it probably isn’t state.
       2. Does it remain unchanged over time? If so, it probably isn’t state.
       3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

5. You need to find the parent component. State should always reside there.

## Higher-Order Functions

1. Higher Order functions are functions that run off other functions.

2. line two is only returning values where the new value being brought in this function(m) is greater than the value being passed in(n).

3. The map method goes through an array and returns a new array with teh same length as the original you mapped through. You can make other changes by chaining.
