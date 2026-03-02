Q) Are functions hoisted?

Ans) 
    Yes, function declarations are hoisted in JavaScript, but function expressions and arrow functions are not hoisted.

        💻 Code Examples
            🔹 Function Declaration (Hoisted)
                    greet(); // works

                    function greet() {
                    console.log("Hello");
                    }

            🔹 Function Expression (Not Hoisted)
                    sayHi(); // ❌ Error

                    const sayHi = function () {
                    console.log("Hi");
                    };

            🔹 Arrow Function (Not Hoisted)
                    welcome(); // ❌ Error

                    const welcome = () => {
                    console.log("Welcome");
                    };

        🔍 Explanation 

                Function declarations are fully hoisted
                Function expressions are hoisted as variables but not initialized
                Arrow functions behave like function expressions

        🎯 One-Line Interview Answer

                Function declarations are hoisted, but function expressions and arrow functions are not hoisted.
                Only function declarations can be called before they are defined.