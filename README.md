# [CampAtlas](https://yelpcamp-cloe.onrender.com)

**CampAtlas** is a web application designed to explore and manage camping sites. It allows users to discover various campgrounds, contribute reviews, and manage information about camping spots. Built using MongoDB, Express, Node.js, it provides a full-stack solution with robust functionality and security features.

## Features

- **User Authentication**: Secure login and registration using Passport.js.
- **Campground Management**: Users can add, edit, and delete camping site details.
- **Review System**: Visitors can leave reviews and ratings for camping sites.
- **Interactive Maps**: Integrated with Mapbox for a dynamic map interface.
- **Responsive Design**: Built with Bootstrap for a seamless user experience across devices.

## Tech Stack

### Frontend
- **HTML** and **EJS** for templating.
- **Bootstrap** for styling.

### Backend
- **Node.js** with **Express.js** for server-side operations.
- **MongoDB** for the database.
- **Passport.js** for authentication.
- **RESTful APIs** for CRUD operations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rohit-893/CampAtlas.git
   cd CampAtlas
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following:
     ```
     DATABASE_URL=<your-mongodb-url>
     MAPBOX_TOKEN=<your-mapbox-token>
     SESSION_SECRET=<your-session-secret>
     ```

4. Run the application:
   ```bash
   nodemon app.js
   ```

5. Open your browser and visit `http://localhost:3000`.
