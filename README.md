**Project Overview**
A simple calculator microservice built using Node.js and Express, providing four arithmetic operations: addition, subtraction, multiplication, and division. Includes Winston logging for monitoring requests.


**Prerequisites**
Node.js (v18+ recommended)
Git
Visual Studio Code

**Installation and Setup**
git clone https://github.com/Dharani4432/sit737-2025-prac4p
cd sit737-2025-prac4p
npm install
npm install winston
node index.js

The server will start on http://localhost:3000.

**API Endpoints**
Addition: GET /add?num1=10&num2=5
Subtraction: GET /subtract?num1=10&num2=5
Multiplication: GET /multiply?num1=10&num2=5
Division: GET /divide?num1=10&num2=5

**Error Handling**
Invalid number inputs return a JSON error message.
Division by zero is handled gracefully.

**Logging with Winston**
Logs are stored in the logs/ directory:

error.log – stores error messages.
combined.log – stores all logs.

