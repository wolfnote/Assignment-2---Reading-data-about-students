JavaScript Async/Await and Promises
This repository demonstrates the use of Async/Await and Promises in JavaScript for handling asynchronous operations such as fetching data from a server. These examples are implemented in the context of managing and displaying a list of students.

Project Structure
The repository includes two HTML files with embedded JavaScript code:

Asynch_Await.html:

Implements asynchronous data fetching using async and await.
Provides user feedback via a loader animation while fetching data.
Parses student data from a remote source and displays it in a formatted text area.
Promise.html:

Demonstrates asynchronous operations using JavaScript Promises.
Includes .then, .catch, and .finally methods for handling promise resolution.
Fetches and processes student data from the same remote source and displays it dynamically.
Features
Common Features
Student Object:

Represents each student with the following properties:
name: Name of the student.
address: Address of the student.
phone: Contact number of the student.
course: Course in which the student is enrolled.
Provides a method getInfo() to format and return student details.
Data Parsing:

Extracts structured student information from a plain-text file format.
Handles scenarios with multiple students listed in the file.
Error Handling:

Handles network or file-related errors gracefully.
Displays meaningful error messages to the user.
Unique Features
Asynch_Await.html:

Uses async/await syntax for cleaner asynchronous code.
Updates the UI dynamically with a loader animation while fetching data.
Promise.html:

Utilizes Promises for asynchronous programming.
Demonstrates step-by-step chaining of operations with .then, .catch, and .finally.
How to Use
Clone this repository to your local machine:
bash
Copy code
git clone <repository-url>
Open the Asynch_Await.html or Promise.html files in a web browser.
Click the "Get Data" button to fetch and display student details.
Check the browser console for additional logs during execution.
Learning Objectives
Understand the differences between async/await and Promises for managing asynchronous JavaScript.
Explore best practices for error handling in asynchronous operations.
Learn how to parse and display dynamic data fetched from external sources.
Technologies Used
HTML: For structuring the user interface.
CSS: For styling elements, including loader animations.
JavaScript: For implementing asynchronous operations and data manipulation.
References
MDN Web Docs - Async/Await
MDN Web Docs - Promises
