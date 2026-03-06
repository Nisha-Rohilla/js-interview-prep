Q) What is shift() method and what is unshift() method?

Ans)
    The shift() method removes the first element from an array and returns that element.
    It also shifts all remaining elements to a lower index.

        💻 Code Example
                let fruits = ["apple", "banana", "mango"];

                let removed = fruits.shift();

                console.log(removed); // apple
                console.log(fruits);  // ["banana", "mango"]

    🔹 2️⃣ What is the unshift() method?

            The unshift() method adds one or more elements to the beginning of an array.
            It returns the new length of the array.

            💻 Code Example
                    let fruits = ["banana", "mango"];

                    fruits.unshift("apple");

                    console.log(fruits); 
                    // ["apple", "banana", "mango"]

    🔍 Explanation 

            shift() → removes the first element of an array
            unshift() → adds elements to the beginning of an array
            Both methods modify the original array

    🎯 One-Line Interview Answers
        // shift
            shift() removes the first element from an array.

        // unshift
            unshift() adds elements to the beginning of an array.