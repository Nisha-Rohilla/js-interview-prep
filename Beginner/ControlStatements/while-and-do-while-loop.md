Q) What is a while loop and what is a do-while loop?

Ans)
    A while loop executes a block of code as long as a specified condition is true.
    The condition is checked before each iteration.

        💻 Code Example
        let i = 1;

        while (i <= 5) {
        console.log(i);
        i++;
        }
        // Output: 1 2 3 4 5

    🔹 2️⃣ What is a do-while loop?

            A do-while loop executes a block of code at least once, even if the condition is false.
            The condition is checked after the loop body.

                    💻 Code Example
                    let j = 6;

                    do {
                    console.log(j);
                    j++;
                    } while (j <= 5);
                    // Output: 6

🔍 Key Difference 
// while → condition checked first
// do-while → condition checked after execution


Loop	            Condition Check	            Executes at least once
while	            Before loop	                ❌ No
do-while	        After loop	                ✅ Yes

🎯 One-Line Interview Answers
// while
A while loop runs as long as the condition is true.

// do-while
A do-while loop runs at least once before checking the condition.