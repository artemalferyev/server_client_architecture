Simple Client-Server Architecture

This project demonstrates a basic client-server architecture using Flask (Python) as the backend and HTML+JavaScript as the frontend. The server provides a simple API endpoint that returns a JSON message, and the client fetches and displays it dynamically.

Features
	•	Flask-based server with a /api/message endpoint
	•	CORS enabled for cross-origin requests
	•	Minimal frontend with HTML and JavaScript
	•	Runs locally on http://localhost:4000/

Project Structure

│── server.py       # Flask backend  
│── index.html      # Frontend  
│── README.md       # Documentation  

How to Run the Project
	1.	Install dependencies:
 pip install flask flask-cors  
 	2.	Run the server:
  python server.py  
  The server will start on http://localhost:4000.
	3.	Open client.html in a browser. The page will fetch and display the message from the server.

Example Output
Server response (JSON):
{"message": "Hello from the server!"}  
Client output (HTML page):
Message from the server  
Hello from the server!  

Technologies Used
	•	Flask (Python)
	•	Flask-CORS
	•	HTML, JavaScript

This is a simple example of client-server communication.
