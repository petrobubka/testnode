// Load environment variables from .env file
require('dotenv').config();

// Access the environment variable
const variable = process.env.VARIABLE;

// Print the value
console.log("The value of VARIABLE is:", variable);

// Start a simple server to display the variable in a browser
const http = require('http');

const server = http.createServer((req, res) => {
    res.writeHead(200, {'Content-Type': 'text/plain'});
    res.end(`The value of VARIABLE is: ${variable}`);
});

const PORT = process.env.PORT || 3000;
server.listen(PORT, () => {
    console.log(`Server is running on port ${PORT}`);
});
