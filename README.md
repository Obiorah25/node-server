Node.js Task Series
This repository contains a series of tasks designed to help you learn and practice Node.js. Each task involves creating a small Node.js application or script to accomplish a specific goal.

Prerequisites
Node.js should be installed on your machine.
Familiarity with JavaScript and basic command-line usage.
Tasks Overview
1. Hello World
Objective: Create a simple Node.js script that prints "HELLO WORLD" to the console.
Steps:
Create a file named hello-world.js.
Write a program that prints "HELLO WORLD" to the console.
Run the program using Node.js by executing the command:
bash
Copy code
node hello-world.js
2. Simple HTTP Server
Objective: Create a basic Node.js server that listens on port 3000 and responds with HTML.
Steps:
Create a file named server.js.
Write a program that creates an HTTP server using the http module.
The server should respond with '<h1>Hello Node!!!!</h1>\n' when accessed at http://localhost:3000.
Start the server with the command:
bash
Copy code
node server.js
3. File System Operations
Objective: Work with the file system in Node.js to create and read files.
Steps:
Create a file named file-system.js.
Require the fs (file system) module in your script.
Write a program that:
Creates a file named welcome.txt with the content "Hello Node".
Reads the content from hello.txt and logs it to the console.
Run the program with the command:
bash
Copy code
node file-system.js
4. Password Generator
Objective: Generate random passwords using a Node.js package.
Steps:
Create a file named password-generator.js.
Install the generate-password package:
Copy code
npm install generate-password
Write a program that generates a random password using the package and logs it to the console.
Run the program with the command:
bash
Copy code
node password-generator.js
5. Email Sender
Objective: Send an email using Node.js.
Steps:
Create a file named email-sender.js.
Install the nodemailer package:
bash
Copy code
npm install nodemailer
Write a program that sends an email to yourself using nodemailer. Follow the guide from W3Schools if needed.
Run the program with the command:
bash
Copy code
node email-sender.js
Notes
Each task is independent and can be completed in any order.
Make sure to follow best practices, such as error handling and commenting your code.
For more information on the Node.js modules used, refer to the official documentation or the package links provided.
License
This project is licensed under the MIT License - see the LICENSE file for details.
