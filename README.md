##Live Demo 
You can view the deployed application at the following link:
[Real Estate](https://real-estate-1-pthu.onrender.com)


######################################################

A Real Estate Web Application built with the MERN stack (MongoDB, Express, React, Node.js). This app allows users to browse, filter, and view details of listed properties.

Features
Browse property listings with search and filter options
View detailed property information
User authentication for contact access
Admin dashboard to manage property listings
Getting Started
Prerequisites
Ensure you have:

Node.js (v14+)
MongoDB (local or cloud)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/<your-username>/real-estate-app.git
cd real-estate-app
Install dependencies:

bash
Copy code
cd server
npm install
cd ../client
npm install
Environment Variables


In server/.env, add:
plaintext
Copy code
MONGODB_URL=mongodb://localhost:27017/realestateapp
JWT_SECRET=your_jwt_secret_key
PORT=5000

Running the App
Backend:
bash
Copy code
cd server
npm start
Frontend:

bash
Copy code
cd ../client
npm start
Open http://localhost:3000 to view in the browser.

Project Structure
client/ - Frontend (React)
server/ - Backend (Node.js, Express, MongoDB)
config/ - Environment configurations
routes/ - API routes for properties and users

