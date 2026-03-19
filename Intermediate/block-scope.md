Q) What is block scope?

Ans)
    Block scope means that variables declared inside a block {} are only accessible within that block.
    In JavaScript, let and const are block-scoped, while var is not.

        💻 Code Examples
                🔹 Block Scope with let
                        if (true) {
                        let x = 10;
                        console.log(x); // 10
                        }

                        console.log(x); // ❌ ReferenceError

                🔹 Block Scope with const
                        {
                        const y = 20;
                        console.log(y); // 20
                        }

                        console.log(y); // ❌ ReferenceError

                🔹 var is NOT Block Scoped
                        if (true) {
                        var z = 30;
                        }

                        console.log(z); // 30 (accessible outside block)

        🔍 Explanation

                {} defines a block
                let and const → accessible only inside the block
                var → ignores block scope (function-scoped)

        🎯 One-Line Interview Answer

            Block scope means variables declared with let and const are only accessible within the block they are defined in.

            let and const are block-scoped, but var is not.