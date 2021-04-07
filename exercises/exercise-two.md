### Object de-structuring Syntax:

    let {age, age} = {name: "Yoni", age: 33}
    console.log(name) // Yoni
    console.log(age) //  33

Explanation:  The curly braces `{ }` stand for the object that is being destructured `name, age` represent the variables to which you want to assign the values. More specifically, the right side of the statement is the JavaScript object that we want to deconstruct. The left side contains the pattern with the corresponding properties of the object. *Remember, the variables, (in this case `name, age`) correspond to the keys in the object, otherwise you will receive an undefined.*.

### Instructions:

1. Declare and assign an empty object using object notation.

2. Add two properties to the empty object.

3. Assign the newly created object to two variables. Be sure to wrap your newly created variables inside curly brackets.

4. Use console.log to print out the variables.
