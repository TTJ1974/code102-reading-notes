# Problem Domain, Ojects, and the Dom

Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one, that has a very similar pattern repeated on it and is double-sided?

The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

Programming is easy if you can understand the problem domain.

Courtesy of <https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming>

## values

JavaScript currently supports eight data types. All of these data types (Booleans, Null, Undefined, Number, BigInt, String, Symbol) are primitive values except for object references.
Many common data types such as arrays, functions, and dates are object references under the hood.
Primitive values can be stored in variables directly. Objects, on the other hand, are stored as references. A variable that has been assigned an object does not store that object directly, it stores the memory address of the location that the object exists at.
Primitive values are immutable — they cannot be changed after being created. Object references, however, are mutable and can be changed.
Since objects are stored as references, special care must be taken when duplicating objects and when performing equality checks on objects.
Understanding how these operations work can be confusing for newcomers to JavaScript, but they make sense once you understand how the language’s type system works.
Developing a strong grasp of primitive values, object references, and mutability is a critical step in progressing past the beginner stages of JavaScript programming.
This knowledge will help you identify bugs, understand key differences in programming paradigms, and help you understand your code at a deeper level.

courtesy of <https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b>
