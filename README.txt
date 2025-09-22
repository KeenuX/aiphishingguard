phishing-url-detector/
│
├─ index.html           # Frontend HTML file
├─ style.css            # Optional separate CSS file
├─ backend/
│   ├─ server.js        # Node.js backend
│   ├─ package.json
│   └─ .env             # Your Google API key



A modern, immersive web application that detects phishing and malicious URLs using Google Safe Browsing API.
The frontend is built with HTML, CSS (Glassmorphism + animated backgrounds) and communicates with a Node.js + Express backend for real-time URL analysis.

Features

Modern, immersive design with glassmorphism and animated floating circles.

Input field to enter URLs for phishing detection.

Real-time detection using Google Safe Browsing API.

Safe-to-use test URLs for verification.

Dynamic result display with green/red alerts for safe or phishing URLs.

Backend API built with Node.js + Express, handling URL requests securely.

Technologies Used

Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express.js

API: Google Safe Browsing API v4

Other: Axios (HTTP requests)


Setup Instructions
1. Clone the repository
git clone <repository-url>
cd phishing-url-detector

2. Set up backend

Navigate to the backend folder (if separate):

cd backend


Install dependencies:

npm install


Create a .env file with your Google API Key:

GOOGLE_API_KEY=YOUR_GOOGLE_SAFE_BROWSING_API_KEY


Start the backend server:

node server.js


Server will run at http://localhost:5000.


Setup Instructions
1. Clone the repository
git clone <repository-url>
cd phishing-url-detector

2. Set up backend

Navigate to the backend folder (if separate):

cd backend


Install dependencies:

npm install


Create a .env file with your Google API Key:

GOOGLE_API_KEY=YOUR_GOOGLE_SAFE_BROWSING_API_KEY


Start the backend server:

node server.js


Server will run at http://localhost:5000.
