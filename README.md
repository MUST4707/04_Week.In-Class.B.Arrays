Introduction to Arrays
======================

An **array** is a data structure that allows you to store multiple values in a single variable. Each value in an array is called an **element**, and each element has a numbered position called an **index**.

Defining an Array
-----------------

Arrays in JavaScript can be defined using square brackets:

`let fruits = ["Apple", "Banana", "Cherry"];`

Accessing Elements with Bracket Notation
----------------------------------------

Array elements are accessed using their index, starting from `0` by typing the array name followed by `[]` with the index number inside.:

`console.log(fruits[0]); // Apple`

You can also access elements using a dynamic index using variables:

`let index = 2;   console.log(fruits[index]); // Cherry`

### Understanding `Bracket Notation`

When you write `myArray[0]`, you are accessing the first element of the array. `myArray[0]` accesses the second element and so on.

*   **Indexing Starts at 0**: Arrays in JavaScript are zero-indexed, meaning the first element is at index `0`.
*   **Retrieving a Value**: `myArray[0]` gets the first element:
    `let myArray = ["Apple", "Banana", "Cherry"];   console.log(myArray[0]); // Apple`*   **Modifying a Value**: You can change the value at index `0`:
    `myArray[0] = "Mango";   console.log(myArray); // ["Mango", "Banana", "Cherry"]`*   **Accessing Out-of-Bounds Indexes**: If you try to access an index that doesn’t exist:
    `console.log(myArray[10]); // undefined`

Array Length
------------

The `length` property returns the number of elements in an array:

`console.log(fruits.length); // 3`

Adding and Removing Elements
----------------------------

*   **push()**: Adds an element to the end of the array.
    `fruits.push("Orange"); // ["Apple", "Banana", "Cherry", "Orange"]`*   **pop()**: Removes the last element from the array.
    `fruits.pop(); // ["Apple", "Banana", "Cherry"]`*   **unshift()**: Adds an element to the beginning of the array.
    `fruits.unshift("Mango"); // ["Mango", "Apple", "Banana", "Cherry"]`*   **shift()**: Removes the first element from the array.
    `fruits.shift(); // ["Apple", "Banana", "Cherry"]`

Conclusion
----------

Arrays are powerful tools for managing collections of data in JavaScript. Understanding how to define, access, and modify arrays is essential for effective programming.