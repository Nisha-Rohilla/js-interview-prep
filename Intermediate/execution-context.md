Q) What is execution context?

Ans)
    Execution context is the environment in which JavaScript code is executed.
    It contains information about variables, functions, and the scope chain during code execution.

    💻 Code Example
            let a = 10;

            function greet() {
                let b = 20;
                console.log(a + b);
            }

            greet();

    🔍 Explanation (Code-based)
                When the code runs, JavaScript creates an execution context
                There are mainly two types:
                    // 1. Global Execution Context (GEC)
                    // 2. Function Execution Context (FEC)

                        🔹 Global Execution Context
                                let x = 5;

                                console.log(x);

                                👉 Created when the program starts

                        🔹 Function Execution Context
                                function test() {
                                let y = 10;
                                console.log(y);
                                }

                                test();

                                👉 Created each time a function is called

    🔹 Execution Context Phases
            // 1. Creation Phase → variables & functions are set up (hoisting)
            // 2. Execution Phase → code runs line by line

            🎯 One-Line Interview Answer

                Execution context is the environment where JavaScript code runs and manages variables, functions, and scope.

                JavaScript runs code inside execution contexts like global and function contexts