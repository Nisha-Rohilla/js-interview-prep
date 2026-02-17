Q) implicit-vs-explicit-type-conversion.md

Ans) 
    🔹 Implicit Type Conversion
            Implicit type conversion is automatic conversion done by JavaScript.

            💻 Code Examples
                    let a = "10" + 5;
                        console.log(a);        // "105"
                        console.log(typeof a); // "string"
                    let b = "10" - 5;
                        console.log(b);        // 5
                        console.log(typeof b); // "number"
                        console.log(true + 1);   // 2
                        console.log(false + 1);  // 1

    🔹 Explicit Type Conversion
            Explicit type conversion is done manually by the developer using built-in functions to convert one data type into another.

            💻 Code Examples
                let x = "10";

                console.log(Number(x));  // 10
                console.log(String(10)); // "10"
                console.log(Boolean(1)); // true

            🔍 Explanation (Code-based)

            Implicit conversion → JavaScript decides the conversion
            Explicit conversion → Developer controls the conversion
            Explicit conversion is safer and more predictable