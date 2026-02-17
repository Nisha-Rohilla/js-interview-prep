Q) What are comparison operators in JavaScript?

Ans)
    Comparison operators are used to compare two values and return a Boolean result (true or false).
    They are commonly used in conditional statements and logical checks.

        💻 Code Examples
                🔹 List of Comparison Operators
                        let a = 10;
                        let b = 5;

                        console.log(a == b);   // false  (equal to)
                        console.log(a != b);   // true   (not equal to)
                        console.log(a === b);  // false  (strict equal)
                        console.log(a !== b);  // true   (strict not equal)
                        console.log(a > b);    // true   (Greater then)
                        console.log(a < b);    // false  (Less then)
                        console.log(a >= b);   // true   (greater then equal to)
                        console.log(a <= b);   // false   (Less then equal to)
                        
                🔹 Equality vs Strict Equality
                        console.log(5 == "5");   // true  (type coercion)
                        console.log(5 === "5");  // false (no type coercion)
        

        == compares values only (allows type coercion)
        === compares both value and type
        Comparison operators always return a Boolean
        === is recommended to avoid unexpected results