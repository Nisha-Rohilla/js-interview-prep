Q) What is the call stack?

Ans)
    The call stack is a data structure used by JavaScript to keep track of function execution.
    It follows the Last In, First Out (LIFO) principle, meaning the last function added is the first one to be executed and removed.

        💻 Code Example
                function first() {
                    console.log("First");
                    second();
                }

                function second() {
                    console.log("Second");
                    third();
                }

                function third() {
                    console.log("Third");
                }

                first();

            🔹 How Call Stack Works
            // Step-by-step:

            // first() is added to stack
            // second() is added
            // third() is added

            // third() executes → removed
            // second() executes → removed
            // first() executes → removed

        🔍 Explanation (Code-based)
                Functions are pushed into the call stack when called
                After execution, they are popped out
                Works in LIFO order
                Helps JavaScript manage execution flow

        🎯 One-Line Interview Answer

                The call stack is a LIFO data structure that manages function execution in JavaScript.
                JavaScript uses a single-threaded call stack to execute code.