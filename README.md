# ITVERSE-SERVER

Welcome to the ITVERSE-SERVER repository! This backend server is designed to support an EdTech e-commerce website, providing essential functionalities to manage users, courses, payments, and more.

## Installation

To get started with the ITVERSE-SERVER, follow these simple steps:

1. Clone this repository to your local machine using the following command:

```
git clone https://github.com/Joysd1010/ITVERSE-SERVER.git
```

2. Navigate into the project directory:

```
cd ITVERSE-SERVER
```

3. Install the required dependencies using npm:

```
npm install
```

## Usage

Before running the server, you need to configure your environment variables. Create a `.env` file in the root directory of the project and add the following variables:

```
PORT=3000
DB_USER=your_database_username
DB_PASS=your_database_password
JWT_SECRET=yoursecretkey
```

Replace `your_database_username` and `your_database_password` with your MongoDB database credentials.

Once you have configured your environment variables, you can start the server using the following command:

```
npm start
```

This will run the server on your local machine, allowing you to interact with it via HTTP requests.

## Dependencies

The ITVERSE-SERVER relies on the following dependencies:

- **cors**: Enables Cross-Origin Resource Sharing (CORS) for handling requests from different origins.
- **dotenv**: Loads environment variables from a .env file into process.env, making it easy to configure the application.
- **express**: A fast, unopinionated, minimalist web framework for Node.js, used for building the server and handling HTTP requests.
- **jsonwebtoken**: Enables the generation and verification of JSON Web Tokens (JWT) for secure authentication.

## Configuration

Before running the server, make sure to set up your environment variables in a .env file at the root of the project. Here's an example .env file:

```
PORT=3000
DB_USER=your_database_username
DB_PASS=your_database_password
JWT_SECRET=yoursecretkey
```

Replace `your_database_username`, `your_database_password`, and `yoursecretkey` with your preferred configurations.