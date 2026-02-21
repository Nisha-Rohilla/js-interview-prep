Q) What is a switch statement?

And)
    A switch statement is a conditional statement used to execute different blocks of code based on the value of an expression.
    It is an alternative to multiple if-else statements when comparing a single value.

    💻 Code Example
        🔹 Basic switch Statement
        let day = 3;

        switch (day) {
        case 1:
            console.log("Monday");
            break;
        case 2:
            console.log("Tuesday");
            break;
        case 3:
            console.log("Wednesday");
            break;
        default:
            console.log("Invalid day");
        }

    🔍 Explanation

    switch evaluates the expression once
    case checks for matching values
    break stops execution
    default runs if no case matches

    ⚠️ Important Interview Point (Fall-through)
    let num = 1;

    switch (num) {
    case 1:
        console.log("One");
    case 2:
        console.log("Two");
    }

    👉 Without break, both cases run (fall-through).

    🎯 One-Line Interview Answer

    A switch statement executes different code blocks based on matching cases of a value.