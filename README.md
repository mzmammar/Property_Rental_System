# Property_Rental_System

This project is a comprehensive property rental system developed using the MERN stack, with a primary focus on front-end development. It allows users to rent properties and list their own properties for rent. The front-end is built using React.js to create dynamic and responsive user interfaces, ensuring a seamless user experience. For layout creation and styling, HTML and CSS were employed, adhering to best practices in web design.

# Features
1. *Easy Booking*: Book houses, apartments, villas, or any kind of properties for rent.
2. *Search Destinations*: Search properties using the name of the city or state where they are located.
3. *Filter Options*: Filter properties based on price range, property type, room type, and amenities.
4. *Secure Payments*: Easy and secure payment integration using Stripe.
5. *Manage Bookings*: Users can manage their bookings conveniently.
6. *Property Listings*: Users can list their own properties for rent.
7. *User Profile Editing*: Users can edit their profile information, including changing passwords, usernames, and phone numbers.
8. *Forgot Password*: Users can reset their password, with the process tested using Mailtrap.

# Technologies Used
React.js: For building the front-end user interface
Node.js: For running the back-end server
Express.js: For handling back-end routes and middleware
MongoDB: For database management
HTML/CSS: For layout creation and styling

# Prerequisites
Before you begin, ensure you have met the following requirements:

Node.js and npm installed on your local machine
MongoDB installed and running
A code editor like Visual Studio Code
Getting Started
To get a local copy up and running, follow these simple steps:

1. Clone the repository
git clone https://github.com/your-username/property-rental-system.git
cd property-rental-system

3. Install dependencies
Navigate to the project starter code folder and install the required dependencies for both the front-end and back-end:

cd frontend
npm install

cd ../backend
npm install

3. Set up the MongoDB database
Ensure that MongoDB is installed and running on your machine. Import the provided SQL file into MongoDB before connecting. This step might require using a tool like MongoDB Compass or the mongo shell.

4. Connect to the MongoDB database
In the backend folder, create a .env file and add your MongoDB connection string:
MONGO_URI=your_mongodb_connection_string

6. Run the application
Open your code editor (e.g., Visual Studio Code) and navigate to the project folder. Run the following commands to start both the backend and frontend servers:

# In one terminal, start the backend server
cd backend
npm start

# In another terminal, start the frontend server
cd frontend
npm start
6. View the application in the browser
Open your web browser and navigate to http://localhost:3000 to view the Property Rental System.

# Usage
User Registration and Login: Users can register and log in to their accounts.
Listing Properties: Registered users can list their properties for rent.
Renting Properties: Users can browse available properties and rent them.

# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

