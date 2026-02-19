Q) What is short-circuit evaluation?
Ans)    
    Short-circuit evaluation is a behavior in JavaScript where the second operand is not evaluated if the result can be determined from the first operand.
    It mainly occurs with logical operators && (AND) and || (OR).

        💻 Code Examples
            🔹 Logical AND (&&)
                    let isLoggedIn = false;

                    isLoggedIn && console.log("Welcome");


                    👉 console.log is not executed because the first condition is false.

            🔹 Logical OR (||)
                    let username = "";

                    let name = username || "Guest";
                    console.log(name); // "Guest"


                    👉 Since username is falsy, the second value is used.

            🔹 Function Call Example
                    function greet() {
                    console.log("Hello");
                    }

                    false && greet(); // greet() is not called
                    true || greet();  // greet() is not called

        🔍 Explanation 

        && stops when it finds the first falsy value

        || stops when it finds the first truthy value

        Improves performance by avoiding unnecessary evaluations