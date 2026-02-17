Q) 

Ans) 
    Template literals are a modern way to create strings in JavaScript using backticks (``).
    They allow string interpolation, multi-line strings, and embedded expressions, making code more readable.

        💻 Code Examples
                🔹 String Interpolation
                        let name = "Nisha";
                        let age = 22;

                        let message = `My name is ${name} and I am ${age} years old.`;
                        console.log(message);
                🔹 Multi-line Strings
                        let text = `This is line one
                        This is line two
                        This is line three`;

                        console.log(text);
                🔹 Expression Inside Template Literal
                        let a = 10;
                        let b = 5;

                        console.log(`Sum is ${a + b}`);

    Template literals use backticks (`)
    ${} is used to insert variables or expressions
    No need for string concatenation using +
    Improves readability and cleaner code