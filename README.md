# Instagram-Login-Phishing-Page
This project is a simple implementation of an Instagram-like login form that connects to a MongoDB database. It uses Node.js, Express, and Mongoose for the backend, and basic HTML and CSS for the frontend.

## Project Structure

```
Instagram-Login-Phishing-Page/
├── public/
│   ├── icons/
│   │   ├── InstagramIcon.png
│   │   ├── google.png
│   │   └── microsoft.png
│   └── styles/
│       └── style.css
├── index.html
└── server.js
```

- **public/**: Contains static assets like images and stylesheets.
- **index.html**: The main HTML file for the login form.
- **server.js**: The Node.js server file that handles form submissions and connects to MongoDB.

## Prerequisites

- Node.js and npm installed on your machine.
- MongoDB installed and running on your local machine.

## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/AbdullahMaqbool22/Instagram-Login-Phishing-Page.git
    cd iInstagram-Login-Phishing-Page
    ```

2. **Install dependencies:**

    ```sh
    npm install
    ```

3. **Ensure MongoDB is running:**

    Open a terminal and start MongoDB with the following command:

    ```sh
    mongod
    ```

4. **Start the server:**

    ```sh
    node server.js
    ```

    The server will start on `http://localhost:3000`.

5. **Open the form in your browser:**

    Navigate to `http://localhost:3000` to access the login form.

## Usage

1. Open your browser and go to `http://localhost:3000`.
2. Fill in the username and password fields.
3. Click the "Log In" button.
4. The form data will be sent to the server and saved in the MongoDB database.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Icons8](https://icons8.com/) for icons

### Additional Notes

- **Validation and Security:** This example does not include input validation or password hashing. For a production environment, you should add validation and securely hash passwords before storing them in the database.
- **Environment Variables:** For deployment, use environment variables to store sensitive information like database connection strings. You can use packages like `dotenv` to manage environment variables.

### Running the Complete Application

1. **Initialize the Project and Install Dependencies:**

    ```sh
    npm init -y
    npm install express mongoose body-parser
    ```

2. **Start MongoDB:**

    ```sh
    mongod
    ```

3. **Start the Server:**

    ```sh
    node server.js
    ```

4. **Open the Form in Your Browser:**

    Navigate to `http://localhost:3000` to access the form.
