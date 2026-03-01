Q) What is a callback function?

Ans)
    A callback function is a function that is passed as an argument to another function and is executed later.
    It is commonly used for asynchronous operations and event handling in JavaScript.

        💻 Code Examples
                🔹 Basic Callback Example
                        function greet(name, callback) {
                        console.log("Hello " + name);
                        callback();
                        }

                        function sayBye() {
                        console.log("Goodbye");
                        }

                        greet("Nisha", sayBye);

                🔹 Callback with Array Method
                        let numbers = [1, 2, 3];

                        numbers.forEach(function (num) {
                        console.log(num);
                        });

                🔹 Asynchronous Callback Example
                        setTimeout(function () {
                        console.log("This runs after 2 seconds");
                        }, 2000);

    🔍 Explanation

            Callback function is passed, not called immediately
            It executes after a task is completed
            Used in async operations, events, and array methods

    🎯 One-Line Interview Answer

    A callback function is a function passed as an argument to another function and executed later.
    Callbacks help handle asynchronous behavior in JavaScript.