Q) What is the nullish coalescing operator (??)?

Ans)
    The nullish coalescing operator (??) returns the right-hand value only when the left-hand value is null or undefined.
    It is used to provide default values without treating 0, false, or empty strings as invalid.

        💻 Code Examples
            🔹 Basic Example
                    let username = null;

                    let name = username ?? "Guest";
                    console.log(name); // "Guest"

            🔹 Difference from Logical OR (||)
                    let score = 0;

                    console.log(score || 100); // 100 (wrong for default)
                    console.log(score ?? 100); // 0   (correct)

            🔹 With Undefined
                    let value;

                    console.log(value ?? "Default"); // "Default"

        ?? checks only for null and undefined

        || checks for all falsy values

        Prevents unintended defaulting