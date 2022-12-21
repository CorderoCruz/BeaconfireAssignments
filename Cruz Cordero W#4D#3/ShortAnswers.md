## 1. Explain when you should and should not use TypeScript.

- You should use TypeScript when working on big projects that usually involve a group to avoid
  some bugs before production.
- TypeScript is not useful if you are a one man team because it increases development and
  might be on time crunch.

## 2. What is static type checking? How can developers benefit from it?

- Static type checking is when an error occurs because a vaalue being assigned to another
  datatype that are conflicting witht the same variable.

## 3. What is type inference?

- A Type inference is when TypeScript infers a variable by its initial value. For example, if
  we were to declare a variable as a 'let myVar = 4', TypeScript would infer that myVar is of
  type number.

## 4. How does the array type differ from tuples?

- An array type can have an array of dynamic length and a Tuple is a fixed sized length array

## 5. What are enums?

- Enums define an object with a group of constants. If no number is specified, then numbers,
  in ascending, 0 indexed, numbers are assigned to the constants

## 6. Explain the difference between type any and unknown.

- The any type is not specifying a specific datatype and the value will be ignored if the
  datatype is changed down the line, where as the unknown type, you don't specifically know
  the datatype just yet, but down the line the type must be checked before accesing it.

## 7. How do you type functions?

- "const arrowFn = (): /_returns number_/ : number => return 1" or if we were to not return
  anything, we could write the function like this,
  "const arrowFn = () : void = => "console.log('Hello, World!')"

## 8. What is the difference between union and intersection types?

- A union is 2+ types representing values that must be equal to at least one type, where as
  an intersection is also a 2+ types representing values but all memeber types must be matched.

## 9. What are type guards? What is narrowing?

- Type guards is a piece of code that involves conditional checking the value types before
  performing an operation on the variable.

## 10. What is type assertion?

- To let TypeScript Know that the variable is of another type.

## 11. Explain the difference type alias vs interface. When should you use each one?

- Type Alias is a type of for a complex type that can be reused where as an interface models an
  object type or a group of key value pairs. Type alias is useful for combining other type
  aliases and interfaces are used to annotate classes and objects.

## 12. What is type readonly?

- Type readonly prevents the variable from being reassigned to another value

## 13. Explain the difference between public, private, protected.

- The default status of a variable is public and it can be accessed from in or out the class and
  a private variable can only be accessed from inside the class and protected variables can only
  be accessed from inside the class or its subclasses.

## 14. What are generics?

- Generics are placeholder types that are changed later down the line when it is being used.
  Good for reusability and writing type safe code.
