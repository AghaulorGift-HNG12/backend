# Number Classification API

## Overview
The **Number Classification API** is a RESTful API that takes an integer as input and returns its mathematical properties, including whether it is prime, perfect, Armstrong, even/odd, and the sum of its digits. It also fetches a fun fact about the number using the [Numbers API](http://numbersapi.com/).

---

## Features
âœ… Accepts an integer as a query parameter  
âœ… Identifies mathematical properties such as prime, perfect, Armstrong, even/odd  
âœ… Computes the sum of the numberâ€™s digits  
âœ… Fetches a fun fact from the Numbers API  
âœ… Returns structured JSON responses  
âœ… Handles errors gracefully  
âœ… Supports CORS for cross-origin access  

---

## API Specification

### **Base URL**
<your-deployment-url>/api/classify-number?number={integer}

Replace `<your-deployment-url>` with the actual deployed API URL.

### **Example Request**
```bash
GET /api/classify-number?number=371

## Installation & Usage
### Prerequisites
### Node.js installed
### Express.js for backend framework

## Setup
### Clone the repository:
git clone https://github.com/AghaulorGift-HNG12/backend.git
cd backend


Install dependencies:
npm install

Start the server:
node server.js
Access the API locally at:

http://localhost:5000/api/classify-number?number=371

## Deployment
### This API can be deployed on any cloud platform supporting Node.js, such as:

### Heroku
### Vercel
### Render
### AWS Lambda (via API Gateway)

## Project Structure

í³¦ numclassification-api
 â”£ í³œ server.js    # Main Express server
 â”£ í³œ package.json # Project dependencies
 â”£ í³œ README.md    # API documentation

## Technologies Used
### Node.js â€“ JavaScript runtime
### Express.js â€“ Web framework
### Axios â€“ API requests
### Numbers API â€“ Fun fact retrieval

## License
### This project is licensed under the MIT License.

## Author
(Aghaulor Gift)[Aghaulor Gift]
[aghaulor.gift@gmail.com](aghaulor.gift@gmail.com)
[https://github.com/AghaulorGift-HNG12](GitHub Profile)
