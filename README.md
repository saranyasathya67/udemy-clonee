Overview

This is a Udemy clone, an e-learning platform that allows users to browse, purchase, and enroll in online courses. The platform includes features for instructors to create courses, students to enroll in them, and an intuitive user interface for seamless learning.

Features

User authentication (Sign up, Login, Logout)

Course browsing and search functionality

Course purchase and enrollment

Video streaming for course content

Instructor dashboard for course creation and management

User profile management

Reviews and ratings system

Payment integration

Technologies Used

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT (JSON Web Tokens)

Payment Gateway: Stripe

Video Hosting: AWS S3 / Cloudinary

Installation

Prerequisites

Ensure you have the following installed:

Node.js (latest LTS version)

MongoDB (local or cloud-based like MongoDB Atlas)

Git

Steps to Run Locally

Clone the Repository

git clone https://github.com/your-username/udemy-clone.git
cd udemy-clone

Install Dependencies

cd backend
npm install
cd ../frontend
npm install

Set Up Environment Variables
Create a .env file in the backend directory and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET=your_stripe_secret_key
CLOUDINARY_URL=your_cloudinary_url

Run the Backend Server

cd backend
npm start

Run the Frontend Server

cd frontend
npm start

Deployment

Backend Deployment

Use platforms like Heroku, DigitalOcean, or AWS EC2.

Ensure environment variables are set up in the deployment settings.

Frontend Deployment

Use Vercel or Netlify for easy React app deployment.

Configure the API base URL in frontend .env.

Contributing

Contributions are welcome! Follow these steps to contribute:

Fork the repository.

Create a new branch: git checkout -b feature-name

Commit your changes: git commit -m 'Add new feature'

Push to the branch: git push origin feature-name

Open a Pull Request.

License

This project is licensed under the MIT License.

