Q) What is the difference between let and var in terms of scope?

Ans)
    var is function-scoped, while let is block-scoped.
    This means var can be accessed outside a block {}, but let is limited to the block in which it is declared.

        💻 Code Examples
                🔹 var (Function Scope)
                    if (true) {
                    var x = 10;
                }

                console.log(x); // 10 (accessible outside block)

                🔹 let (Block Scope)
                    if (true) {
                    let y = 20;
                }

                console.log(y); // ❌ ReferenceError

                🔹 Inside Function
                function test() {
                    var a = 5;
                    let b = 10;

                    console.log(a); // 5
                    console.log(b); // 10
                }

                test();

                console.log(a); // ❌ Error
                console.log(b); // ❌ Error

            🔍 Explanation
                    var ignores block scope and is accessible outside {}
                    let is restricted to the block {}
                    Both are limited inside functions

            🎯 One-Line Interview Answer

                var is function-scoped, while let is block-scoped and cannot be accessed outside its block.

                let is preferred over var because it avoids scope-related bugs.