How do you define an `indexer` in a class in C#?
- public T this[int index] { get; set; }
- public T Get(int index) { }
- public void Set(int index, T value) { }

What is the difference between `Task.Run` and `Task.Factory.StartNew` in C#?
- `Task.Run` is a simplified way to start a task on the thread pool, while `Task.Factory.StartNew` provides more configuration options
- `Task.Run` provides more configuration options than `Task.Factory.StartNew`
- `Task.Run` and `Task.Factory.StartNew` are equivalent in all circumstances

What is the `Repository` design pattern and how is it applied in C#?
- A pattern that abstracts data access logic into an interface to simplify data management
- A pattern that directly implements data access logic in entity classes
- A pattern that uses SQL methods directly in entity classes

How is the `Mediator` design pattern implemented in C#?
- Using a `Mediator` class that coordinates communication between objects without them referring to each other directly
- Using an interface to define direct communication between objects
- Using a service that makes direct calls to the involved objects

What is a `lambda expression` in C# and how is it used?
- A concise way to define anonymous functions that can be passed as arguments to other methods
- A function declared with a specific name for use throughout the application
- A method defined within a class to perform a specific operation

How is the `readonly` modifier used in a class in C#?
- It is used to declare fields that can only be assigned in the constructor or at the variable declaration
- It is used to define methods that cannot be overridden in derived classes
- It is used to declare properties that can only be read

What is a `dynamic` type and how does it affect performance in C#?
- `dynamic` allows type resolution at runtime, which can negatively impact performance due to the lack of compile-time checking
- `dynamic` allows types to be checked at compile time to improve performance
- `dynamic` optimizes performance by performing all checks at compile time

How is an atomic operation implemented in C#?
- Using the `Interlocked` class to perform operations atomically and avoid concurrency issues
- Using `lock` blocks to synchronize access to shared resources
- Using the `volatile` keyword to indicate a field may be changed at any time

What is a `dynamic proxy` in C# and when is it used?
- A proxy generated dynamically at runtime to intercept and modify method calls
- A type of proxy defined statically for communication between components
- A proxy used only for network communication

How is `memory management` handled in C#?
- Through the `garbage collector`, which automatically frees unused memory
- By manually managing memory through pointers
- Using special directives for memory allocation and release

How is the `Chain of Responsibility` design pattern used in C#?
- By defining a chain of handlers that process a request and pass it along the chain until a handler processes it
- By defining a single handler that processes all requests directly
- Using a static class to handle all requests

What is a `volatile` field and when is it used in C#?
- A field marked as `volatile` ensures that reads and writes are always visible to all threads
- A `volatile` field is used to improve the performance of thread operations
- A `volatile` field is used to define global constants

How is a `custom attribute` defined in C# and how is it applied?
- Defined as a class that inherits from `System.Attribute` and applied using brackets in the code
- Defined as a method that must be explicitly invoked
- Defined as an interface that must be implemented in classes

What is a `ValueTuple` and how does it differ from a `Tuple` in C#?
- `ValueTuple` is a value type that allows more efficient deconstruction and is not immutable, while `Tuple` is an immutable reference type
- `ValueTuple` is a reference type that allows immutability, while `Tuple` is a value type
- There are no significant differences between `ValueTuple` and `Tuple`

How is the `lock` keyword used for synchronization in C#?
- To ensure that only one thread can execute a block of code at a time, avoiding concurrency issues
- To allow multiple threads to access a block of code simultaneously
- To define a region of code that will execute in the order of thread arrival

What is a `memory leak` and how is it avoided in C#?
- A `memory leak` occurs when memory is reserved but not freed, and it can be avoided using the `garbage collector` and managing resources properly
- A `memory leak` occurs when memory is freed prematurely, and it can be avoided using the `static` keyword
- A `memory leak` occurs when `finalize` is used incorrectly

How is the `ConcurrentDictionary` class used in C#?
- To handle a dictionary that supports concurrent access without explicit locking
- To implement a dictionary that does not support concurrent access
- To store data sequentially in a dictionary

What is `composition` versus `inheritance` in C#?
- Composition involves building classes from other classes by including instances, while inheritance involves deriving classes from other classes
- Inheritance is used to include instances within a class, while composition is used to derive classes
- There is no difference between composition and inheritance in C#

How is `deserialization` performed in C#?
- By converting data in JSON, XML, or other formats into C# objects using methods like `JsonConvert.DeserializeObject`
- By transforming objects into text using `ToString()`
- By using the `convert` keyword to convert data

What is a `deadlock` and how is it avoided in C#?
- A `deadlock` occurs when two or more threads wait indefinitely for resources that are locked by each other, and it is avoided by proper lock management and techniques like resource ordering
- A `deadlock` occurs when a thread runs indefinitely without freeing up, and it is avoided by resource release
- A `deadlock` occurs when a thread blocks without reason and is avoided with the `unlock` keyword

How is `dependency injection` implemented in C# using `Microsoft.Extensions.DependencyInjection`?
- By registering services in the service container and resolving dependencies through the container
- By using the singleton pattern directly for all dependencies
- By manually implementing dependency injection in each class

What is a `future` in C# and how does it differ from a `Task`?
- A `future` is an object representing the result of an operation that may not be complete yet, while a `Task` is a representation of an asynchronous operation in C#
- A `future` and `Task` are synonymous concepts in C#
- A `future` is an operation running on the main thread, while a `Task` runs on a separate thread

What is a `Proxy` and how is it used in C#?
- A design pattern that provides a substitute or representative for another object to control access to it
- A class that stores cached data to improve performance
- A type of collection used to handle complex objects

How is object serialization implemented in C#?
- Using serialization attributes and methods like `BinaryFormatter.Serialize` or `JsonConvert.SerializeObject` to convert an object into a storage format
- Storing an object directly in a file using `File.WriteAllBytes`
- Using the `ToString()` method to convert an object to text

How is the `Observer` design pattern used in C#?
- By defining a one-to-many relationship between objects so that when one changes state, all dependents are notified and updated automatically
- By defining a single object that observes all changes in other objects
- By using an object that performs all state updates directly