Q) How do you access array elements and what is the array length property?

Ans)
    Array elements are accessed using their index number inside square brackets [].
    Array indexing starts from 0.

        💻 Code Example
                let fruits = ["apple", "banana", "mango"];

                console.log(fruits[0]); // apple
                console.log(fruits[1]); // banana
                console.log(fruits[2]); // mango

                🔹 Accessing Last Element
                        let numbers = [10, 20, 30, 40];

                        console.log(numbers[numbers.length - 1]); // 40

🔹 2️⃣ What is the array length property?
        The length property returns the total number of elements in an array.

        💻 Code Example
            let colors = ["red", "blue", "green"];

            console.log(colors.length); // 3

            🔹 Using length in a Loop
                    let items = ["pen", "book", "bag"];

                    for (let i = 0; i < items.length; i++) {
                    console.log(items[i]);
                    }

        🔍 Explanation 

                Array elements are accessed using index values
                Index starts from 0
                length gives the number of elements in the array
                Often used in loops to iterate arrays

        🎯 One-Line Interview Answers
                // Access array elements
                Array elements are accessed using their index inside square brackets.

                // Array length
                The length property returns the number of elements in an array.