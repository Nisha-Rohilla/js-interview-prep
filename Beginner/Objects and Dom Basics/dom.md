Q) What is the DOM?

Ans)
    DOM (Document Object Model) is a programming interface for HTML and XML documents.
    It represents the structure of a web page as a tree of objects so that JavaScript can access and manipulate the content, structure, and styles of the page.

        💻 Example HTML
                <h1 id="title">Hello World</h1>

        💻 Accessing DOM with JavaScript
                let heading = document.getElementById("title");

                console.log(heading);

        💻 Changing DOM Content
                let heading = document.getElementById("title");

                heading.textContent = "Hello JavaScript";

        🔍 Explanation

                The browser converts HTML into a DOM tree
                Each HTML element becomes a node/object
                JavaScript can read, modify, add, or delete elements

        🎯 One-Line Interview Answer

            The DOM is a tree-like representation of an HTML document that allows JavaScript to interact with and modify web page content.