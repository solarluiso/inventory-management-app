# Inventory Management Dashboard Application

This repository contains the code for a Fullstack Inventory Management Dashboard built with Next.js, Node.js, and integrated with AWS services. The application enables efficient management of inventory data, offering features like data visualization, user management, and CRUD operations.

## How to Use It

1.  Clone the repository: `git clone https://github.com/solarluiso/invetnory-management-app`
2.  Navigate to the client or server directory to set up each environment individually.

## Requirements

- **NODE**: Ensure Node.js is installed on your operating system.
- **GIT**: Required for cloning the repository.
- **PostgreSQL**: Database for backend services.
- **AWS Account**: For deployment and cloud services.

## Configuration Steps

1. Client Setup

   1. Navigate to the client directory: `cd client`
   2. Install dependencies: `npm install
   3. Set up environment variables by creating a `.env` file using the provided template.
   4. Start the development server: `npm run dev`
   5. To build and deploy the application: `npm run build` `npm start`

2. Server Setup

   1. Open a new terminal and Navigate to the server directory: `cd server`
   2. Install dependencies: `npm install`
   3. Set up environment variables by creating a `.env` file using the provided template.
   4. Seed the database (if required): `npm run seed`
   5. Start the development server: `npm run dev`
   6. To build and deploy the server: `npm run build` `npm start`

## Tech Stack

### Frontend:

- **Next.js**: Framework for server-rendered React applications.

- **TailwindCSS**: Utility-first CSS framework for styling.

- **Redux Toolkit**: State management.

- **Recharts**: Charting library for visualizing data.

- **MUI Data Grid**: Advanced data grid for inventory display.

### Backend:

- **Node.js**: Backend runtime.

- **Express**: Web framework for APIs.

- **Prisma**: ORM for database management.

- **PostgreSQL**: Relational database for backend storage.

### AWS Deployment:

- **AWS EC2**: For hosting backend services.

- **AWS RDS**: Managed PostgreSQL database.

- **AWS S3**: Object storage for static assets and backups.

- **AWS Amplify**: Deployment and hosting of frontend.

- **AWS API Gateway**: Manage API traffic for the backend.

### Additional Tools:

- **dotenv**: Environment variable management.

- **Helmet**: Enhancing security for Express applications.

- **Morgan**: HTTP request logging middleware.
