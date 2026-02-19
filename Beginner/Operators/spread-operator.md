Q) What is the spread operator?

Ans)
    The spread operator (...) is used to expand elements of an array, object, or iterable into individual values.
    It helps in copying, merging, and passing data in a clean and readable way.

        💻 Code Examples
                🔹 Spread with Arrays
                        let arr1 = [1, 2, 3];
                        let arr2 = [...arr1];

                        console.log(arr2); // [1, 2, 3]

                🔹 Merging Arrays
                        let a = [1, 2];
                        let b = [3, 4];

                        let merged = [...a, ...b];
                        console.log(merged); // [1, 2, 3, 4]

                🔹 Spread with Objects
                        let user = { name: "Nisha", age: 22 };

                        let updatedUser = { ...user, city: "Delhi" };
                        console.log(updatedUser);

                🔹 Spread in Function Calls
                        let numbers = [5, 10, 15];

                        console.log(Math.max(...numbers)); // 15

        🔍 Explanation 

        ... expands elements

        Creates shallow copies

        Prevents direct mutation of arrays/objects

        Commonly used in React and modern JavaScript