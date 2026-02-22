Q) What is the break statement and what is the continue statement?

Ans)
    The break statement is used to immediately stop the execution of a loop or a switch statement.
    Control moves to the next statement after the loop or switch.

        💻 Code Example
        for (let i = 1; i <= 5; i++) {
        if (i === 3) {
            break;
        }
        console.log(i);
        }
        // Output: 1 2


🔹 2️⃣ What is the continue statement?

            The continue statement skips the current iteration of a loop and moves to the next iteration.
            The loop does not stop completely.

                💻 Code Example
                for (let i = 1; i <= 5; i++) {
                if (i === 3) {
                    continue;
                }
                console.log(i);
                }
                // Output: 1 2 4 5


🔍 Explanation 

break → exits the loop entirely
continue → skips current iteration only
Used in for, while, and do-while loops
break is also used in switch statements

🎯 One-Line Interview Answers
// break
Break stops the loop immediately.

// continue
Continue skips the current iteration and continues with the next one.