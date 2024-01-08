Assignment No:03

1.	Rewrite the following code using a ternary operator:
let result;
if (score >= 80) {
    result = "Pass";
} else {
    result = "Fail";
}

Code:
![1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/324f0393-a088-4903-b706-34b03949ded8)

Output:
 

2.  How does the optional chaining operator (?.) work, and how can it be used to access nested properties of an object?
The optional chaining operator (?.) is a feature introduced in JavaScript (ES11/ES2020) that provides a concise and safe way to access properties of an object, especially when dealing with nested objects or properties that may be undefined or null.
Code:
Traditional Approach:







Optional Chaining:








Output:



3. Compare the for...in loop and the for...of loop in terms of their use cases and the types of values they iterate over.
The for...in and for...of loops are both used for iteration in JavaScript, but they have different use cases and iterate over different types of values.
for...in Loop:
Use Case:
Primarily used to iterate over the enumerable properties of an object, including inherited properties from its prototype chain.
It's often used with objects to loop through keys (property names).
Code:

     



Output:



for...of Loop:
Use Case:
Introduced in ECMAScript 2015 (ES6), it is used to iterate over values of iterable objects, such as arrays, strings, maps, sets, etc.
It's designed for more concise iteration over the values themselves, not the properties or keys.
Code:




Output:



  

4. Define a function calculateAverage that takes an array of numbers as an argument and returns the average value.
Code:







Output:






5.  Explain the concept of "closures" in JavaScript and provide an example of their practical use.
Concept: 
A closure is a JavaScript feature that allows a function to access variables from its outer (enclosing) scope, even after the outer function has finished executing. It essentially "closes over" the variables it needs, preserving their values.
Code:







Output:



6. Create an object named student with properties name, age, and grades. Add a method calculateAverage that calculates the average of the grades.
Code:











Output:
 


7. How can you clone an object in JavaScript and also give one example each deep copy, shallow copy, and reference copy
Cloning an object in JavaScript can be done using various methods, and each method has different implications for copying. Here are examples for deep copy, shallow copy, and reference copy
1. Deep Copy:
A deep copy creates a completely independent copy of the object, including nested objects, so changes to the original object or its nested objects won't affect the copy.
Code:




Output:	


2. Shallow Copy:
A shallow copy creates a new object, but it only copies the references to the nested objects. Changes to the properties of the nested objects are reflected in both the original and the copied objects.

Code:




Output:	


 
Reference Copy:
A reference copy simply copies the reference to the original object, so changes to the properties of the original object are reflected in the copied object and vice versa.
Code:




Output:	



8. Write a loop that iterates over an array of numbers and logs whether each number is even or odd, using a ternary operator.
Code:






Output:






9. Describe the differences between the for loop, while loop, and do...while loop in JavaScript. When might you use each?
For Loop:
Use Case: Known number of iterations, often for arrays.

While Loop:
Use Case: Unknown number of iterations determined by a condition.
Do...While Loop:
Use Case: Similar to while but guarantees at least one execution.
When to Use Each:
For Loop: Known iterations, especially for arrays.
While Loop: Unknown iterations based on a condition.
Do...While Loop: Ensure at least one execution, even if the condition is initially false.


10. Provide an example of using optional chaining within a loop to access a potentially missing property of an object.
Code:








Output:




11. Write a for...in loop that iterates over the properties of an object and logs each property name and value.
Code:




Output:



•	The for...in loop is used to iterate over the properties of the sampleObject.
•	The loop variable property represents the property name at each iteration.
•	Inside the loop, sampleObject[property] is used to access the value associated with the current property.
•	The console.log statement logs each property name and its corresponding value.


12. Explain the use of the break and continue statements within loops. Provide scenarios where each might be used.
Break Statement:
The break statement is used to exit a loop prematurely, before the loop condition is false or before all iterations are completed. It is often used to terminate the loop when a certain condition is met.
Use Cases for break:
Searching or Filtering: If you find the item you are looking for, you can break out of the loop.
Limiting Iterations: Exit the loop early if a certain condition is satisfied.
Handling Errors: Break out of a loop if an error condition is encountered.
continue Statement:
The continue statement is used to skip the rest of the code in the current iteration and proceed to the next iteration of the loop. It allows you to bypass certain parts of the loop's body based on a condition.
Use Cases for continue:
Skipping Unwanted Elements: Continue to the next iteration without processing specific elements.
Avoiding Redundant Code: Skip unnecessary code execution based on certain conditions.
Filtering Items: Use it to filter out items from being processed in a loop.
Scenario Examples:
Using break:
Suppose you are searching for a specific item in an array:









Using continue:
Suppose you want to process only positive numbers in an array:











13. Write a function calculateTax that calculates and returns the tax amount based on a given income. Use a ternary operator to determine the tax rate.
Code:







Output:


14. Create an object car with properties make, model, and a method startEngine that logs a message. Instantiate the object and call the method.
Code:



\



Output:



15. Explain the differences between regular functions and arrow functions in terms of scope, this binding, and their use as methods.
1. Scope:
Regular Functions:
•	Have their own this binding.
•	Create a new this context when invoked.
Arrow Functions:
•	Inherit this from the enclosing scope.
2. this Binding:
Regular Functions:
•	Have dynamic this binding, determined by how the function is called (e.g., as a method, standalone function, etc.).
Arrow Functions:
•	Inherit this from the surrounding lexical context (the context in which they are defined).
3. Use as Methods:
Regular Functions:
•	Suitable for use as object methods due to their dynamic this binding.

Arrow Functions:
•	Not suitable as object methods if dynamic this binding is required; instead, use regular functions.
4. Arguments Object:
Regular Functions:
•	Have access to the arguments object, which holds all arguments passed to the function.
Arrow Functions:
•	Do not have their own arguments object; it inherits from the enclosing scope.
Use Cases:
Regular Functions:
•	Use when you need the flexibility of dynamic this binding (e.g., in object methods).
•	When you need access to the arguments object.
•	In scenarios where this needs to be determined at runtime.
Arrow Functions:
•	Use when you want to inherit this from the enclosing scope (lexical scoping).
•	For concise, short functions, especially in functional programming.
•	When you want to avoid the arguments object and prefer rest parameters.


