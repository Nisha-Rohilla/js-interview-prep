Q) What is an arrow function?

Ans)
    An arrow function is a shorter syntax for writing functions in JavaScript using the => operator.
    It makes the code more concise and does not have its own this keyword.

        💻 Syntax
            (parameters) => {
            // function body
            }

        💻 Code Examples
            🔹 Basic Arrow Function
            const add = (a, b) => {
            return a + b;
            };

            console.log(add(3, 4)); // 7

            🔹 Shorter Syntax (Implicit Return)
            const multiply = (a, b) => a * b;

            console.log(multiply(2, 5)); // 10

            🔹 Single Parameter (Parentheses Optional)
            const square = x => x * x;

            console.log(square(4)); // 16

        🔍 Explanation

            Uses => instead of function keyword
            Cleaner and shorter syntax
            Implicit return possible for single expressions
            Does not have its own this (important for React)

        🎯 One-Line Interview Answer

        An arrow function is a concise way to write functions using the => syntax and it does not have its own this.