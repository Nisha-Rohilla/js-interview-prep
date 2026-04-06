Q) What is the Temporal Dead Zone (TDZ)?

Ans)
    The Temporal Dead Zone (TDZ) is the time between when a variable is declared and when it is initialized, during which the variable cannot be accessed.
    It applies to variables declared with let and const.

    💻 Code Examples
            🔹 TDZ Example
                    console.log(a); // ❌ ReferenceError

                    let a = 10;

                    👉 Even though a is hoisted, it is in TDZ until initialization.

            🔹 var vs TDZ
                    console.log(x); // undefined
                    var x = 5;

                    👉 var does NOT have TDZ.

            🔹 Proper Usage
                    let b = 20;
                    console.log(b); // 20

            🔍 Explanation

                    TDZ exists from start of scope → until variable initialization
                    Accessing variable in TDZ → ReferenceError
                    Only affects let and const, not var

        🎯 One-Line Interview Answer

                Temporal Dead Zone is the period where a let or const variable is declared but cannot be accessed before initialization.

                TDZ prevents accessing variables before they are initialized, making code safer.