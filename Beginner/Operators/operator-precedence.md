Q) What is operator precedence?

Ans)
    Operator precedence determines the order in which operators are evaluated in an expression.
    Operators with higher precedence are evaluated before operators with lower precedence.
    Parentheses () can be used to change the default order.

        💻 Code Examples
            🔹 Example 1: Without Parentheses
                    let result = 10 + 5 * 2;
                    console.log(result); // 20


                    👉 * has higher precedence than +, so 5 * 2 is evaluated first.

            🔹 Example 2: With Parentheses
                    let result = (10 + 5) * 2;
                    console.log(result); // 30


                    👉 Parentheses change the order: addition happens first.

            🔹 Example 3: Comparison vs Logical Operators
                    let x = 5;

                    console.log(x > 3 && x < 10); // true


                    👉 Comparison operators (>, <) run before logical AND (&&).

        🔍 Explanation 

        () → highest precedence

        * and / → higher than + and -

        Comparison operators → evaluated before logical operators

        Use parentheses to avoid confusion and bugs