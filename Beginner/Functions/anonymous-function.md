Q) What is an anonymous function?

Ans)
    An anonymous function is a function that does not have a name.
    It is usually used as a function expression or passed as a callback.

    💻 Code Examples
        🔹 Anonymous Function as Function Expression
                const greet = function () {
                console.log("Hello");
                };

                greet();

        🔹 Anonymous Function as Callback
                setTimeout(function () {
                console.log("Executed after 1 second");
                }, 1000);

        🔹 Anonymous Function in Array Method
                let numbers = [1, 2, 3];

                numbers.map(function (num) {
                return num * 2;
                });

    🔍 Explanation (Code-based)

        Anonymous functions have no name
        Commonly used for one-time use
        Often passed as callbacks
        Improves code flexibility

    🎯 One-Line Interview Answer

            An anonymous function is a function without a name, commonly used as a callback or function expression.

