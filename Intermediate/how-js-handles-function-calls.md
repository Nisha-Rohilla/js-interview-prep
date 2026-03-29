Q) How does JavaScript handle function calls internally?

Ans)
    JavaScript handles function calls using the call stack.
    Each time a function is called, a new execution context is created and pushed onto the call stack.
    After execution, it is removed (popped) from the stack.

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

        🔹 Internal Working (Step-by-Step)
                // Step 1: Global Execution Context is created

                // Step 2: first() is called → pushed to call stack

                // Step 3: second() is called → pushed

                // Step 4: third() is called → pushed

                // Step 5: third() executes → removed (pop)

                // Step 6: second() executes → removed

                // Step 7: first() executes → removed

            🔍 Explanation 
                    Every function call creates a new execution context
                    Contexts are stored in the call stack
                    Stack follows LIFO (Last In First Out)
                    After execution, function is removed from stack

        🎯 One-Line Interview Answer

            JavaScript handles function calls using the call stack, where each function creates an execution context that is pushed and popped during execution.
            Each function call creates a new execution context and is managed by the call stack.