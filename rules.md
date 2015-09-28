# No `undefined`
`undefined` is not a keyword or value. Variables **must** be initialized when defined (although can be initialized to `null`).

# No `new`
You cannot instantiate objects with `new`, you must use a factory function to create objects using the object literal syntax `{}`.

# No `prototype`
Although JacksonScript compiles to JavaScript, objects do not have prototypes, code reuse should be achieved through composition or mixin.

# Block scoped variables (let)
There is no `var` keyword in JacksonScript, there is only `let` and it's semantics are the same as in JavaScript.

# No function declarations, only function expressions
You can't declare a function in JacksonScript, only define them as part of an expressions and assign them to a variable.

# Ergo no variable or function hoisting
The use of `let` and inability to declare functions outside of expressions means that there is no hoisting in JacksonScript.
