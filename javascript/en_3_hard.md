What method is used to get a list of enumerable properties of an object in JavaScript?
- Object.keys
- Object.values
- Object.entries

What is the behavior of the `Object.freeze()` method?
- Prevents modification of object properties
- Allows deletion of object properties
- Clones the object into a new object

Which array method is used to find the first element that satisfies a condition specified by a function?
- find
- filter
- some

What is the main difference between `Object.assign()` and the spread operator (`...`)?
- `Object.assign()` performs a shallow copy while the spread operator can perform a deep copy
- The spread operator performs a shallow copy while `Object.assign()` performs a deep copy
- `Object.assign()` cannot copy nested objects while the spread operator can

How can you access an object's property using a string as the property name?
- obj[propertyName]
- obj.propertyName
- obj->propertyName

What method is used to get the internal class of an object in JavaScript?
- Object.prototype.toString.call(obj)
- obj.getClass()
- obj.constructor.name

What feature of arrow functions makes them different from traditional functions?
- They do not have their own `this` and use the `this` from the lexical context
- They are faster in execution
- They allow a greater number of parameters

What is the purpose of the `Reflect.apply()` method in JavaScript?
- Allows invoking a function with a specific context and arguments
- Creates a new function from an existing function
- Changes the context of `this` in a function

How can you ensure a function is executed only once?
- Using a singleton design pattern or a `Set`
- Calling the function within a loop
- Defining the function as `async`

Which `Promise` function is used to handle multiple promises in parallel?
- Promise.all
- Promise.race
- Promise.any

What method is used to create a function that runs only after a certain number of calls?
- debounce
- throttle
- once

What is the result of `Object.getPrototypeOf(Object.create(null))`?
- null
- Object.prototype
- undefined

What method is used to combine multiple arrays into a single array without modifying the original arrays?
- concat
- push
- merge

What is the difference between `null` and `undefined` in JavaScript?
- `null` is an explicitly assigned value, while `undefined` indicates the absence of assignment
- Both are values indicating the absence of value
- `undefined` is an explicitly assigned value, while `null` indicates the absence of assignment

How can you check if a function is a constructor (i.e., can be used with the `new` operator)?
- Checking if the function has a `prototype` property
- Verifying if the function has a name
- Evaluating if the function returns a value

What method is used to define a static method in a class?
- static
- prototype
- instance

What is the purpose of the `Symbol.for()` method in JavaScript?
- Create or retrieve a global symbol that can be shared across different parts of the code
- Create a new unique symbol for each call
- Convert a symbol into a string

What technique is used to create a function that returns another function in JavaScript?
- Currying
- Memoization
- Closures

How can you handle errors in a promise using `async/await`?
- Using `try` and `catch`
- Using `finally`
- Using `resolve` and `reject`

What method is used to change the context of a function?
- bind
- apply
- call

What operator is used to define a getter or setter in a class?
- get/set
- define/get
- function/get

What is the behavior of the `Array.prototype.flat()` method?
- Flattens a nested array into a single level
- Creates a new array without duplicate elements
- Sorts the elements of an array

What is the difference between `Object.seal()` and `Object.preventExtensions()`?
- `Object.seal()` prevents the addition of new properties and marks existing properties as non-configurable, while `Object.preventExtensions()` only prevents the addition of new properties
- `Object.seal()` only prevents the addition of new properties, while `Object.preventExtensions()` also prevents the deletion of properties
- `Object.seal()` does not allow modification of existing properties, while `Object.preventExtensions()` allows modification of existing properties

What is the purpose of the `Object.create()` method in JavaScript?
- Create a new object with the specified prototype
- Clone an existing object
- Define a new class

What function is used to perform an operation on each element of an array and return a new array with the results?
- map
- reduce
- forEach

How can you handle the error of a promise using `Promise.all()`?
- `Promise.all()` returns a promise that is rejected if any of the promises in the array are rejected
- `Promise.all()` handles the error without rejecting any promises
- `Promise.all()` returns a promise that is resolved if all the promises in the array are resolved

What method is used to get a list of key-value pairs from an object?
- Object.entries
- Object.keys
- Object.values

What is the difference between `Object.prototype.hasOwnProperty()` and `in` in property checking?
- `Object.prototype.hasOwnProperty()` checks if the property is a direct property of the object, while `in` checks if the property exists on the object or its prototype chain
- `in` checks if the property is a direct property of the object, while `Object.prototype.hasOwnProperty()` checks if the property exists on the object or its prototype chain
- Both check if the property is a direct property of the object or on its prototype chain