Q) What are non-primitive data types?

Ans) 
    Non-primitive data types are complex data types that can store multiple values and are stored by reference instead of by value.
    They are mutable, meaning their values can be changed after creation.


        🔹 Types of Non-Primitive Data Types
                1️⃣ Object
                    Used to store data in key–value pairs.

                    let person = {
                    name: "Nisha",
                    age: 22
                    };

                2️⃣ Array

                    Used to store multiple values in a single variable.

                    let colors = ["red", "blue", "green"];

                3️⃣ Function

                    A block of reusable code.

                    function greet() {
                    console.log("Hello");
                    }

                4️⃣ Date (Object type)
                    let today = new Date();

    📌 Key Characteristics

        Store multiple values
        Mutable in nature
        Stored by reference
        More complex than primitive data types

        🔄 Primitive vs Non-Primitive (Quick Difference)

        Primitive	                Non-Primitive
        Stores single value	        Stores multiple values
        Immutable	                Mutable
        Stored by value	            Stored by reference
        Example: number, string	    Example: object, array