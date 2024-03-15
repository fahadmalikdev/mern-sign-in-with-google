# MERN Stack (Sign In with Google) Application

![ss mern_sign_w_google](https://github.com/fahadmalikdev/mern-sign-in-with-google/assets/33700606/6f829bea-47cf-45f2-89c7-da2e96d0a8d2)

This repository hosts a MERN (MongoDB, Express.js, React, Node.js) stack application, featuring a server built with Node.js and a client built with React.

## Setup

To set up the project, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `client` directory using your terminal/command prompt.
3. Run `npm install` to install the necessary client dependencies.
4. Navigate to the `server` directory using your terminal/command prompt.
5. Run `npm install` to install the necessary server dependencies.

## Server

The server is built with Node.js. Below are the configurations and scripts used for the server:
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
}

### Configuration

In the `server` directory, you'll find a file named `index.js`. Here's the relevant configuration:

javascript
const cors = require('cors');

app.use(cors({
    origin: "http://localhost:3001",
    methods: "GET,POST,PUT,DELETE",
    credentials: true
}));

const clientId = "<YOUR_API_KEY>";
const clientSecret = "<YOUR_API_SECRET>";


## Usage


After setting up the project, you can run both the server and client using the provided scripts. Make sure MongoDB is running, and the necessary environment variables are set up, especially the Google API key and secret.

Feel free to explore and modify the code according to your requirements. If you encounter any issues or have any suggestions, please feel free to open an issue or contribute to the project by creating a pull request.

Happy coding! 🚀
