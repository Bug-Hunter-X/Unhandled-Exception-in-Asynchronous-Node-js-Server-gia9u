# Unhandled Exception in Asynchronous Node.js Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions within asynchronous operations.  The `bug.js` file contains a server that simulates an asynchronous task that might throw an error.  Without proper error handling, this error causes the server to crash.

The solution, provided in `bugSolution.js`, shows how to gracefully handle this type of error using a `try...catch` block within the asynchronous operation.