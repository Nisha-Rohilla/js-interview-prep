Q) What is for...in loop and what is for...of loop?

Ans)
    The for...in loop is used to iterate over the enumerable properties (keys) of an object.
    It can also be used with arrays, but it is mainly recommended for objects.

        💻 Code Example
        let user = {
        name: "Nisha",
        age: 22,
        city: "Delhi"
        };

        for (let key in user) {
        console.log(key, user[key]);
        }

🔹 2️⃣ What is a for...of loop?

        The for...of loop is used to iterate over iterable values such as arrays, strings, and maps.
        It gives direct access to the values instead of keys.

            💻 Code Example
            let colors = ["red", "blue", "green"];

            for (let color of colors) {
            console.log(color);
            }

🔍 Key Difference 
// for...in → keys
// for...of → values

Feature	            for...in	            for...of
Iterates over	    Object keys	            Values
Best used for	    Objects	                Arrays, strings
Output	            Index or key	        Actual value


🎯 One-Line Interview Answers
// for...in
for...in iterates over object keys.

// for...of
for...of iterates over iterable values.

🔥 Interview Tip

Use for...in for objects and for...of for arrays.