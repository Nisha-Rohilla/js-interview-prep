Q) What is global scope?

Ans)
    Global scope refers to variables that are declared outside any function or block and can be accessed from anywhere in the program.

        💻 Code Examples
                🔹 Global Variable
                        let name = "Nisha"; // global scope

                        function greet() {
                        console.log(name); // accessible inside function
                        }

                        greet();
                        console.log(name); // accessible outside

                🔹 Global with var
                        var age = 22;

                        function showAge() {
                        console.log(age);
                        }

                        showAge()

        🔍 Explanation (Code-based)

                Variables declared outside functions are global
                Accessible from anywhere in the code
                Stored in the global execution context

        🎯 One-Line Interview Answer

                Global scope means variables declared outside any function can be accessed anywhere in the program.
                Avoid too many global variables to prevent conflicts.