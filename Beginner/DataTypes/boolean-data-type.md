Q) What is the Boolean data type in JavaScript?

Ans)
    The Boolean data type represents one of two values: true or false.
I   t is commonly used in conditional statements, comparisons, and logical operations to control program flow.

            💻 Code Examples
                🔹 Basic Boolean Values
                        let isLoggedIn = true;
                        let hasPermission = false;

                        console.log(isLoggedIn);      // true
                        console.log(hasPermission);  // false
                🔹 Boolean from Comparison
                        let a = 10;
                        let b = 5;

                        console.log(a > b);  // true
                        console.log(a < b);  // false
                🔹 Boolean in Conditions
                        let isStudent = true;

                        if (isStudent) {
                        console.log("Access granted");
                        }
                🔹 Boolean Conversion
                        console.log(Boolean(1));      // true
                        console.log(Boolean(0));      // false
                        console.log(Boolean(""));     // false
                        console.log(Boolean("JS"));   // true
          

        Boolean has only two values: true and false
        Comparisons (>, <, ==, ===) return Boolean values
        Boolean() converts values to true or false
        Used heavily in if-else, loops, and logical checks