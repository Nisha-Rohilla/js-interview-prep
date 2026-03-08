Q) What is map() method and what is filter() method?

Ans)
    The map() method is used to create a new array by applying a function to each element of the original array.
    It does not modify the original array.

        💻 Code Example
                let numbers = [1, 2, 3, 4];

                let doubled = numbers.map(function (num) {
                return num * 2;
                });

                console.log(doubled); // [2, 4, 6, 8]

    🔹 2️⃣ What is the filter() method?
            The filter() method is used to create a new array containing elements that satisfy a specific condition.

                    💻 Code Example
                            let numbers = [1, 2, 3, 4, 5];

                            let evenNumbers = numbers.filter(function (num) {
                            return num % 2 === 0;
                            });

                            console.log(evenNumbers); // [2, 4]

    🔍 Key Difference (Code-based)
            // map() → transforms every element
            // filter() → selects elements based on condition
            
    Feature	                    map()	                        filter()
    Purpose	                    Transform elements	            Select elements
    Output size	                Same as original array	        May be smaller
    Condition required	        No	                            Yes

    🎯 One-Line Interview Answers
        // map
            map() creates a new array by transforming each element.

        // filter
            filter() creates a new array with elements that match a condition.