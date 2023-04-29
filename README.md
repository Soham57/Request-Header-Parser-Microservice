# Request Header Parser Microservice

This is a full-stack JavaScript application that parses a request header and returns the relevant information as a JSON response.

Features
The application listens for HTTP requests on a specified port, parses the request headers and returns a JSON response with the relevant information.
The JSON response includes the client's IP address, preferred language and software used to make the request.
Installation
Clone the repository: git clone https://github.com/Soham57/Request-Header-Parser-Microservice.git
Install the dependencies: npm install
Usage
Start the server: npm start
Open your web browser and navigate to http://localhost:3000/.
The server will parse the request header and return a JSON response.
Example Response

{
"ipaddress": "::ffff:159.20.14.100",
"language": "en-US,en;q=0.5",
"software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
Technologies Used
Node.js
Express.js
License
This project is licensed under the MIT License. See the LICENSE file for more information.
