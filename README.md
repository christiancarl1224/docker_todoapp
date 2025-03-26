# Docker Node.js application

A lightweight Node.js API application containerized with Docker. This project provides basic CRUD (Create, Read, Update, Delete) operations for managing items.

## Tech Stack

- **Node.js**: JavaScript runtime
- **Express**: Web framework
- **PostgreSQL/SQLite**: Database options
- **Docker**: Containerization

## Prerequisites

- **Node.js** (v18 recommended)
- **Docker**
- **npm**

## Getting Started

### Running Locally

1. **Clone this repository**
2. **Install dependencies**
    ```bash
    npm install
    ```
3. **Start the development server**
    ```bash
    npm run dev
    ```
    The API will be available at [http://localhost:3000](http://localhost:3000)

### Running with Docker

1. **Build the Docker image**
    ```bash
    docker build -t docker-nodejs .
    ```
2. **Run the container**
    ```bash
    docker run -p 3000:3000 docker-nodejs
    ```
    The API will be available at [http://localhost:3000](http://localhost:3000)

## Available Scripts

- `npm start` - Start the application
- `npm run dev` - Start the application with hot-reloading using nodemon
- `npm run prettify` - Format code using Prettier
- `npm test` - Run tests using Jest