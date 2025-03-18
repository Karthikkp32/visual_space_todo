# visual_space_todo
A TODO platform using MERN full stack
# Express Task Manager API

This project is a simple Express-based API that connects to a MongoDB database and serves a task management application. It serves static files from a public directory and provides an API for managing tasks via defined routes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Routes](#routes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The project is built using Node.js, Express, and MongoDB. It leverages several middleware packages including:
- **CORS:** To enable cross-origin requests.
- **Body-parser:** To parse incoming JSON requests.
- **dotenv:** To manage environment variables.

The `server.js` file (see :contentReference[oaicite:0]{index=0}) is the main entry point of the application, which:
- Connects to MongoDB using a connection string from environment variables.
- Serves static files from the `public` directory.
- Sets up routes, including a route for handling task operations (`/tasks`).

## Features

- **MongoDB Integration:** Connects to a MongoDB database using Mongoose.
- **RESTful API:** Provides endpoints for managing tasks.
- **Static File Serving:** Delivers static content (HTML, CSS, JS) from the `public` directory.
- **Middleware:** Uses CORS and body-parser for handling cross-origin requests and JSON parsing.
- **Environment Variables:** Configurable via a `.env` file.

//outputs
![image](https://github.com/user-attachments/assets/03805f3e-084f-4894-abfb-c6e80b40664a)

![image](https://github.com/user-attachments/assets/c6de9750-11a9-4bcb-a261-428717234379)

![image](https://github.com/user-attachments/assets/90f8e265-4798-4a6c-9a3c-a6ce6b871052)

