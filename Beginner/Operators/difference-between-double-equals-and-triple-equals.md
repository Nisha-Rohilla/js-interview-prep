Q) What is the difference between == and ===?

Ans)
    == compares values with type coercion, while === compares both value and type without coercion.

            💻 Code Examples
                🔹 Using == (Loose Equality)
                        console.log(5 == "5");     // true
                        console.log(0 == false);  // true
                🔹 Using === (Strict Equality)
                        console.log(5 === "5");    // false
                        console.log(0 === false); // false


        == converts operands to the same type before comparison
        === does not perform type conversion
        === is safer and more predictable
             

        Always prefer === in real projects to avoid unexpected bugs.