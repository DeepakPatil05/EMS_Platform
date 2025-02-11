# Event Management System (EMS) Platform

## Overview

The Event Management System (EMS) Platform is a web-based application designed to help users manage events efficiently. With this platform, users can create, view, update, and delete events, making it a comprehensive tool for event planning and organization. Whether you're managing a small gathering or a large conference, the EMS Platform simplifies the process.

## ✨ Key Features
- ➕ Add Events: Create new events with details like name, date, time, location, and description.

- 👀 View Events: Browse through a list of all events with essential details.

- ✏️ Update Events: Edit event information to keep it up-to-date.

- ❌ Delete Events: Remove events that are no longer needed.

- 🎨 User-Friendly Interface: Clean and responsive design for seamless navigation.

- 📈 Scalable: Built with modern technologies to handle events of any scale.

## 🛠️ Tech Stack
- 🌐 Frontend: React.js

- 🔧 Backend: Node.js, Express.js

- 🗃️ Database: MongoDB

- 🔐 Authentication: JWT (JSON Web Tokens)

## 📂 Project Structure
- 📱 Frontend: Handles the user interface and interactions.

- ⚙️ Backend: Manages APIs, database operations, and business logic.

- 💾 Database: Stores event details and user information.

## 🚀 Getting Started

### 📝 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js and npm (Node Package Manager)
- MongoDB or any other database system
- Git (for version control)

### ⚙️ Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/DeepakPatil05/EMS_Platform.git
   cd ems-platform
   ```

2. **Install Dependencies**

   Navigate to the project directory and install the required dependencies for both the frontend and backend.

   ```bash
   # Install backend dependencies
   cd api
   npm install

   # Install frontend dependencies
   cd ../client
   npm install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the backend directory and add the necessary environment variables:

   ```env
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/ems
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Run the Application**

   Start the backend server and the frontend development server.

   ```bash
   # Start the backend server
   cd api
   npm start

   # Start the frontend development server
   cd ../client
   npm start
   ```

5. **Access the Platform**

   Open your browser and navigate to `http://localhost:5173` to access the EMS Platform.

## Usage

- **Adding an Event**: Click on the "Add Event" button, fill in the required details, and submit the form.
- **Viewing Events**: The homepage displays a list of all events. Click on an event to view more details.
- **Updating an Event**: Navigate to the event details page and click on the "Edit" button to update the event information.
- **Deleting an Event**: On the event details page, click on the "Delete" button to remove the event.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to all the open-source libraries and tools used in this project.
- Inspiration from various event management platforms. 

---

Thank you for using the EMS Platform! We hope it helps you manage your events more efficiently.
