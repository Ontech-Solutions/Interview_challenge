# Developer Interview Challenge

## Overview
This challenge assesses your skills in Python, React, Laravel, MySQL, and Postgres. The tasks are divided into sections, each focusing on a specific technology. You are required to complete any task within plus compulsary task number 4 in 48 hours.

---

## Tasks

### 1. Python Challenge: Data Analysis and API Creation
#### Task:
- Create a Python script that:
  - Fetches data from a public API (e.g., OpenWeatherMap or SpaceX API).
  - Analyzes the data (e.g., identify weather trends or summarize recent launches).
  - Creates a RESTful API using Flask or FastAPI to serve the analyzed data.

#### Requirements:
- Use Python libraries like `requests` for API calls and `pandas` or `json` for data processing.
- API should have endpoints like `/summary` and `/details`.

#### Evaluation Criteria:
- Code structure and readability.
- Efficient use of Python libraries.
- Functionality and correctness of the REST API.

---

### 2. React Challenge: Dynamic Frontend
#### Task:
- Build a React application with:
  - A table displaying data fetched from a given API.
  - A search bar to filter table rows.
  - A modal that pops up when a row is clicked, showing more details about the selected item.

#### Requirements:
- Use React hooks like `useState` and `useEffect`.
- Ensure responsiveness and a clean UI using Material-UI or Tailwind CSS.
- State management should be handled efficiently.

#### Evaluation Criteria:
- Clean and responsive UI.
- Proper state management.
- Correct integration with the API.

---

### 3. Laravel Challenge: CRUD and Middleware
#### Task:
- Create a Laravel application that:
  - Implements CRUD operations for a `Product` model (fields: `name`, `price`, `description`, `quantity`).
  - Adds middleware to log all API requests to a log file.

#### Requirements:
- Use Laravel migrations for database setup.
- Include validation in the controllers.
- Middleware should log method, URL, and request body.

#### Evaluation Criteria:
- Code organization and adherence to Laravel best practices.
- Correct implementation of CRUD and middleware.
- Proper database handling.

---

### 4. Database Challenge: MySQL and Postgres
#### Task:
- Create SQL queries for the following:
  - **MySQL**: Write a query to find the second-highest salary from an `employees` table.
  - **Postgres**: Write a query to find all customers who have placed orders in the last 30 days, joining `customers` and `orders` tables.

#### Requirements:
- Provide the SQL schema for the tables used.
- Ensure queries are optimized and include relevant indexes.

#### Evaluation Criteria:
- Query correctness.
- Query optimization.
- Appropriate use of SQL features.

---

### 5. Full-Stack Integration Challenge
#### Task:
- Integrate the backend API (Python or Laravel) with the React frontend:
  - React app should fetch data from the API created in the Python challenge or Laravel challenge.
  - Display the data in a dashboard with sortable and filterable columns.
  - Include a feature to export table data as a CSV.

#### Requirements:
- Deploy the backend API and React app to a platform like Heroku, Vercel, or AWS.
- Ensure proper API integration and error handling.

#### Evaluation Criteria:
- Correct integration of frontend and backend.
- Deployment success.
- Overall user experience.

---

## Submission Guidelines
1. **Duration**: 48 hours to complete the challenge.
2. **Submission**: Candidates should submit:
   - Code repository (GitHub/Bitbucket).
   - Deployment links (if applicable).
   - Documentation or README detailing their approach, tools used, and how to run the application locally.

---

## Tools and Platforms
- Use **Codility**, **HackerRank**, or **CodeSignal** to host the coding parts of the challenge.
- For project-based tasks, consider using **GitHub Classroom** or simply collect submissions via a shared GitHub repository link.

---
