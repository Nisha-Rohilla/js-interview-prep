Q) What is document.getElementById()?

Ans)
    document.getElementById() is a DOM method used to select an HTML element by its id.
    It returns the element object so JavaScript can manipulate its content, style, or attributes.

        💻 HTML Example
                <h1 id="title">Hello</h1>

        💻 JavaScript Example
                let element = document.getElementById("title");
                console.log(element);

        🔹 Changing Text Content
                 document.getElementById("title").textContent = "Hello Nisha";

        🔹 Changing Style
                 document.getElementById("title").style.color = "blue";

        🔍 Explanation 

            document → represents the web page
            getElementById() → selects an element using its id
            Returns a single element (IDs are unique)

        🎯 One-Line Interview Answer

            document.getElementById() is a DOM method used to select an HTML element using its id.