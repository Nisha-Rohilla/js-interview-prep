Q) What is an object?

Ans)
    An object is a data structure used to store data in the form of key–value pairs.
    It is used to represent real-world entities and allows storing multiple related values in a single variable.

        💻 Code Examples
                🔹 Creating an Object
                        let user = {
                        name: "Nisha",
                        age: 22,
                        city: "Delhi"
                        };

                        console.log(user);

                🔹 Accessing Object Properties
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        console.log(user.name);      // dot notation
                        console.log(user["age"]);    // bracket notation

                🔹 Adding a New Property
                        let user = {
                        name: "Nisha"
                        };

                        user.age = 22;

                        console.log(user);

    🔍 Explanation 

            Objects store data as key–value pairs
            Keys are called properties
            Values can be strings, numbers, arrays, or functions
            Access using dot notation or bracket notation

    🎯 One-Line Interview Answer

             An object is a data structure that stores data as key–value pairs in JavaScript.