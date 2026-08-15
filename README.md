# wanderlust-stays
A full-stack travel accommodation platform inspired by Airbnb, built with Node.js, Express, MongoDB, and EJS, featuring property listings, authentication, reviews, maps, and responsive UI.

# Wanderlust – Travel Stay Platform

> A modern, responsive and full-stack travel accommodation platform inspired by Airbnb.

Wanderlust is a full-stack web application that allows users to explore, create, edit and manage travel accommodation listings through an intuitive and responsive interface. The project focuses on real-world web development concepts such as authentication, authorization, CRUD operations, RESTful APIs, database management, image handling, map integration and responsive UI design.

## Features

* Browse and explore available stays
* Search and discover listings
* Create new property listings
* Edit and update existing listings
* Delete listings
* User authentication and authorization
* Protected routes for authorized users
* Reviews and ratings
* Image upload and cloud-based image management
* Location-based map integration
* Dynamic pricing and tax information
* Flash messages for user actions
* Fully responsive design
* Clean and modern Airbnb-inspired user interface
* RESTful routing and backend architecture

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap
* EJS

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB
* MongoDB Atlas

### Authentication and Services

* Passport.js
* Cloudinary
* Mapbox

### Development and Deployment

* Git
* GitHub
* VS Code
* Render

## Project Structure

```text
Wanderlust/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
│   ├── css/
│   └── js/
├── utils/
├── init/
├── middleware.js
├── app.js
├── schema.js
├── package.json
└── README.md
```

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/anushkavish4-png/wanderlust-stays.git
```

### 2. Navigate to the Project

```bash
cd wanderlust-stays
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory and add the required credentials:

```env
ATLASDB_URL=your_mongodb_connection_string
SECRET=your_session_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
MAP_TOKEN=your_mapbox_token
```

### 5. Start the Application

```bash
node app.js
```

Or, if using Nodemon:

```bash
nodemon app.js
```

The application will run locally on:

```text
http://localhost:8080
```

## Project Highlights

### Home and Listings

A clean and responsive interface where users can explore different stays and properties.

### Property Details

Each listing provides important information such as:

* Property title
* Description
* Location
* Price
* Images
* Reviews
* Map location

### Authentication

Users can securely register and log in to access features based on their authentication status.

### Listing Management

Authenticated users can create, update and delete their own property listings.

### Reviews and Ratings

Users can add reviews and ratings to share their experience with different properties.

### Interactive Maps

Map integration allows users to visualize the location of listed properties.

### Responsive Design

The application is designed to provide a consistent experience across:

* Desktop
* Tablet
* Mobile

## Core Application Flow

```text
User
  |
  v
Register / Login
  |
  v
Explore Listings
  |
  v
View Property
  |
  +----> Create Listing
  |
  +----> Edit Listing
  |
  +----> Delete Listing
  |
  +----> Add Review
  |
  v
Explore Location on Map
```

## What I Learned

Through this project, I gained practical experience in:

* Building a full-stack web application
* Implementing MVC architecture
* Designing RESTful routes and APIs
* Performing CRUD operations
* Managing MongoDB databases
* Implementing user authentication and authorization
* Working with Express.js routing
* Using EJS templating
* Implementing middleware
* Managing images with Cloudinary
* Integrating Mapbox
* Creating responsive web interfaces
* Using Git and GitHub for version control
* Deploying applications using Render

## Future Improvements

* Online booking and payment system
* Wishlist functionality
* Advanced search and filtering
* Email notifications
* User profile dashboard
* Host analytics dashboard
* Enhanced review and rating system
* Improved recommendation system

## Live Demo

Live Project:

https://wanderlust-stays-22ab.onrender.com

## GitHub Repository

Repository:

https://github.com/anushkavish4-png/wanderlust-stays

## Developer

### Anushka Vishwakarma

A passionate web development learner focused on building real-world applications and strengthening full-stack development skills.

## Acknowledgements

This project was built as a practical full-stack development project to understand and implement modern web development concepts, backend architecture, database integration, authentication and deployment.

## License

This project is created for educational and portfolio purposes.

---

Made with Node.js, Express.js, MongoDB and EJS.

