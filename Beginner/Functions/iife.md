Q) What is an IIFE?

Ans)
    An IIFE (Immediately Invoked Function Expression) is a function that runs immediately after it is defined.
    It is commonly used to create a private scope and avoid polluting the global namespace.

        💻 Code Examples
            🔹 Basic IIFE
                    (function () {
                    console.log("IIFE executed");
                    })();

            🔹 IIFE with Parameters
                    (function (name) {
                    console.log("Hello " + name);
                    })("Nisha");
                
            🔹 Arrow Function IIFE
                    (() => {
                    console.log("Arrow IIFE");
                    })();

        🔍 Explanation 

                Function is wrapped in parentheses
                Immediately executed using ()
                Creates a private scope
                Prevents global variable conflicts

        🎯 One-Line Interview Answer

        An IIFE is a function that executes immediately after being defined to create a private scope.

        IIFEs were commonly used before ES6 modules to avoid global scope pollution.