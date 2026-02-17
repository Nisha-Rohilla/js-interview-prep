Q) What is the typeof operator and what does typeof null return?

Ans) 
    The typeof operator in JavaScript is used to determine the data type of a variable or value.
    It returns a string that indicates the type of the operand.
    When we use typeof null, it returns "object", which is a well-known bug in JavaScript.


    💻 Code Example
        // typeof operator examples
        console.log(typeof 10);           // "number"
        console.log(typeof "Hello");      // "string"
        console.log(typeof true);         // "boolean"
        console.log(typeof undefined);    // "undefined"
        console.log(typeof null);         // "object"

    🔍 Explanation (Based on Code)
         let value = null;
         console.log(value);        // null
         console.log(typeof value); // "object"

    typeof is used to check the data type of a value
    typeof null returns "object" due to a historical bug in JavaScript
    This behavior is kept for backward compatibility