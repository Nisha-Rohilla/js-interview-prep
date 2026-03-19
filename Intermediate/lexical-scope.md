Q) What is lexical scope?

Ans)
    Lexical scope means that a function can access variables from its outer scope based on where the function is defined in the code.
    In JavaScript, scope is determined at write time (lexically), not at runtime.

        💻 Code Example
                let outerVar = "I am outside";

                function outerFunction() {
                    let innerVar = "I am inside";

                    function innerFunction() {
                        console.log(outerVar); // accessible
                        console.log(innerVar); // accessible
                    }

                    innerFunction();
                }

                outerFunction();

        🔹 Another Example
                function parent() {
                    let name = "Nisha";

                    function child() {
                        console.log(name); // child can access parent's variable
                    }

                    child();
                }

                parent();

        🔍 Explanation

            Inner functions can access outer function variables
            Outer functions cannot access inner variables
            Scope is determined by where the function is written

        🎯 One-Line Interview Answer

            Lexical scope means a function can access variables from its outer scope based on where it is defined in the code.