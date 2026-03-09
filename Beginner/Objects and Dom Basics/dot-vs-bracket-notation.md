Q) What is the difference between dot notation and bracket notation?

Ans)
    Dot notation and bracket notation are both used to access object properties in JavaScript.
    Dot notation uses a fixed property name, while bracket notation allows dynamic property access using strings or variables.

        💻 Code Examples
                🔹 Dot Notation
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        console.log(user.name); // Nisha

                🔹 Bracket Notation
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        console.log(user["name"]); // Nisha

                🔹 Dynamic Property Access
                        let user = {
                        name: "Nisha",
                        age: 22
                        };

                        let key = "name";

                        console.log(user[key]); // Nisha

        🔍 Key Differences
                // dot → fixed property name
                // bracket → dynamic property name

            Feature	                Dot Notation	                Bracket Notation
            Syntax	                object.property	                object["property"]
            Property name	        Fixed	                        Can be dynamic
            Variables allowed	    ❌ No	                       ✅ Yes
            Use case	            Simple access	                Dynamic keys

            🎯 One-Line Interview Answer

                Dot notation is used for fixed property names, while bracket notation allows dynamic property access using strings or variables.