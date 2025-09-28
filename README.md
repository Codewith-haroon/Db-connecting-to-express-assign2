# Backend for Event Management App

Imagine you're building the backend for a simple **event management application**. Your task is to independently set up an **Express.js** server and connect it to a **MongoDB** database using **Mongoose**.

This assignment will challenge you to apply everything you’ve learned so far—writing the full connection logic, managing configuration with environment variables, and confirming whether the connection is successful—all on your own.

## Instructions

### 1. Initialize the Project

- Use the provided Express boilerplate as a starting point.
- Open your terminal and install dependencies:

  ```bash
  npm install
  ```

### 2. Set Up Environment Configuration

- Create a `.env` file at the root of your project.

- Inside the `.env` file, store your MongoDB connection string like this:

  ```
  MONGO_URI=mongodb://localhost:27017/eventsDB
  ```

- This ensures that sensitive configuration values are kept separate from your source code.

### 3. Connect Express to MongoDB

- Open `index.js` in the root of your project.
- If the Express app is not already running, set it up.
- Write the connection logic using Mongoose to:

  - Load the connection string from the `.env` file
  - Attempt to connect to the `eventsDB` database
  - Log the outcome clearly:

    - Success:
      `Connected to MongoDB`
    - Failure:
      `Error connecting to MongoDB: <error details>`

### 4. Test Your Backend

- Start the server with `node index.js` or `npm start`.
- Look for the success or error message in the terminal to confirm your connection logic works correctly.

## How to Fork and Set Up Your Repository

### 1. Fork the StackBlitz Repository

- A StackBlitz project link will be shared for this assignment.
- Click **Fork** to create your own editable version.

### 2. Push to Your GitHub Repository

You can push your work either manually or directly from StackBlitz.

#### Option A: Manual Push

1. Download the code from StackBlitz.
2. Use your terminal to push it to GitHub:

   ```bash
   git init
   git remote add origin <your_github_repo_url>
   git add .
   git commit -m "Connected Express app to MongoDB"
   git push -u origin main
   ```

#### Option B: Direct Push via StackBlitz

- Use StackBlitz’s **Push to GitHub** feature to publish your code directly.

### 3. Submit Your Work

- After pushing your code to GitHub:

  1. Copy your repository URL.
  2. Submit it on the assignment submission portal.

#### Format:

`https://github.com/<your_username>/<repository_name>`

### Example Submission

If your GitHub username is `zaraTech` and your repository name is `event-backend`, submit:
`https://github.com/zaraTech/event-backend`
