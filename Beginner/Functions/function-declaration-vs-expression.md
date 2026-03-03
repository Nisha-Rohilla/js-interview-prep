Q) What is the difference between function declaration and function expression?

Ans)
    A function declaration defines a named function using the function keyword and is hoisted, while a function expression assigns a function to a variable and is not fully hoisted.

        💻 Code Examples
            🔹 Function Declaration (Hoisted)
                    greet(); // Works

                    function greet() {
                    console.log("Hello");
                    }

            🔹 Function Expression (Not Hoisted)
                    sayHi(); // ❌ Error

                    const sayHi = function () {
                    console.log("Hi");
                    };

        🔍 Key Differences (Code-based)
        // Function Declaration
        // - Uses function keyword
        // - Has a name
        // - Fully hoisted

        // Function Expression
        // - Assigned to a variable
        // - Can be anonymous
        // - Not fully hoisted


        Feature	            Function Declaration	            Function Expression
        Hoisting	        Fully hoisted	                    Not hoisted
        Syntax	            Uses function keyword	            Assigned to variable
        Name	            Must have a name	                Can be anonymous
        Usage	            Can call before definition	        Cannot call before definition


        🎯 One-Line Interview Answer

            Function declarations are hoisted and can be called before definition, while function expressions are not hoisted and cannot be called before they are defined.
            The main difference is hoisting behavior.