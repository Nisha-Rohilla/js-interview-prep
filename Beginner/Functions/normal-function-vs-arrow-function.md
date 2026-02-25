Q) What is the difference between a normal function and an arrow function?

Ans)
    A normal function uses the function keyword and has its own this, while an arrow function uses the => syntax and does not have its own this.
    Arrow functions provide shorter syntax and are commonly used in modern JavaScript and React.

        💻 Code Examples
                🔹 Normal Function
                function greet() {
                console.log("Hello");
                }
                greet();

                🔹 Arrow Function
                const greet = () => {
                console.log("Hello");
                };
                greet();

                🔹 this Keyword Difference (Very Important)
                Normal Function
                const user = {
                name: "Nisha",
                greet: function () {
                    console.log(this.name);
                }
                };

                user.greet(); // "Nisha"
                Arrow Function
                const user = {
                name: "Nisha",
                greet: () => {
                    console.log(this.name);
                }
                };

                user.greet(); // undefined

                👉 Arrow functions do not have their own this.

        🔍 Key Differences

        Feature	            Normal Function	                Arrow Function
        Syntax	            Uses function keyword	        Uses =>
        this	            Has its own this	            Inherits this
        Hoisting	        Hoisted	                        Not hoisted
        Arguments object	Available	                    Not available
        Use case	        General purpose	                Callbacks, React
        
        🎯 One-Line Interview Answer

        Normal functions have their own this, while arrow functions do not and provide a shorter syntax.