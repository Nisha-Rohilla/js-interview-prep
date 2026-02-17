Q) type-coercion-in-javascript.md

Ans)
    Type coercion is the automatic conversion of one data type into another by JavaScript during operations.
    It usually happens when we perform operations between different data types, like a string and a number.

    💻 Code Examples
            🔹 Example 1: String + Number
                    let result = "5" + 2;
                    console.log(result);        // "52"
                    console.log(typeof result); // "string"
                    [👉 Number 2 is converted into string "2".]

            🔹 Example 2: String - Number
                    let result = "5" - 2;
                    console.log(result);        // 3
                    console.log(typeof result); // "number"
                    [👉 String "5" is converted into number 5.]

            🔹 Example 3: Boolean Coercion
                    console.log(true + 1);   // 2
                    console.log(false + 1);  // 1
                    [👉 true → 1, false → 0]

            🔹 Example 4: Equality (==)
                    console.log(5 == "5");  // true
                    [👉 "5" is coerced into number 5.]

        🔍 Explanation (Based on Code)

                JavaScript automatically converts data types when required
                + prefers string concatenation
                Other operators (-, *, /) prefer numeric conversion
                == allows type coercion

