Q) How do you convert a string to a number and a number to a string in JavaScript?

Ans)
    🔹 Converting a String to a Number
            A string can be converted into a number using built-in JavaScript methods like Number(), parseInt(), or parseFloat().

            💻 Code Examples
                let str = "123";

                console.log(Number(str));    // 123
                console.log(typeof Number(str)); // "number"
                let str2 = "123.45";

                console.log(parseInt(str2));   // 123
                console.log(parseFloat(str2)); // 123.45
                
    🔹 Converting a Number to a String
            A number can be converted into a string using String() or the .toString() method.

            💻 Code Examples
                let num = 100;

                console.log(String(num));      // "100"
                console.log(typeof String(num)); // "string"
                let num2 = 50;

                console.log(num2.toString());  // "50"
                console.log(typeof num2.toString()); // "string"



        Number() converts a string into a number
        parseInt() converts to an integer
        parseFloat() converts to a decimal number
        String() and .toString() convert numbers into strings

