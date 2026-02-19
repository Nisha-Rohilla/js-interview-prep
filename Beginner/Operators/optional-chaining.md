Q) What is optional chaining (?.)?

Ans) 
    Optional chaining (?.) is a JavaScript operator that allows safe access to nested object properties or methods without causing an error.
    If the value before ?. is null or undefined, the expression returns undefined instead of throwing an error.

        💻 Code Examples
                🔹 Without Optional Chaining (Error)
                        let user = {};

                        console.log(user.profile.name); // ❌ TypeError

                🔹 With Optional Chaining
                        let user = {};

                        console.log(user.profile?.name); // undefined (no error)

                🔹 Optional Chaining with Methods
                        let user = {
                        greet() {
                            return "Hello";
                        }
                        };

                        console.log(user.greet?.()); // "Hello"

                🔹 Optional Chaining with Arrays
                        let users = [];

                        console.log(users[0]?.name); // undefined

        ?. prevents runtime errors
        Works with objects, arrays, and functions
        Returns undefined if the chain breaks
        Very useful in API responses and React apps