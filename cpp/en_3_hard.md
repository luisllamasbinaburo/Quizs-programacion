What does the 'typeid' operator do in C++?
- Returns the data type at runtime
- Returns the size of the data type
- Converts one data type to another

What is a 'vtable' in C++?
- A table of pointers to virtual functions
- A table of global variables
- A table of static functions

What is a 'functor' in C++?
- An object that behaves like a function
- A special type of function pointer
- A function that operates on pointers

What is the 'heap' in C++?
- The region of dynamic memory
- The region of static memory
- The space where pointers are stored

What is 'stack unwinding' in C++?
- The process of cleaning up the call stack during exception handling
- The process of allocating memory on the stack
- The process of loop optimization at compile time

What is 'RTTI' in C++?
- Runtime Type Information
- Real-Time Threading Interface
- Register Transfer Timing Information

What does the 'volatile' keyword do in C++?
- Indicates that a variable may be modified at any time by processes outside the control of the code
- Prevents a variable from being optimized by the compiler
- Declares a variable as immutable

What is 'placement new' in C++?
- A technique for constructing an object in a previously allocated memory location
- A way to allocate memory on the stack instead of the heap
- A mechanism for optimizing dynamic memory allocation

What is 'template metaprogramming' in C++?
- A technique for performing compile-time calculations using templates
- A method for automatically generating source code
- A mechanism for optimizing templates at runtime

What does 'constexpr' mean in C++?
- An expression that is evaluated at compile time
- An expression that is evaluated at runtime
- An expression that returns a constant pointer

What is the concept of 'move semantics' in C++?
- Allows for the efficient transfer of resources from one object to another without making copies
- Prevents operator overloading of assignment
- Optimizes code for mathematical operations

What does the 'std::forward' function do in C++?
- Preserves the reference type of an argument for function invocation
- Converts a data type into a pointer
- Returns a pointer to a function

What is a 'smart pointer' in C++?
- An object that simulates a pointer but automatically manages memory
- A pointer that points to multiple memory addresses
- A pointer that adapts to different data types

What does the 'std::unique_ptr' function do in C++?
- Manages the unique ownership of a resource and automatically frees it when no longer needed
- Allows sharing the ownership of a resource among multiple pointers
- Creates a deep copy of a pointer

What is a 'deadlock' in C++?
- A situation where two or more threads are permanently blocked waiting for resources from each other
- A state where a program stops responding due to an infinite loop
- A situation where a null pointer is dereferenced

What does 'RAII' stand for in resource management in C++?
- Resource Acquisition Is Initialization
- Resource Allocation In Interrupts
- Resource Assignment Is Immediate

What is a 'forward declaration' in C++?
- A declaration of a function or class before its full definition
- An instruction to move a pointer to the next element
- A technique for optimizing loop usage

What is a 'thread-safe function' in C++?
- A function that can be safely executed in a multithreaded environment without causing synchronization issues
- A function that runs in a single thread only
- A function that always returns the same value

What does the 'std::async' function do in C++?
- Launches an asynchronous task in a separate thread
- Synchronizes the execution of multiple threads
- Blocks execution until a task is complete

What is 'nullptr' in C++?
- A specific null pointer literal that replaces NULL
- A function that returns a null pointer
- A special pointer type used in smart pointers

What is a 'regular expression' in C++?
- A sequence of characters forming a search pattern
- An expression that always evaluates to true or false
- An expression that only contains basic arithmetic operations

What is a 'forward list' in C++?
- A singly linked list
- A list that only allows insertion of elements at the end
- A list that does not allow duplicates

What is a 'race condition' in C++?
- A situation where the behavior of a program depends on the order of execution of threads
- A condition where an exception occurs due to a null pointer
- A scenario where two functions compete for the same resource

What is a 'lambda capture' in C++?
- A mechanism to capture variables from the surrounding context within a lambda expression
- A process for capturing the output of a lambda function
- A technique for optimizing lambda functions at runtime

What does the 'std::bind' function do in C++?
- Binds arguments to a function, creating a new partial function
- Converts a function into a function pointer
- Merges two functions into one

What is a 'tuple' in C++?
- A collection of elements of different types
- An array of pointers
- A special type of smart pointer

What is a 'shared_ptr' in C++?
- A smart pointer that shares ownership of the pointed-to object with other 'shared_ptr'
- A pointer that can dynamically change type
- A pointer that guarantees exclusive access to a resource

What is a 'function object' in C++?
- An object that behaves like a function by overloading the `()` operator
- A function that returns an object
- A special type of function that can be called with pointers

What is a "functor" in C++ and how is it defined?
- A class that overloads the `()` operator
- A class that defines a static method
- A function passed as an argument

What is the difference between `std::vector` and `std::array` in C++?
- `std::vector` is dynamic and can change size; `std::array` is fixed-size
- `std::array` is dynamic and can change size; `std::vector` is fixed-size
- `std::vector` stores elements of different types; `std::array` only stores one type

How is type conversion performed using `reinterpret_cast`?
- To safely convert between data types at the bit level
- To perform conversions between pointers to unrelated types
- To convert between pointers to base and derived classes

What is the "Rule of Five" in C++11 and when does it apply?
- The need to explicitly define a copy constructor, destructor, copy assignment operator, move constructor, and move assignment operator when managing dynamic resources
- The need to define five methods in a class for correct functionality
- The requirement to define five overloaded operators in a class

How is a "template alias" defined in C++?
- Using the syntax `template <typename T> using Alias = Type<T>;`
- Using `typedef template <typename T> Alias = Type<T>;`
- Using `template <typename T> Alias<Type<T>>;`

What is "type_traits" in C++ and how is it used?
- A library that provides templates for querying and modifying type properties at compile time
- A library that allows dynamic conversion between types
- A library that defines operators for data types

How is template specialization done in C++?
- By defining a specific version of a template for a particular type
- By defining a template without parameters
- By using the `template` operator in the body of a function

What is a "constexpr" expression and how is it used?
- An expression whose value can be evaluated at compile time
- An expression that allows evaluation at runtime
- An expression that is only valid within `constexpr` functions