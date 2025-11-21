WERQAMA SACCO – Savings & Loan Management System

The WERQAMA SACCO Management System is a full-featured MERN Stack (MongoDB, Express.js, React.js, Node.js) application designed to modernize and automate cooperative financial operations.
It provides secure, efficient, and user-friendly tools to manage member savings, loans, contributions, authentication, and financial reporting for small and medium-sized Savings and Credit Cooperatives (SACCOs).

🚀 Prerequisites

Before installing the system, ensure the following tools are installed on your machine:

1. Node.js & npm

Download and install Node.js (LTS Recommended):
🔗 https://nodejs.org/en/download

During installation:

Accept the license agreement

Keep the default destination

Ensure “Add to PATH” is checked

Verify installation:

node -v
npm -v

2. MongoDB (Atlas or Local)

You can use MongoDB Community or MongoDB Atlas Cloud.

👉 Setup MongoDB Atlas:

Visit: https://www.mongodb.com/try/download/community

Create a free MongoDB Atlas cluster

Add a database user and whitelist your IP

Copy your connection string:

mongodb+srv://<username>:<password>@cluster0.mongodb.net/werqama_sacco

📁 Project Structure
WERQAMA-SACCO/
│
├── backend/
│   ├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── .env
│
└── README.md

🔐 Environment Variables
Create a .env file in the backend/ directory:
PORT=8080
MONGO_URI=<your_mongo_connection_string>
JWT_SECRET=<your_jwt_secret>
NODE_ENV=development

EMAIL_USER=<your_email>
EMAIL_PASS=<your_email_app_password>

CHAPA_PUBLIC_KEY=<your_chapa_public_key>
CHAPA_SECRET_KEY=<your_chapa_secret_key>

FRONTEND_URL=http://localhost:3000
BASE_URL=http://localhost:8080

FAYDA_BASE_URL=https://fayda-auth.vercel.app
FAYDA_API_KEY=<your_fayda_api_key>

Optional: .env in frontend/

Used for frontend-specific configurations.

🛠️ Installation Guide
1. Clone the Repository
git clone https://github.com/girmaygebray/WERQAMA-SACCO-Saving-Loan-Management-System.git 
cd Werqama-Sacco-System

2. Install Backend Dependencies
cd backend
npm install

3. Install Frontend Dependencies

(Open a new terminal)

cd frontend
npm install


After installation, run backend & frontend separately.

🧰 Technologies Used
Layer	Technologies Used
Frontend	React.js, Axios, TailwindCSS, BootstrapCSS
Backend	Node.js, Express.js
Database	MongoDB, Mongoose
Authentication	JWT, FAYDA (Ethiopian Digital ID Verification)
Hosting	MongoDB Atlas
📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Girmay Gebray – MERN Stack Developer
GitHub: https://github.com/girmaygebray 

Email: ggebray@gmail.com 
