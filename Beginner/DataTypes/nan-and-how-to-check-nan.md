Q) What is NaN and how do you check if a value is NaN?

Ans) 
    NaN stands for “Not a Number”.
    It represents a value that is supposed to be a number but is not a valid numeric value as a result of an invalid mathematical operation.

    💻 Code Examples
        let result = "abc" / 2;

        console.log(result);        // NaN
        console.log(typeof result); // "number"


    🔹 How do you check if a value is NaN?
            ✅ Method 1: Number.isNaN() (Recommended)
                console.log(Number.isNaN(NaN));      // true
                console.log(Number.isNaN("abc"));    // false
                console.log(Number.isNaN("abc" / 2));// true

            ⚠️ Method 2: isNaN() (Not recommended)
                console.log(isNaN("abc")); // true (because it coerces the value)



    NaN means an invalid numeric result
    typeof NaN returns "number" (interview trick)
    Number.isNaN() checks without type coercion
    isNaN() performs type coercion, so it can give confusing results