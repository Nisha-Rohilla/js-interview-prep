Q) What is if-else and what is an else-if ladder?

Ans)
    if-else is a conditional statement used to execute one block of code when a condition is true and another block when the condition is false.

        💻 Code Example
            let age = 16;

            if (age >= 18) {
            console.log("Adult");
            } else {
            console.log("Minor");
            }

🔹 2️⃣ What is an else-if ladder?
            An else-if ladder is used to check multiple conditions sequentially.
            The first condition that evaluates to true gets executed, and the rest are skipped.

        💻 Code Example
            let marks = 82;

            if (marks >= 90) {
            console.log("Grade A");
            } else if (marks >= 75) {
            console.log("Grade B");
            } else if (marks >= 50) {
            console.log("Grade C");
            } else {
            console.log("Fail");
            }

🔍 Explanation 

if-else → two conditions (true / false)
else-if ladder → multiple conditions
Only one block executes in an else-if ladder

🎯 One-Line Interview Answers
// if-else
if-else executes different blocks based on a condition.

// else-if ladder
else-if ladder checks multiple conditions one by one.