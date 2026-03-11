Q) What is JSON?

Ans)
    JSON (JavaScript Object Notation) is a lightweight data format used to store and exchange data between a server and a client (like a browser). It is easy for humans to read and write and easy for machines to parse and generate.

        Key Points
                JSON is text-based.
                It is derived from JavaScript object syntax.
                It is commonly used in APIs and web applications.
                Data in JSON is stored as key–value pairs.

        Example of JSON
            {
            "name": "Nisha",
            "age": 23,
            "course": "MCA",
            "skills": ["HTML", "CSS", "JavaScript", "React"]
            }

        Structure of JSON
                JSON supports mainly these data types:

                        Object – { } (key-value pairs)
                        Array – [ ] (list of values)
                        String – "text"
                        Number – 10, 20
                        Boolean – true / false
                        Null – null

        Why JSON is used

            To send data between frontend and backend
            Used in REST APIs
            Lightweight compared to XML
            Supported by most programming languages

        Example in JavaScript
            let user = {
            "name": "Nisha",
            "age": 23
            };

            console.log(user.name); // Nisha

        JSON Example
                {
                "name": "Nisha",
                "age": 22,
                "city": "Delhi"
                }

        👉 In JSON:

            Keys must be strings
            Strings must use double quotes

        💻 Converting Object to JSON
                let user = {
                name: "Nisha",
                age: 22
                };

                let jsonData = JSON.stringify(user);

                console.log(jsonData);

        💻 Converting JSON to Object
                let jsonString = '{"name":"Nisha","age":22}';

                let obj = JSON.parse(jsonString);

                console.log(obj.name); // Nisha

        🔍 Explanation 

                JSON.stringify() → converts object to JSON string
                JSON.parse() → converts JSON string to JavaScript object
                Commonly used in APIs and data exchange

                ✅ In simple words:
                    JSON is a format used to transfer data between systems, especially between frontend (React/JavaScript) and backend servers.