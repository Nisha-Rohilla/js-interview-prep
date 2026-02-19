Q) What is the ternary operator?

Ans)
    The ternary operator is a shorthand way of writing an if...else statement in a single line.
    It evaluates a condition and returns one value if the condition is true and another value if it is false.

            💻 Syntax
                        condition ? valueIfTrue : valueIfFalse;

            💻 Example
                    let age = 20;

                    let result = age >= 18 ? "Adult" : "Minor";
                    console.log(result);

            🔹 Ternary vs if-else
                    let isLoggedIn = true;

                    // if-else
                    if (isLoggedIn) {
                    console.log("Welcome");
                    } else {
                    console.log("Please login");
                    }

                    // ternary
                    console.log(isLoggedIn ? "Welcome" : "Please login");

            🔍 Explanation

            ? checks the condition

            : separates true and false values

            Makes code shorter and cleaner
