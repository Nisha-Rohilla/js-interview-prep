Q) What is push() method and what is pop() method?

Ans) 
    The push() method is used to add one or more elements to the end of an array.
    It also returns the new length of the array.

    💻 Code Example
            let fruits = ["apple", "banana"];

            fruits.push("mango");

            console.log(fruits); 
            // ["apple", "banana", "mango"]

    🔹 2️⃣ What is the pop() method?

            The pop() method removes the last element from an array and returns that element.

                💻 Code Example
                        let fruits = ["apple", "banana", "mango"];

                        let removed = fruits.pop();

                        console.log(removed); // mango
                        console.log(fruits);  // ["apple", "banana"]

            🔍 Explanation 

                    push() → adds element at the end of array
                    pop() → removes element from the end of array
                    Both methods modify the original array

            🎯 One-Line Interview Answers
                    // push
                        push() adds elements to the end of an array.

                    // pop
                        pop() removes the last element from an array.