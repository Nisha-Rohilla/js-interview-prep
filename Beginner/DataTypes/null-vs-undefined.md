Q) What is the difference between null and undefined?


Ans) 
    ✅ Difference between null and undefined in JavaScript
            Feature	        null	                        undefined
            Meaning	        Intentional absence of value	Value not assigned
            Assigned by	    Developer	                    JavaScript
            Type	        object (this is a JS bug)	    undefined
            Default value	❌ No	                        ✅ Yes
            Use case	    Explicitly clear a value	    Variable declared but not initialized


        🔹 Examples
                undefined
                let x;
                console.log(x); // undefined

                null
                let y = null;
                console.log(y); // null

        📌 Important Interview Points

        undefined means value not assigned yet
        null means value intentionally set to empty

        typeof null returns "object" (common interview trick)

        undefined means a variable has been declared but not assigned a value, while null is an intentional empty value assigned by the developer.