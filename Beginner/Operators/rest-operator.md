Q) What is the rest operator?

Ans)
    The rest operator (...) is used to collect multiple values into a single array or object.
    It is mainly used in function parameters and destructuring to handle an unknown number of arguments.

        💻 Code Examples
                🔹 Rest Operator in Function Parameters
                        function sum(...numbers) {
                        return numbers.reduce((total, num) => total + num, 0);
                        }

                        console.log(sum(1, 2, 3)); // 6
                        console.log(sum(5, 10));   // 15

                🔹 Rest Operator with Array Destructuring
                        let [first, ...restValues] = [10, 20, 30, 40];

                        console.log(first);      // 10
                        console.log(restValues); // [20, 30, 40]

                🔹 Rest Operator with Object Destructuring
                        let user = { name: "Nisha", age: 22, city: "Delhi" };

                        let { name, ...otherDetails } = user;

                        console.log(name);          // "Nisha"
                        console.log(otherDetails);  // { age: 22, city: "Delhi" }

        ... collects remaining values

        Used on the left-hand side of assignment

        Helps handle variable number of arguments

        Makes code clean and flexible