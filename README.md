# 🩺 Doctor Appointment System  

A **full-stack doctor appointment booking system** that connects patients, doctors, and admins in one seamless platform.  
Built using **React.js, Node.js, Express, and MongoDB**.  

---

## 📌 Features

### 👩‍⚕️ For Patients
- Book appointments online  
- View and manage bookings  
- Receive appointment confirmations  

### 🩺 For Doctors
- Manage schedules & availability  
- Accept or decline appointment requests  

### 🛠️ For Admins
- View all users & doctors  
- Monitor bookings and manage system data  

---

## 🖼️ Project Structure
prescripto-full-stack/
│── frontend/ # Patient-side web app (React.js)
│── backend/ # REST API server (Node.js + Express + MongoDB)
│── admin/ # Admin dashboard (React.js)


---

## 🚀 Tech Stack

**Frontend:**  
- React.js  
- Redux (optional for state management)  
- Bootstrap / TailwindCSS  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB with Mongoose  

**Other Tools:**  
- JWT Authentication  
- bcrypt for password hashing  

---

## ⚙️ Installation & Setup

1️⃣ **Clone the Repository**  
bash
git clone https://github.com/yourusername/doctor-appointment-system.git
cd doctor-appointment-system
2️⃣ Install Dependencies

bash
Copy
Edit
cd backend && npm install
cd ../frontend && npm install
cd ../admin && npm install
3️⃣ Setup Environment Variables
Create .env files inside backend and frontend with keys like:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
4️⃣ Run the App
Backend:

bash
Copy
Edit
cd backend
npm start
Frontend:

bash
Copy
Edit
cd frontend
npm start
Admin Dashboard:

bash
Copy
Edit
cd admin
npm start
🛡 Security
Passwords are hashed using bcrypt

JWT tokens for secure authentication

Role-based access control (Admin, Doctor, Patient)

🏆 Future Enhancements
📱 Mobile App version

💳 Online payment integration

📩 Email/SMS reminders

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.


💡 Developed with ❤️ by Shreyas P Rayas
