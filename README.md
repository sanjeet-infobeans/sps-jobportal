# Job Portal (MERN + MySQL)

## Overview
A job portal platform built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with MySQL as the database. The platform allows multiple recruiters to post jobs and receive applications from candidates.

## Features
- User authentication (Recruiter & Job Seeker)
- Recruiters can post job listings
- Job seekers can browse and apply for jobs
- Admin dashboard to manage users and jobs
- Secure API endpoints

## Tech Stack
- **Frontend**: React.js, Redux
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Token)
- **Styling**: Tailwind CSS

## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MySQL
- npm or yarn

### Clone the Repository
```sh
git clone https://github.com/yourusername/job-portal.git
cd job-portal
```

### Backend Setup
1. Navigate to the `server` directory:
   ```sh
   cd server
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the `server` folder and add the following:
   ```env
   PORT=5000
   DB_HOST=localhost
   DB_USER=root
   DB_PASSWORD=yourpassword
   DB_NAME=job_portal
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```sh
   npm start
   ```

### Frontend Setup
1. Navigate to the `client` directory:
   ```sh
   cd ../client
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend server:
   ```sh
   npm start
   ```

## API Endpoints
| Method | Endpoint       | Description |
|--------|---------------|-------------|
| GET    | /jobs         | Get all job postings |
| POST   | /apply        | Apply for a job |
| POST   | /auth/signup  | User signup |
| POST   | /auth/login   | User login |

## License
This project is licensed under the MIT License.

