Q) What are truthy and falsy values in JavaScript?

Ans) 
    Truthy values are values that evaluate to true in a Boolean context, while falsy values evaluate to false.
    JavaScript automatically converts values to Boolean when used in conditions like if statements.

        💻 Code Examples
                🔹 Falsy Values (Total 6)
                        console.log(Boolean(false));     // false
                        console.log(Boolean(0));         // false
                        console.log(Boolean(-0));        // false
                        console.log(Boolean(""));        // false
                        console.log(Boolean(null));      // false
                        console.log(Boolean(undefined)); // false
                        console.log(Boolean(NaN));        // false

                        👉 Falsy values list (interview point):
                        false, 0, -0, "", null, undefined, NaN

                🔹 Truthy Values
                        console.log(Boolean(true));      // true
                        console.log(Boolean(1));         // true
                        console.log(Boolean("0"));       // true
                        console.log(Boolean("false"));   // true
                        console.log(Boolean([]));        // true
                         console.log(Boolean({}));        // true
                🔹 Truthy & Falsy in Conditions
                        let username = "";

                        if (username) {
                        console.log("User exists");
                        } else {
                        console.log("User not found"); // runs
                        }
        
        JavaScript converts values to Boolean automatically in conditions
        Falsy values behave like false
        All other values are truthy