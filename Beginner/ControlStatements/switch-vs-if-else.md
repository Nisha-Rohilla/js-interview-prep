Q) What is the difference between switch and if-else?

Ans)
    Both switch and if-else are used for decision making, but they are used in different situations.
    switch is best when comparing a single value with multiple fixed values, while if-else is better for complex conditions and ranges.

        💻 Code Examples
            🔹 if-else Example
                let marks = 82;

                if (marks >= 90) {
                console.log("Grade A");
                } else if (marks >= 75) {
                console.log("Grade B");
                } else {
                console.log("Grade C");
                }
            🔹 switch Example
                let grade = "B";

                switch (grade) {
                case "A":
                    console.log("Excellent");
                    break;
                case "B":
                    console.log("Very Good");
                    break;
                case "C":
                    console.log("Good");
                    break;
                default:
                    console.log("Invalid grade");
                }

        🔍 Key Differences
        // Conceptual differences (for interview)

        Feature	            if-else	                            switch
        Condition type	    Complex conditions, ranges	        Single value comparison
        Readability	        Better for logical expressions	    Cleaner for fixed values
        Data types	        Works with all comparisons	        Best with numbers/strings
        Flexibility	        More flexible	                    Less flexible


        🎯 One-Line Interview Answer
        if-else is used for complex and range-based conditions, while switch is used to compare a single value with multiple fixed cases.

        Use if-else for conditions like ranges, and switch for fixed values.