# Job Portal Website

This project is a Job Portal Website developed using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides features for posting jobs, viewing job listings, updating job details, and more.

![mern-job-portal-website](/job-portal-client/src//assets/MERN%20STACK.png)

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Features

- **Job Posting**: Users can post new job listings with details such as job title, company name, salary, and more.

- **Job Listings**: View a list of all jobs, sorted by the date of posting.

- **Job Details**: Retrieve detailed information about a specific job using its unique identifier.

- **User-Specific Jobs**: Users can view job listings based on their email, useful for tracking jobs posted by a specific user.

- **Job Update and Deletion**: Users can update and delete their posted jobs.

## Prerequisites

- Node.js and npm installed.
- MongoDB database.
- MongoDB connection URI.

## Installation

1. Clone the repository:

2. Navigate to the project directory:

3. Install dependencies:

## Usage

1. Set up your MongoDB connection URI in the `index.js` file.

2. Run the server and react-app in terminals of respective folder.

   ```bash
   npm start
   npm run dev
   ```

3. Change the ip addresses to local and access the application. Local Host: `http://localhost:5000`.

## API Endpoints

- **POST /post-job**: Create a new job listing.
- **GET /all-jobs**: Get all job listings.
- **GET /all-jobs/:id**: Get details of a specific job.
- **GET /myJobs/:email**: Get jobs based on the user's email.
- **DELETE /job/:id**: Delete a job listing.
- **PATCH /update-job/:id**: Update a job listing.

## Project Structure

- **client**: Frontend React application.
- **components**: Reusable React components.
- **context**: Application context providers.
- **pages**: React components representing different pages.
- **PrivateRoute**: Custom route component for private routes.
- **router**: Application routes configuration.
- **server**: Node.js and Express.js server code.
- **sidebar-filters**: React components for filtering job listings.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.
