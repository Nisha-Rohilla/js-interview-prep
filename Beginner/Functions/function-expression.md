Q) What is a function expression?

Ans)
    A function expression is a function that is assigned to a variable.
    Unlike function declarations, function expressions are not hoisted.

        💻 Code Example
                const add = function (a, b) {
                return a + b;
                };

                console.log(add(4, 6)); // 10

        🔍 Explanation

            Function is stored in a variable (add)
            Function expressions can be anonymous
            They are created at runtime
            Cannot be called before declaration

        ⚠️ Hoisting Difference (Important Interview Point)
        console.log(sum(2, 3)); // ❌ Error

        const sum = function (a, b) {
        return a + b;
        };
        
        🎯 One-Line Interview Answer

        A function expression is a function assigned to a variable and is not hoisted like a function declaration.