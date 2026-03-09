Q) How do you create an object?

Ans)
    Objects in JavaScript can be created in multiple ways, such as using object literals, the new Object() constructor, or a constructor function.

        💻 Code Examples
                🔹 1️⃣ Using Object Literal (Most Common)
                        let user = {
                        name: "Nisha",
                        age: 22,
                        city: "Delhi"
                        };

                        console.log(user);

                🔹 2️⃣ Using new Object() Constructor
                        let user = new Object();

                        user.name = "Nisha";
                        user.age = 22;

                        console.log(user);

                🔹 3️⃣ Using Constructor Function
                        function Person(name, age) {
                        this.name = name;
                        this.age = age;
                        }

                        let user1 = new Person("Nisha", 22);

                        console.log(user1);

        🔍 Explanation 

                Object literal {} is the most common method
                new Object() creates an empty object
                Constructor functions help create multiple similar objects

        🎯 One-Line Interview Answer

                Objects can be created using object literals, the new Object() constructor, or constructor functions in JavaScript.