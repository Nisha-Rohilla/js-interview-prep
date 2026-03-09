Q) How do you access object properties?

Ans)
    Object properties can be accessed using dot notation (.) or bracket notation ([]).

        💻 Code Examples
                🔹 Accessing with Dot Notation
                        let user = {
                        name: "Nisha",
                        age: 22,
                        city: "Delhi"
                        };

                        console.log(user.name); // Nisha
                        console.log(user.age);  // 22

                🔹 Accessing with Bracket Notation
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        console.log(user["name"]); // Nisha
                        console.log(user["age"]);  // 22

                🔹 Dynamic Property Access
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        let key = "name";

                        console.log(user[key]); // Nisha

        🔍 Explanation (Code-based)

                Dot notation → simple and commonly used
                Bracket notation → useful when property name is dynamic or stored in a variable
                Both methods access object property values

        🎯 One-Line Interview Answer

                Object properties can be accessed using dot notation (object.property) or bracket notation (object["property"]).