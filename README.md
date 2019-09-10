# Today I Learned

## 05.09.19

An object literal is a comma-seperated list of name-value pairs wrapped in curly braces.

## 10.09.19

When using Object.assign without the first argument you can avoid mutating any variables.

Object.assign(objOne, objTwo); Will concatenate the values from objTwo into objOne.

If you do Object.assign({}, objOne, objTwo); instead then the function will only return a new object with objOne and objTwo concatenated.
