# Explore

Explore is a web application built using the MERN stack. It provides users with a platform to document and share their travel experiences. Integrated with user authentication, Google Maps API, and CRUD operations, Explore offers a seamless experience for users to post and discover new places.

## Tech Stack
- React.js
- Node.js
- Express.js
- MongoDB
- Google Maps API

## Features
- User Authentication: Allows users to sign up, log in, and log out securely.
- Google Maps Integration: Enables users to pinpoint and display their visited places on the map.
- CRUD Operations: Users can create, read, update, and delete their posts.

##Note: The frontend and backend folders are refered as client and server.

## Installation
1. Clone the repository: `git clone https://github.com/sandeep-069/Explore.git`
2. Navigate to the project directory: `cd Explore`
3. Install dependencies for the client: `cd client && npm install`
4. Install dependencies for the server: `cd .. && cd server && npm install`
5. Create a `.env` file for the client in the client directory and add the following content:

```plaintext
REACT_APP_GOOGLE_API_KEY=your_google_api_key
REACT_APP_BACKEND_URL=http://localhost:5000/api
REACT_APP_ASSET_URL=http://localhost:5000
```

6. Create a nodemon.json file for the server in the server directory and add the following content:

```
{
    "env": {
        "DB_URL": "your_mongodb_connection_url",
        "GOOGLE_API_KEY": "your_google_api_key",
        "JWT_KEY": ""
    }
}
```

6. Start both client and server using: `npm start`

## Screenshots
![Home](/images/s1.jpg)
![Login](/images/s2.jpg)
![Add Place](/images/s3.jpg)
![My Places](/images/s4.jpg)


