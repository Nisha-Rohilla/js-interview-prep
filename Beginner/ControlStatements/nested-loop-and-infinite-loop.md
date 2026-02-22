Q) What is a nested loop and what is an infinite loop?

Ans)
    A nested loop is a loop inside another loop.
    The inner loop runs completely for every iteration of the outer loop.

        💻 Code Example
        for (let i = 1; i <= 3; i++) {
        for (let j = 1; j <= 2; j++) {
            console.log("i:", i, "j:", j);
        }
        }

        👉 The inner loop runs fully each time the outer loop runs.

🔹 2️⃣ What is an Infinite Loop?

        An infinite loop is a loop that never stops because its condition always remains true.
        It can crash the program or browser if not handled properly.

            💻 Code Example (Do NOT Run in Real Projects)
            while (true) {
            console.log("This will run forever");
            }
            🔹 Accidental Infinite Loop Example
            let i = 1;

            while (i <= 5) {
            console.log(i);
            // i++ is missing → condition never becomes false
            }

🔍 Explanation 

    Nested loop → loop inside another loop
    Infinite loop → condition never becomes false
    Always ensure loop condition changes properly

🎯 One-Line Interview Answers
// Nested loop
A nested loop is a loop inside another loop.

// Infinite loop
An infinite loop is a loop that never ends because its condition always remains true.