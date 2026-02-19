Q) What is the delete operator and what is the typeof operator used for?

Ans)
    The delete operator is used to remove a property from an object.
    It returns true if the property is successfully deleted.

        💻 Code Examples
                let user = {
                name: "Nisha",
                age: 22
                };

                delete user.age;

                console.log(user); 
                // { name: "Nisha" }

            🔹 Important Point (Interview Trick)
                    let arr = [1, 2, 3];
                    delete arr[1];

                    console.log(arr); 
                    // [1, empty, 3]

                    👉 delete removes the value but does not change array length.

        🔹 2️⃣ What is the typeof operator used for?

                The typeof operator is used to check the data type of a variable or value.
                It returns the type as a string.

                💻 Code Examples
                        console.log(typeof 10);        // "number"
                        console.log(typeof "Hello");   // "string"
                        console.log(typeof true);      // "boolean"
                        console.log(typeof undefined); // "undefined"
                        console.log(typeof null);      // "object" (JavaScript bug)


        delete → removes object properties

        typeof → checks data type

        typeof null returns "object" (common interview question)

                // delete
                The delete operator removes a property from an object.

                // typeof
                The typeof operator is used to check the data type of a value.


                Next question bhejo 💻🔥
                Main file name + interview-focused theory + code isi format me