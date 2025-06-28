DocSpot – Seamless Appointment Booking for Health

Project Overview

DocSpot is a full-stack web application that enables patients to book, reschedule, and manage medical appointments online. It supports doctor discovery, appointment scheduling, secure payments, digital prescriptions, and (optionally) video consultations. The platform is designed for three roles — Patient, Doctor, and Admin — and provides smooth, real-time interaction across the healthcare workflow.

Tech Stack:

Frontend: React.js, Bootstrap, Material UI, MDB UI Kit Backend: Node.js, Express.js Database: MongoDB + Mongoose Authentication: JWT (JSON Web Tokens) Payment Gateway: Razorpay API Communication: Axios

📁 Project Structure

Project Files/ ├── frontend/ │ ├── public/ │ └── src/ │ ├── components/ │ ├── pages/ │ ├── assets/ │ └── App.js ├── backend/ │ ├── controllers/ │ ├── models/ │ ├── routes/ │ ├── config/ │ └── index.js ├── .env.example ├── README.md ├── admin/ │ ├── public/ │ └── src/ │ ├── assets/ │ ├── components/ │ ├── context/ │ └── pages/ │ ├── Admin/ │ └── Doctor/

⚙ Setup Instructions

Clone the Project
git clone https://github.comRajeswari1606/docspot.git
cd docspot
2. Install Backend Dependencies
cd (project folder name ,when you enter in correct folder then do below steps)
npm install
3. Install Frontend Dependencies
cd (project folder name , ,when you enter in correct folder then do below steps)
npm install
4. Install admin Dependencies
cd (project folder name ,when you enter in correct folder then do below steps)
npm install
4. Configure Environment Variables
Create a .env file in /backend/ with the following:

init
PORT=5000
MONGO_URI=your_mongodb_connection_string(give your connection url)
RAZORPAY_KEY_ID=your_razorpay_key(give your coonection url)
RAZORPAY_KEY_SECRET=your_razorpay_secret(give your url)
JWT_SECRET=your_jwt_secret(give your connection url)
▶ Running the Application
Start Backend
bash
cd backend
npm start
Start Frontend
bash
cd frontend
npm run dev
Start Admin
bash
cd admin
npm run dev
✅ Key Features
Role-based login: Patient, Doctor, Admin

Doctor search with filters (specialization, location)

Appointment booking and cancellation

Razorpay payment integration

Doctor availability management

Admin dashboard for system management


📁 Notes
MongoDB must be running (local or Atlas)

Use .env to manage sensitive keys

Test credentials are available in /Documentation/ folder

👥 Developed By (Team)
Y.Divya Charitha , M. Rajeswari , B. Swarna Latha
