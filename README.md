# Natours App

A full stack web application specially designed for individuals who have a passion for traveling and enjoy tour vacations. The project is developed using Node.js, Express, and MongoDB, providing a seamless and interactive experience for users to explore and book exciting tours around the world.

## Features

- **Authentication and Authorization**
  - Sign up, Log in, Logout, Update, and reset password.
- **User profile**
  - Update username, photo, email, password, and other information
  - A user can be either a regular user or an admin or a lead guide or a guide.
  - When a user signs up, that user by default regular user.
- **Tour**
  - Manage booking, check tour map, check users' reviews and rating
  - Tours can be created by an admin user or a lead-guide.
  - Tours can be seen by every user.
  - Tours can be updated by an admin user or a lead guide.
  - Tours can be deleted by an admin user or a lead-guide.
- **Bookings**
  - Only regular users can book tours (make a payment).
  - Regular users can not book the same tour twice.
  - Regular users can see all the tours they have booked.
  - An admin user or a lead guide can see every booking on the app.
  - An admin user or a lead guide can delete any booking.
  - An admin user or a lead guide can create a booking (manually, without payment).
  - An admin user or a lead guide can not create a booking for the same user twice.
  - An admin user or a lead guide can edit any booking.
- **Reviews**
  - Only regular users can write reviews for tours that they have booked.
  - All users can see the reviews of each tour.
  - Regular users can edit and delete their own reviews.
  - Regular users can not review the same tour twice.
  - An admin can delete any review.
- **Favorite Tours**
  - A regular user can add any of their booked tours to their list of favorite tours.
  - A regular user can remove a tour from their list of favorite tours.
  - A regular user can not add a tour to their list of favorite tours when it is already a favorite.
- **Credit card Payment**

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Make sure you have the following installed:

- Node.js: [Download and Install Node.js](https://nodejs.org/)
- MongoDB: [Download and Install MongoDB](https://www.mongodb.com/try/download/community)

### Installing

A step by step series of examples that tell you how to get a development env running

1. **Clone the repository:**

```bash
git clone https://github.com/mohammedhassad/natours-app.git
```

2. **Install dependencies:**

```bash
cd natours-app
npm install
```

3. **Set up the environment variables:**

   Create a `.env` file in the root directory and set the required environment variables. You can use the provided `example.env` as a template.

4. **Run the application:**

```bash
npm start  # The application will be accessible at http://localhost:3000
```

## Tech Stack

- [NodeJS](https://nodejs.org/en/) - JS runtime environment
- [Express](http://expressjs.com/) - The web framework used
- [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
- [Pug](https://pugjs.org/api/getting-started.html) - High performance template engine
- [JSON Web Token](https://jwt.io/) - Security token
- [ParcelJS](https://parceljs.org/) - Blazing fast, zero configuration web application bundler
- [Stripe](https://stripe.com/) - Online payment API and Making payments on the app.
- [Postman](https://www.getpostman.com/) - API testing
- [Mailtrap](https://mailtrap.io/) & [Sendgrid](https://sendgrid.com/) - Email delivery platform
- [Mapbox](https://www.mapbox.com/) - Displaying the different locations of each tour.

## Folder Structure

```
natours-app/
|-- public/              # Public assets
|-- src                  # Source code for the application
  |-- controllers/       # Controllers handling application logic
  |-- dev-data/          # Development data for testing
  |-- models/            # Data models for MongoDB
  |-- routes/            # Express routes
  |-- utils/             # Utility functions and helper modules
  |-- views/             # Pug templates for views
  |-- app.js             # Entry point for the application, sets up Express and middleware
|-- index.js             # Alternative entry point, responsible for starting the server
|-- .gitignore           # Git ignore file
|-- .prettierrc          # Prettier configuration for code formatting
|-- .eslintrc.json       # ESLint configuration for linting JavaScript code
|-- package.json         # Node.js dependencies and scripts
|-- README.md            # Project documentation
|-- example.env          # Example environment variable file
|-- LICENSE              # License file for the project
```

## Contributing

Pull requests are welcome but please open an issue and discuss what you will do before 😊

## Known Bugs

Feel free to email me at [Email](mailto:mohammed.hassad98@gmail.com) or [Lnkedin](https://linkedin.com/me/mohemedhassad) if you run into any issues or have questions, ideas or concerns. Please enjoy and feel free to share your opinion, constructive criticism, or comments about my work. Thank you! 🙂

## License

This project is licensed under the [MIT License](/LICENSE). Feel free to use, modify, and distribute the code.
