Q) What is recursion?

Ans)
    Recursion is a programming technique where a function calls itself until a base condition is met.
    It is commonly used to solve problems that can be broken down into smaller subproblems.

        💻 Code Example
                🔹 Basic Recursion (Factorial)
                        function factorial(n) {
                        if (n === 0) {
                            return 1; // base case
                        }
                        return n * factorial(n - 1); // recursive call
                        }

                        console.log(factorial(5)); // 120

                🔹 Another Example (Countdown)
                        function countdown(num) {
                        if (num === 0) {
                            console.log("Done");
                            return;
                        }
                        console.log(num);
                        countdown(num - 1);
                        }

                        countdown(3);

        🔍 Explanation 

                A recursive function must have a base case
                Base case stops the recursion
                Without a base case → infinite recursion → stack overflow
                Each recursive call gets added to the call stack

        🎯 One-Line Interview Answer

                Recursion is a technique where a function calls itself until a base condition stops it.
                Recursion must have a base condition to avoid infinite calls.