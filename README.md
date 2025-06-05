CURE NEST 




This project focuses on developing an online doctor appointment system that allows patients to book appointments with doctors conveniently. The system streamlines the appointment process, reduces waiting times, and enhances efficiency in healthcare services. The project includes features such as user authentication, doctor availability tracking, appointment scheduling etc


Background- Digitization has revolutionized healthcare, improving efficiency and accessibility. Online systems simplify booking appointments, accessing records, and consulting doctors. These platforms reduce errors, save time, and enhance user convenience. Appointment systems streamline schedules, reduce overcrowding, and improve communication between patients and healthcare providers, making healthcare more effective.




Problem Statement -Manual appointment systems face issues like long waiting times, booking errors, and inconvenience for remote patients. The proposed solution is a user-friendly web application that allows patients to book, reschedule, or cancel appointments and helps doctors manage their schedules efficiently



## 📦 Tech Stack

**Frontend:**
* React.js
* HTML
* CSS
* JavaScript


**Backend:**
* Node.js
* Express.js

**Database:**
* MongoDB


**Other Tools:**
* Botpress Chatbot
* Git / GitHub (for Version Control)

## 📁 Folder Structure
CURE NEST/
│
├── backend/                  # Main Node.js/Express backend API 
│   └── server.js
│
├──frontend/                    # Citizen-facing React frontend
│   └── src/index.js
│
├── admin/
│   ├── backend/              # Admin Node.js/Express backend API
│   │   └── server.js
│   └── frontend/             # Admin React frontend
│       └── src/index.js
## 🚀 Quick Start (Development)

Follow these steps to get your development environment up and running.

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd "curenest"
    ```

2.  **Install dependencies:**
    * For the Citizen Backend:
        ```bash
        cd backend && npm install
        ```
    * For the Citizen Frontend:
        ```bash
        cd ../frontend && npm install
        ```
    * For the Admin:
        ```bash
        cd ../admin && npm install
        ```
    
3.  **Set up Environment Variables:**
    Create a `.env` file in both `backend/` and `admin/backend/` directories with the following:
    ```
    MONGODB_URI=your-mongodb-uri
    JWT_SECRET=your-jwt-secret
    ```
    * *Note*: Replace `your-mongodb-uri` with your MongoDB connection string and `your-jwt-secret` with a strong, random string.

4.  **Start Development Servers:**
    * **Citizen Backend:**
        ```bash
        cd backend
        npm start # Runs on http://localhost:4000
        ```
    * **Citizen Frontend:**
        ```bash
        cd ../frontend
        npm run dev # Runs on http://localhost:5173
        ```
    * **Admin :**
        ```bash
        cd ../admin/frontend
        npm run dev # Runs on http://localhost:5174
        ```

## ✅ Requirements

* Node.js (v14 or above)
* npm (Node Package Manager)
* MongoDB (local instance or cloud service like MongoDB Atlas)

## 🤝 Contributing

Contributions are always welcome! Feel free to:

* Fork the repository.
* Open issues for bug reports or feature requests.
* Submit pull requests with improvements.

## 📝 Notes

* Ensure your backend APIs are running and accessible to the frontends, especially during development and after deployment.
* For optimal security, use strong, randomly generated `JWT_SECRET` keys and never expose your `MONGODB_URI` publicly.
