# The Language Club - Backend

## Overview
The backend of The Language Club is built using Node.js and Express.js to serve RESTful APIs. It handles user authentication, role-based authorization, and manages resources such as users, courses, and bookings. The backend communicates securely with the frontend, allowing users to register, log in, and interact with courses according to their roles. MongoDB is used as the database to store all user and course-related data.

## Features

 **Authentication & Authorization:**
  - **JWT Authentication:** Users authenticate using JWT tokens which are passed with each request to ensure security.
  - Role-Based Access Control:
    - Users can have one of three roles - student, instructor, or admin.
    - Admins can assign roles to users (i.e., an instructor can be promoted to an Admin).
    - Students can select courses, while instructors and admins do not have this option.


## Technologies Used

- **Express.js:** For building dynamic user interfaces with reusable components.
- **MongoDB:** For secure sign-in and sign-out functionality.
- **JWT:** For custom styling and responsive design.
- **Bcrypt.js:** For adding smooth animations and transitions.
- **Mongoose:** For creating interactive and swipeable elements, especially for courses.

## Getting Started

**1. Clone the frontend repository:**
```bash
git clone <Repo URL>
cd <repo-folder>
```
**2. Install dependencies:**
```bash
npm install
```

**3. Start the frontend development server:**
```bash
npm run dev
```

**4. Access the frontend locally:**
    http://localhost:5000

## 📞 Contact

For any inquiries or issues, feel free to reach out:

- **Email:** [arif.aust.eng@gmail.com](mailto:arif.aust.eng@gmail.com)
- **LinkedIn:** [Md. Arifur Rahman](https://www.linkedin.com/in/engarif3/)
