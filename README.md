# 1. Basic Types & Functions
### Exercise: Create a function that takes in a person’s `name` (string), `age` (number), and `isEmployed` (boolean) and returns a descriptive string. Define types for each parameter and for the return value.
### Goal: Practice defining parameter and return types for functions.


# 2. Interfaces & Objects
### Exercise: Define an interface `Car` with properties for `make`, `model`, `year`, and an optional `color`. Create an object using this interface and write a function that takes a `Car` object and returns a string description of the car.
### Goal: Practice using interfaces to define the structure of objects.

# 3. Enums
### Exercise: Create an enum Day for the days of the week, then write a function that takes in a Day and returns whether it's a weekend or a weekday.
### Goal: Understand how to use enums and how they can improve code readability and type safety.

# 4. Generics
### Exercise: Create a generic function `getArray` that takes an argument of any type and returns an array containing elements of that type. Then, use it to create arrays of different types.
### Goal: Understand the basics of generics and how to make functions flexible with different types.

# 5. Union Types & Type Guards
### Exercise: Write a function `formatInput` that takes either a`string` or a `number` as input and returns a formatted `string`. If the input is a string, it should return the uppercase version; if it’s a number, return the number as a string with two decimal places.
### Goal: Practice using union types and implementing type guards.

# 6. Classes and Inheritance
### Exercise: Create a `Person` class with properties `name` and `age` (both `private`), and a method `describe` that returns a string description of the person. Then, create a subclass `Employee` that extends `Person` and adds an `employeeId` property (`private`) and overrides the `describe` method to include the employee ID in the description.
### Goal: Learn how to create classes, define constructors, use inheritance, and override methods.

# 7. Type Aliases and Intersection Types
### Exercise: Define a type alias `Address` with properties for `street`, `city`, and `zipcode`. Create another type alias `ContactInfo` with properties `email` and `phone`. Define an intersection type `User` that combines `Address` and `ContactInfo` properties, then create an object of type `User`.
### Goal: Understand type aliases and how to use intersection types to combine types.

# 8. Async/Await and Promises
### Exercise: Create an async function `fetchData` that simulates fetching data from an API. Use `Promise` and `setTimeout` to return a value after a delay. Then use `async/await` to handle the result.
### Goal: Practice working with promises and async/await syntax in TypeScript.

# 9. Utility Types (e.g., Partial, Readonly)
### Exercise: Create an interface Task with properties `id`, `title`, and `completed`. Use TypeScript’s `Partial` utility type to create a type for updating tasks, where all fields are optional. Then, use `Readonly` to create a type where all properties of `Task` are immutable.
### Goal: Understand how to use utility types to manipulate object properties.

# 10. Type Assertions
### Exercise: Create a function `getValue` that takes an argument of type `unknown` and returns it as a string. Use type assertions to treat the value as a string within the function.
### Goal: Learn how to use type assertions to handle values of unknown or any type.
