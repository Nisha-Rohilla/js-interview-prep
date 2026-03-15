Q) What is the difference between synchronous and asynchronous JavaScript?

Ans)
    Synchronous JavaScript executes code line by line, where each task waits for the previous one to complete.
    Asynchronous JavaScript allows tasks to run in the background without blocking the execution of other code.

        💻 Code Example
                🔹 Synchronous JavaScript
                        console.log("Start");

                        console.log("Task 1");

                        console.log("Task 2");

                        console.log("End");

                        👉 Output:

                                Start
                                Task 1
                                Task 2
                                End

                        Execution happens one line at a time.

                🔹 Asynchronous JavaScript
                        console.log("Start");

                        setTimeout(() => {
                        console.log("Async Task");
                        }, 2000);

                        console.log("End");

                        👉 Output:

                                Start
                                End
                                Async Task

                        The asynchronous task runs later without blocking the main thread.

        🔍 Key Differences
                Feature	                Synchronous	                    Asynchronous
                Execution	            Line by line	                Non-blocking
                Waiting	                Tasks wait for each other	    Tasks run in background
                Speed	                Slower for long tasks	        More efficient
                Example	                Normal function calls	        setTimeout, fetch, promises

        🎯 One-Line Interview Answer
                    Synchronous JavaScript runs code line by line, while asynchronous JavaScript allows tasks to execute without blocking the main thread.