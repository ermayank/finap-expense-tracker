# FinAp Expense Tracker

Welcome to FinAp Expense Tracker! This application is designed to help you manage your expenses efficiently. Whether you're a freelancer, a small business owner, or just trying to keep track of personal spending, FinAp has got you covered.

## Features

### 1. Expense Tracking
- Easily record your expenses with detailed information such as date, category, amount, and description.
- View and manage your expenses conveniently in a user-friendly interface.

### 2. Income Tracking
- Keep track of your income sources to maintain a comprehensive overview of your financial transactions.
- Record income details including date, source, amount, and any additional notes.

### 3. Categories
- Organize your expenses and income by assigning them to different categories.
- Customize categories to suit your specific needs, ensuring accurate tracking and reporting.

### 4. Reports and Insights
- Gain valuable insights into your spending habits and financial trends with visual reports.
- Analyze your expenses and income over time to make informed financial decisions.

### 5. Budgeting
- Set budgets for different expense categories to help you stay within your financial limits.
- Receive notifications when you're approaching or exceeding your budget to avoid overspending.

### 6. Multi-platform Access
- Access your financial data from anywhere using our web and mobile applications.
- Sync data seamlessly across devices to ensure you always have the latest information at your fingertips.

## Technologies Used

FinAp Expense Tracker is built using a variety of modern technologies to provide a seamless and reliable user experience:

- **Frontend:**
  - React.js: A popular JavaScript library for building user interfaces.
  - Redux: Used for state management to ensure a consistent application state.
  - Material-UI: A React UI framework for implementing Google's Material Design.
  - Chart.js: Provides interactive charts for visualizing financial data.

- **Backend:**
  - Node.js: A JavaScript runtime for building scalable server-side applications.
  - Express.js: A minimal and flexible Node.js web application framework.
  - MongoDB: A NoSQL database for storing and managing financial data.
  - Mongoose: An ODM (Object Data Modeling) library for MongoDB, used for easier interaction with the database.

- **Authentication and Security:**
  - JSON Web Tokens (JWT): Used for secure authentication and authorization.
  - bcrypt.js: A library for hashing passwords to enhance security.
  - Passport.js: A middleware for authentication in Node.js applications.

- **Deployment and Hosting:**
  - Heroku: Used for deploying and hosting the web application.
  - MongoDB Atlas: A cloud database service for storing MongoDB databases.

## Getting Started

To get started with FinAp Expense Tracker, follow these steps:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/ermayank/finap-expense-tracker.git
```

2. Navigate to the project directory:

```bash
cd finap-expense-tracker
```

3. Install dependencies for both the frontend and backend:

```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

4. Set up environment variables:
- Create a .env file in the server directory.
- Define the following environment variables in the .env file:
    - JWT_SECRET: Secret key for JWT token generation.
    - MONGODB_URI: URI for connecting to your MongoDB database.

5. Start the development servers:
```bash
cd ../server
npm start

cd ../client
npm start
```

## Contributing
We welcome contributions from the community to improve FinAp Expense Tracker. If you have any ideas, suggestions, or bug fixes, please feel free to open an issue or submit a pull request on GitHub.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Special thanks to all the contributors who helped make this project possible.
Inspired by the need for a simple yet effective expense tracking solution.