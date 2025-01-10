# Hospital Management System

A comprehensive Hospital Management System designed to streamline the management of patients, staff, and appointments. This full-stack application ensures efficient healthcare operations with secure and user-friendly features.

## Features

- **User Authentication:** Secure login and role-based access control for admins, doctors, and patients.
- **Patient Management:** Manage patient records, including personal details, medical history, and appointments.
- **Appointment Scheduling:** Allow patients to book appointments and enable staff to manage schedules efficiently.
- **Staff Management:** Manage staff details, including doctors, nurses, and administrative personnel.
- **Dynamic Dashboard:** Real-time updates and intuitive navigation for smooth operations.

## Technologies Used

### Frontend:
- **React.js:** For building an interactive and responsive user interface.
- **HTML, CSS:** For structuring and styling the application.
- **Bootstrap:** For responsive design and user-friendly components.

### Backend:
- **Node.js & Express.js:** For developing a robust and scalable server-side application.

### Database:
- **MongoDB:** For secure storage of patient records, appointments, and staff details.

## Setup and Installation

### Prerequisites:
- Node.js installed on your system.
- MongoDB database set up and running.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/DeepakGaut/Hospital-Management-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Hospital-Management-system
   ```
3. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```
4. Install dependencies for the backend:
   ```bash
   cd ../backend
   npm install
   ```
5. Configure environment variables:
   - Create a `.env` file in the `backend` directory and add your MongoDB connection string and other necessary variables.

6. Start the application:
   - Start the backend:
     ```bash
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

### Accessing the App:
- Open your browser and go to `http://localhost:3000` to access the application.

## Project Structure
```
Hospital-Management-system
├── frontend
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       └── styles
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   └── utils
└── README.md
```

## Contribution
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your proposed changes.

## Contact
For any inquiries, please reach out to **Deepak Gautam** at [imdeepakgautam@gmail.com](mailto:imdeepakgautam@gmail.com).
