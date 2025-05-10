# Interview Prep

## Overview

Interview Prep is a full-stack web application designed to streamline interview preparation by providing curated resources, practice questions, and essential guides. The platform offers a user-friendly interface for navigating various interview topics and techniques.

## Project Structure

The project is divided into two parts:

1. **Frontend** - Built with React and Tailwind CSS.
2. **Backend** - Developed using Express.js and MongoDB.

## Tech Stack

### Frontend

* React (v18.3.1)
* React Router DOM (v6.23.1)
* React Icons (v5.2.1)
* Tailwind CSS (v3.4.3)

### Backend

* Express (v4.19.2)
* Mongoose (v8.4.0)
* CORS (v2.8.5)
* Express Session (v1.18.0)

## Installation and Setup

### Prerequisites

* Node.js
* npm
* MongoDB

### Frontend Setup

```bash
cd interview-prep-front
npm install
npm start
```

### Backend Setup

```bash
cd interviewprep-backend
npm install
node index.js
```

## Running the Application

1. Start the backend server first:

   ```bash
   cd interviewprep-backend
   node index.js
   ```
2. Run the frontend application:

   ```bash
   cd interview-prep-front
   npm start
   ```
3. Visit the application at `http://localhost:3000`

## Features

* User Authentication
* Curated Interview Questions
* Interactive Practice Environment
* Dashboard to track progress

## Contributing

Contributions are welcome! Please fork the repository and create a pull request.

## License

This project is licensed under the ISC License.
