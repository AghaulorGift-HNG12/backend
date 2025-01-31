# Public API to Retrieve Basic Information

## Description

This project is a simple public API developed using **Node.js and Express.js**. It provides basic information, including:

- Email address.
- The current date and time in **ISO 8601 format** (UTC).
- The GitHub URL of the project's codebase.

## Features

- Accepts **GET requests**
- Returns **JSON responses**
- Generates **current datetime dynamically**
- Handles **CORS appropriately**
- Provides a **publicly accessible endpoint**

## Technologies Used

- **Node.js**
- **Express.js** (for building the API)
- **CORS** (to handle cross-origin requests)
- **GitHub** (for version control)

---

## API Documentation

### **Base URL:**

```
<your-deployment-url>
```

### **Endpoint: GET /**

#### **Response Format:**

```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

#### **Success Response:**

- **Status Code:** `200 OK`
- **Content-Type:** `application/json`

---

## Setup Instructions

### **1. Clone the Repository**
```bash
git clone https://github.com/AghaulorGift-HNG12/your-repo.git
cd your-repo
```

### **2. Install Dependencies**

```bash
npm install
```

### **3. Run the Server Locally**

```bash
node index.js
```
---

## Deployment

The API is deployed to a **publicly accessible endpoint**. To deploy it yourself, consider using:

- **Render**
- **Vercel**
- **Railway**
- **Heroku**
- **AWS Lambda with API Gateway**

---

## Example Usage

To test the API, you can use **cURL** or **Postman**:

```bash
curl -X GET <your-deployment-url>
```

Or, in JavaScript:

```javascript
fetch('<your-deployment-url>')
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## Resources

- [Node.js Developers](https://hng.tech/hire/nodejs-developers)

For any questions or contributions, feel free to open an **issue** or **pull request** on GitHub.
