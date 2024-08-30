# YOURHR - MERN Stack Job Portal

**YOURHR** is a robust job portal application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This platform empowers users to explore job opportunities, apply for positions, and effortlessly manage their applications.

## Key Features

- **User Authentication:** Secure login and registration for both job seekers and employers using JWT (JSON Web Tokens).
- **Job Listings:** Explore a variety of job listings stored in MongoDB.
- **Responsive Design:** Optimized for a seamless experience across devices of all sizes.

## Technologies Used

- **Frontend:** React.js, React Router, Bootstrap
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JWT (JSON Web Tokens), Bcrypt for secure password hashing
- **Image Upload:** Cloudinary for efficient image storage and management
- **Deployment:** Vercel (frontend), Render (backend), MongoDB Atlas (database)

## Getting Started

To set up a local version of this application, follow these steps:

### Prerequisites

- Ensure Node.js is installed (version 22.2.0 or higher recommended)
- Set up a MongoDB Atlas account (or use a local MongoDB instance)
- Create a Cloudinary account for image storage

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/srinjoy29/Project--YOURHR.git

2. **Install the required NPM packages:**

   ```bash
   cd jobquest
   cd backend
   npm install
   cd ../frontend
   npm install

3. **Set up environment variables:**
Create a config.env file in the config folder within the backend directory with the following content:
PORT=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=
FRONTEND_URL=
DB_URL=
JWT_SECRET_KEY=
JWT_EXPIRE=
COOKIE_EXPIRE=

4. **Start the application:**
   ```bash
   npm start 

5. Open your browser and visit http://localhost:5173 to explore the app.


## Contact ##
For any queries or feedback, feel free to reach out:

Your Github - https://github.com/srinjoy29

Project Link: https://yourhr-five.vercel.app/

Portfolio : https://srinjoy.online
