Q) What is a default parameter and what is a return statement?

Ans)
    A default parameter allows a function parameter to have a default value if no argument is passed.
    It helps avoid undefined values.

        💻 Code Example
            function greet(name = "Guest") {
            console.log("Hello " + name);
            }

            greet();        // Hello Guest
            greet("Nisha"); // Hello Nisha

        🔹 2️⃣ What is a return statement?

                The return statement sends a value back from a function and stops its execution.
                After return, no code in the function is executed.

                    💻 Code Example
                            function add(a, b) {
                            return a + b;
                            console.log("This will not run");
                            }

                            console.log(add(4, 6)); // 10

        🔍 Explanation

            Default parameters prevent missing argument issues
            return gives output from a function
            Function execution stops after return

            🎯 One-Line Interview Answers
                    // Default parameter
                    A default parameter provides a fallback value to a function parameter.

                    // Return statement
                    The return statement sends a value back and stops function execution.