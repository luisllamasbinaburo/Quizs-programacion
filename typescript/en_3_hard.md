How do you declare a type that combines two types in TypeScript, ensuring that properties from both types are present?
- type Combined = Type1 & Type2
- type Combined = Type1 | Type2
- type Combined = Type1 + Type2

What does the `ReturnType<T>` type do in TypeScript?
- Obtains the return type of a function type `T`
- Obtains the type of the first parameter of a function type `T`
- Obtains the type of the second parameter of a function type `T`

How do you define a conditional type in TypeScript?
- type Result = Condition extends TrueType ? TypeA : TypeB
- type Result = Condition ? TypeA : TypeB
- type Result = Condition ? TypeA & TypeB : TypeC

What is a mapped type in TypeScript?
- A type that is constructed from another type by applying a transformation to each property
- A type that combines multiple types into one
- A type that is defined as a set of optional properties

How do you define a type that accepts a variable number of parameters of different types in TypeScript?
- (...args: [Type1, Type2, ...]) => Type
- (args: [Type1, Type2, ...]) => Type
- (...args: Type[]) => Type

What is the `keyof` type in TypeScript?
- An operator that obtains a set of keys from a type
- A type that combines all possible keys in TypeScript
- A type used to define optional keys in an object

How do you define a type that is the intersection of an optional property and a mandatory property?
- type Combined = { prop1?: Type1 } & { prop2: Type2 }
- type Combined = { prop1: Type1 } | { prop2: Type2 }
- type Combined = { prop1?: Type1, prop2?: Type2 }

What does `Exclude<T, U>` mean in TypeScript?
- A type that excludes from `T` the types that are in `U`
- A type that includes all types in `T` that are in `U`
- A type that combines `T` and `U` into a new type

How do you define a type that can be a promise of a specific type in TypeScript?
- Promise<Type>
- Future<Type>
- Async<Type>

What does the `Partial<T>` utility do in TypeScript?
- Converts all properties of `T` to optional
- Converts all properties of `T` to required
- Converts some properties of `T` to optional

How do you declare a type that represents an object where all properties are functions in TypeScript?
- type Functions = { [key: string]: () => Type }
- type Functions = { [key: string]: Function }
- type Functions = { [key: string]: Type }

What is a "union" type in TypeScript and how is it used?
- A type that allows a value to be one of several possible types
- A type that allows combined values of multiple types
- A type that restricts a value to one of several predefined types

How do you define a type that is a function returning another function in TypeScript?
- type FunctionReturningFunction = (param: Type) => () => Type
- type FunctionReturningFunction = (param: Type) => Type
- type FunctionReturningFunction = () => (param: Type) => Type

What is an "inferred" type in TypeScript and how is it used?
- A type that is automatically determined from the compiler's type inference
- A type that is explicitly defined in the code
- A type used only for anonymous functions

How do you define a type that is an object with properties of generic types in TypeScript?
- type GenericObject<T> = { [key: string]: T }
- type GenericObject<T> = { key: T }
- type GenericObject<T> = { key: T[] }

What does `Readonly<T>` mean in TypeScript?
- A type that makes all properties of `T` read-only
- A type that makes all properties of `T` optional
- A type that removes all properties of `T`

How do you define a type that is a function that accepts and returns a function in TypeScript?
- type Func = (fn: (arg: Type) => Type) => (arg: Type) => Type
- type Func = (fn: Type) => (arg: Type) => Type
- type Func = (fn: (arg: Type) => Type) => Type

What does the `ThisType<T>` type do in TypeScript?
- Defines the type of `this` in the context of an object
- Defines the return type of a function
- Defines the type of function parameters

How do you declare a type that is a function accepting a variable number of optional parameters in TypeScript?
- (...args?: Type[]) => Type
- (args?: Type[]) => Type
- (...args: [Type?]) => Type

What does the `Awaited<T>` type do in TypeScript?
- Extracts the type of value that a promise `T` will resolve to
- Extracts the type of a function that returns a promise
- Extracts the type of a parameter of an asynchronous function

How do you define a type that is a subset of an object in TypeScript?
- type Subtype = Pick<Type, 'property'>
- type Subtype = Omit<Type, 'property'>
- type Subtype = Exclude<Type, 'property'>

What is a "conditional type" in TypeScript and how is it used?
- A type that selects between two types based on a condition
- A type that allows the combination of several types
- A type used to define optional values

How do you define a type that is a function that accepts an argument and returns a different type of function in TypeScript?
- type Func = (param: Type) => (arg: OtherType) => ReturnType
- type Func = (param: Type) => ReturnType
- type Func = (param: Type) => (arg: Type) => OtherType

What does `Extract<T, U>` mean in TypeScript?
- A type that extracts from `T` the types that are in `U`
- A type that excludes from `T` the types that are in `U`
- A type that combines `T` and `U` into a new type

How do you declare a type that is an object with optional and default properties in TypeScript?
- type Obj = { prop?: Type } & { propDefault?: Type }
- type Obj = { prop?: Type, propDefault: Type }
- type Obj = { prop: Type? } & { propDefault: Type }

What is a "template literal" type in TypeScript?
- A type constructed from a string with interpolations
- A type that defines a fixed string
- A type that combines strings and numbers

How do you define a type representing a function that can accept different amounts of parameters with different types in TypeScript?
- type Func = (...args: [Type1, Type2, ...]) => Type
- type Func = (args: [Type1, Type2, ...]) => Type
- type Func = (args: Type[]) => Type

What does the `Constructable` type do in TypeScript?
- Represents a type that can be instantiated using `new`
- Represents a type that can only be called as a function
- Represents a type that can be extended by classes