Q) What is a for loop?

Ans)
    A for loop is used to execute a block of code repeatedly for a specific number of times.
    It is commonly used when the number of iterations is known in advance.

        💻 Syntax
        for (initialization; condition; increment/decrement) {
        // code to execute
        }

        💻 Code Examples
            🔹 Basic for Loop
                    for (let i = 1; i <= 5; i++) {
                    console.log(i);
                    }
                    // Output: 1 2 3 4 5
            🔹 Looping Through an Array
                    let colors = ["red", "blue", "green"];

                    for (let i = 0; i < colors.length; i++) {
                    console.log(colors[i]);
                    }
        🔍 Explanation

        Initialization → runs once at the start
        Condition → checked before each iteration
        Increment/Decrement → updates loop counter
        Loop stops when the condition becomes false

        🎯 One-Line Interview Answer

        A for loop repeatedly executes a block of code until a specified condition becomes false.