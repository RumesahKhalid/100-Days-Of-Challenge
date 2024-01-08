Assignment No:03

#1.	Rewrite the following code using a ternary operator:
let result;
if (score >= 80) {
    result = "Pass";
} else {
    result = "Fail";
}

Code:

![1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/324f0393-a088-4903-b706-34b03949ded8)


Output:

![1 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/629450eb-649b-4bde-9f0f-e1b3c9164236)

 
#2.  How does the optional chaining operator (?.) work, and how can it be used to access nested properties of an object?

The optional chaining operator (?.) is a feature introduced in JavaScript (ES11/ES2020) that provides a concise and safe way to access properties of an object, especially when dealing with nested objects or properties that may be undefined or null.

Code:
Traditional Approach:


![2](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/3c3afced-919a-446b-98bd-333ac7a4593d)



Optional Chaining:



![2 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/80735d0d-b672-458b-a07a-17cdc92615fb)



Output:


![2 2](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/eadbc292-e9df-4b3e-bce4-afe776ebe715)



#3. Compare the for...in loop and the for...of loop in terms of their use cases and the types of values they iterate over.

The for...in and for...of loops are both used for iteration in JavaScript, but they have different use cases and iterate over different types of values.
for...in Loop:

Use Case:
Primarily used to iterate over the enumerable properties of an object, including inherited properties from its prototype chain.
It's often used with objects to loop through keys (property names).

Code:

     
![3](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/fa4502bf-a913-4a3a-9759-ad429fb3df60)


Output:


![3 3](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/ca75cebb-e04d-4a17-b3af-5fdcca3837b7)


for...of Loop:

Use Case:
Introduced in ECMAScript 2015 (ES6), it is used to iterate over values of iterable objects, such as arrays, strings, maps, sets, etc.
It's designed for more concise iteration over the values themselves, not the properties or keys.

Code:


![3 4](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/58e21627-b0d6-4766-a618-425623afb227)



Output:


![3 5](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/2f1c614a-f32d-4202-9ee9-2cba23340288)

  

#4. Define a function calculateAverage that takes an array of numbers as an argument and returns the average value.
   
Code:



![4](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/f8b94c65-6a63-4166-a005-afe391cb6fda)



Output:


![4 4](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/6b69d0f8-f50b-456b-8bd4-4cbec4c9ed50)



#5.  Explain the concept of "closures" in JavaScript and provide an example of their practical use.

Concept: 
A closure is a JavaScript feature that allows a function to access variables from its outer (enclosing) scope, even after the outer function has finished executing. It essentially "closes over" the variables it needs, preserving their values.

Code:



![5](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/e8808538-4bf1-455d-abc8-292ca7bfb921)




Output:


![5 5](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/fde4249d-bbe4-4242-81ab-1a3157bb8bb1)


#6. Create an object named student with properties name, age, and grades. Add a method calculateAverage that calculates the average of the grades.

Code:


![6](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/58c2966c-0975-4842-a937-7f645116420c)




Output:


![6 6](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/478647d8-8943-4f8a-adbf-0b0564616199)
 

#7. How can you clone an object in JavaScript and also give one example each deep copy, shallow copy, and reference copy

Cloning an object in JavaScript can be done using various methods, and each method has different implications for copying. Here are examples for deep copy, shallow copy, and reference copy

Deep Copy:
A deep copy creates a completely independent copy of the object, including nested objects, so changes to the original object or its nested objects won't affect the copy.

Code:

![7](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/6c09588d-2c3a-49c2-84c1-9bb341e7b150)


Output:	

![7 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/9d256f85-ce48-4da2-a86f-f7c3103b7196)


Shallow Copy:
A shallow copy creates a new object, but it only copies the references to the nested objects. Changes to the properties of the nested objects are reflected in both the original and the copied objects.

Code:


![7 2](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/8de5bdb2-c895-4293-af9a-38d3a3f007d0)



Output:	


![7 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/9d256f85-ce48-4da2-a86f-f7c3103b7196)



Reference Copy:
A reference copy simply copies the reference to the original object, so changes to the properties of the original object are reflected in the copied object and vice versa.

Code:


![7 4](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/afb1dcfb-0762-48de-bf6e-80e9d2d47d6c)



Output:	

![7 5](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/697aca79-692d-47e3-86c7-7b112735e175)


#8. Write a loop that iterates over an array of numbers and logs whether each number is even or odd, using a ternary operator.

Code:


![8](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/570014db-5fed-462b-a9ff-2ebee5b17119)



Output:


![8 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/9d6b847c-3ea1-42d5-8245-1abfcc3af27c)


#9. Describe the differences between the for loop, while loop, and do...while loop in JavaScript. When might you use each?

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


#10. Provide an example of using optional chaining within a loop to access a potentially missing property of an object.

Code:


![10](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/632d1104-90f2-4247-b204-e05bf26fd75e)



Output:


![10 2](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/7f02181b-e4a7-4909-8239-b7f2632f4146)



#11. Write a for...in loop that iterates over the properties of an object and logs each property name and value.

Code:


![11](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/76b130e2-8ef7-4cb8-b9a2-26d9e5983829)



Output:


![11 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/4c8a67d1-1722-49e7-a69a-8b239cab7f69)


•	The for...in loop is used to iterate over the properties of the sampleObject.

•	The loop variable property represents the property name at each iteration.

•	Inside the loop, sampleObject[property] is used to access the value associated with the current property.

•	The console.log statement logs each property name and its corresponding value.


#12. Explain the use of the break and continue statements within loops. Provide scenarios where each might be used.

Break Statement:

The break statement is used to exit a loop prematurely, before the loop condition is false or before all iterations are completed. It is often used to terminate the loop when a certain condition is met.

Use Cases for break:

1. Searching or Filtering: If you find the item you are looking for, you can break out of the loop.
2. Limiting Iterations: Exit the loop early if a certain condition is satisfied.
3. Handling Errors: Break out of a loop if an error condition is encountered.

continue Statement:

The continue statement is used to skip the rest of the code in the current iteration and proceed to the next iteration of the loop. It allows you to bypass certain parts of the loop's body based on a condition.

Use Cases for continue:

1. Skipping Unwanted Elements: Continue to the next iteration without processing specific elements.
2. Avoiding Redundant Code: Skip unnecessary code execution based on certain conditions.
3. Filtering Items: Use it to filter out items from being processed in a loop.

Scenario Examples:

Using break:

Suppose you are searching for a specific item in an array:



![12](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/4a78bb4a-df9c-4bf8-98ce-fd107e072879)



![12 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/4fbfa813-a7e6-445f-a382-e1ddfcf1fcbf)



Using continue:

Suppose you want to process only positive numbers in an array:


![12 2](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/7f71d294-9335-4d13-9218-64fd4f2cc50f)



![12 3](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/a8569990-207f-4e42-953c-1dfbc2f006a3)





#13. Write a function calculateTax that calculates and returns the tax amount based on a given income. Use a ternary operator to determine the tax rate.
    
Code:


![13](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/888ebdf8-e3f5-4ff7-b2e5-1b20a5d6f07f)



Output:


![13 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/6cdfc8f0-baad-4199-93e1-85dbf250de26)



#14. Create an object car with properties make, model, and a method startEngine that logs a message. Instantiate the object and call the method.
    
Code:


![14](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/13e515c7-1afe-4c53-b728-3763d5136077)




Output:


![14 1](https://github.com/RumesahKhalid/100-Days-Of-Challenge/assets/112583410/dd33f997-f749-46db-99d7-bfbaa13b8dc7)



#15. Explain the differences between regular functions and arrow functions in terms of scope, this binding, and their use as methods.
    
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

5. Use Cases:
   
Regular Functions:

•	Use when you need the flexibility of dynamic this binding (e.g., in object methods).

•	When you need access to the arguments object.

•	In scenarios where this needs to be determined at runtime.

Arrow Functions:

•	Use when you want to inherit this from the enclosing scope (lexical scoping).

•	For concise, short functions, especially in functional programming.

•	When you want to avoid the arguments object and prefer rest parameters.


