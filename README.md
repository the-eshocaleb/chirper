# Chirper - A Social Media Web App

Chirper is a social media platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It enables users to connect, share posts, and interact with a dynamic online community.

## Features

- **User Authentication**: Secure signup and login, powered by JWT (JSON Web Tokens).
- **Post Creation and Interaction**: Users can create, edit, and delete posts, as well as like and comment on others' posts.
- **Real-time Updates**: Leveraging WebSockets for real-time notifications and updates on user actions. \*In development.
- **Profile Customization**: Users can personalize their profiles, add profile pictures, and view their post history.
- **Responsive Design**: Optimized for both desktop and mobile views.

## Tech Stack

- **Frontend**: React.js with React Router for seamless navigation, Redux for state management, and Tailwind CSS for styling.
- **Backend**: Node.js with Express.js to handle API routes and authentication.
- **Database**: MongoDB, with Mongoose ORM to manage data relationships.
- **Real-time Communication**: Socket.IO for live interactions and notifications.

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/Chirper.git
   cd Chirper

   ```

2. **Install Dependencies**

   ### Install server-side dependencies:

    ```bash 
    cd server
    npm install
    ```

    ### Install client-side dependencies:
    ```bash 
    cd ../client
    npm install
    ```


3. **Environment Variables**

    Create a .env file in the server directory and add the following:

    ``` bash
    MONGO_URI=<Your MongoDB URI>
    JWT_SECRET=<Your JWT Secret>
    SOCKET_PORT=<Your Preferred Socket Port>

    ```


## Run the Application


**Start the server**:

```bash
cd server
npm start
```

**Start the client**:

```bash
cd ../client
npm start
``` 


## Access the Application

Go to http://localhost:3000 to access the Chirper app.


## Project Structure
```
Chirper/
│
├── server/ # Backend directory
│ ├── models/ # Mongoose models
│ ├── controllers/ # Controller functions
│ ├── routes/ # Express routes
│ ├── utils/ # Utility functions
│ └── app.js # Main server file
│
└── client/ # Frontend directory
├── src/
│ ├── components/ # Reusable components
│ ├── pages/ # Page components
│ ├── redux/ # Redux setup and actions
│ └── App.js # Main React component
```


## Contributors

    ALAGO VICTOR C.
    ESHO CALEB
    NGUYEN TRAN KHANH
    NGUYEN DUC TIN
