# Personal Finance Tracker

Personal Finance Tracker is a web application built with Next.js that allows users to track their expenses and manage their personal finances. Users can categorize expenses, record income, and visualize their financial data through charts and reports.

## Features

- User authentication
- Expense tracking and categorization
- Income recording
- Financial reports with charts
- MongoDB integration for data storage

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14 or later)
- npm or yarn
- MongoDB instance (local or cloud-based)
- Next.js knowledge

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/personal-finance-tracker.git
   cd personal-finance-tracker
   ```

2. Install the dependencies:

   ```
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the following variables:

   ```
   MONGODB_URI=your_mongodb_connection_string
   NEXTAUTH_SECRET=your_nextauth_secret
   NEXTAUTH_URL=http://localhost:3000
   ```

   Replace `your_mongodb_connection_string` with your actual MongoDB connection string and `your_nextauth_secret` with a secure random string.

## Running the Application

1. Start the development server:

   ```
   npm run dev
   # or
   yarn dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

The project consists of three main pages:

1. Expenses (`/pages/expenses.js`)
2. Income (`/pages/income.js`)
3. Reports (`/pages/reports.js`)

## Models

The application uses the following MongoDB models:

- User
- Expense
- Income
- Category

## API Routes

API routes are located in the `/pages/api` directory and handle CRUD operations for expenses and income.

## Authentication

This project uses NextAuth.js for user authentication. Ensure you have set up the necessary providers in `/pages/api/auth/[...nextauth].js`.

## Contributing

Contributions to the Personal Finance Tracker are welcome. Please feel free to submit a Pull Request.

## License

[Add your chosen license here]

## Contact

If you have any questions or feedback, please contact [Your Name] at [your.email@example.com].
