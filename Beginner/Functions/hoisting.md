Q) What is hoisting?

Ans)
    Hoisting is JavaScript’s behavior of moving variable and function declarations to the top of their scope before code execution.
    Only declarations are hoisted, not initializations.

        💻 Code Examples
            🔹 Variable Hoisting with var
                    console.log(a); // undefined
                    var a = 10;

                    👉 Declaration is hoisted, value assignment is not.

            🔹 let and const (Temporal Dead Zone)
                    console.log(b); // ❌ ReferenceError
                    let b = 20;

                    👉 let and const are hoisted but not accessible before declaration.

            🔹 Function Declaration Hoisting
                    greet(); // works

                    function greet() {
                    console.log("Hello");
                    }

                    👉 Function declarations are fully hoisted.

            🔹 Function Expression (Not Hoisted)
                    sayHi(); // ❌ Error

                    const sayHi = function () {
                    console.log("Hi");
                    };

    🔍 Explanation (Code-based)

            var → hoisted and initialized as undefined
            let / const → hoisted but in Temporal Dead Zone
            Function declarations → fully hoisted
            Function expressions → not hoisted

    🎯 One-Line Interview Answer

            Hoisting is JavaScript’s behavior where declarations are moved to the top of their scope before execution.
            Hoisting applies to declarations, not initializations.