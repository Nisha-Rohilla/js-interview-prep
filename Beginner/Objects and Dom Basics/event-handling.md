

Ans)
    Event handling is the process of responding to user actions such as clicks, key presses, mouse movements, or form submissions in a web page.
    JavaScript can detect these events and execute a function when they occur.

        💻 HTML Example
                <button onclick="showMessage()">Click Me</button>

        💻 JavaScript Example
                function showMessage() {
                console.log("Button clicked!");
                }

        🔹 Using addEventListener() (Recommended)
                let btn = document.getElementById("btn");

                btn.addEventListener("click", function () {
                console.log("Button clicked");
                });

        🔹 HTML
                <button id="btn">Click Me</button>


        🔍 Explanation 

                Event → user action (click, input, keypress, etc.)
                Event handler → function that runs when the event occurs
                addEventListener() is the modern way to handle events

                🎯 One-Line Interview Answer

                        Event handling is the process of executing JavaScript code in response to user actions like clicks or key presses.