Q) function-scope.md

Ans)
    Function scope means that variables declared inside a function are only accessible within that function and cannot be accessed outside.

        💻 Code Examples
                🔹 Function Scope with var
                        function test() {
                            var x = 10;
                            console.log(x); // 10
                        }

                        test();

                        console.log(x); // ❌ ReferenceError

                🔹 Function Scope with let and const
                        function greet() {
                            let name = "Nisha";
                            const age = 22;

                            console.log(name); // Nisha
                            console.log(age);  // 22
                        }

                        greet();

                        console.log(name); // ❌ Error
                        console.log(age);  // ❌ Error

        🔍 Explanation 
            Variables inside a function are local to that function
            Cannot be accessed from outside the function
            Applies to var, let, and const

        🎯 One-Line Interview Answer

            Function scope means variables declared inside a function are accessible only within that function.
            Function scope helps in data hiding and prevents variable conflicts.