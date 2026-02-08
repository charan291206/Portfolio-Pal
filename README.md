# Portfolio-Pal

Portfolio-Pal is a web application designed for managing student portfolios. It features a login system for admins and students, allowing users to view and potentially manage portfolio projects. The app uses a simple backend to handle authentication and data serving, with data stored in JSON format.

## Live Demo
View the active deployment on Render: [https://ds1-54t7.onrender.com/login](https://ds1-54t7.onrender.com/login). Use sample credentials:
- **Admin:** Username: admin, Password: admin123
- **Student:** Username: student1, Password: student123

## Features
- User authentication with separate roles for admins and students.
- Portfolio management, including viewing projects from `projects-data.json`.
- Server-side rendering with templates for dynamic content.
- Static assets serving for styles, scripts, and images.

## Technologies Used
- **Backend**: Node.js with Express (inferred from `server.js` and `package.json`).
- **Frontend**: HTML, CSS, JavaScript.
- **Templating**: Likely EJS or similar (based on `views/` directory).
- **Data**: JSON file (`projects-data.json`) for storing project information.
- **Dependencies**: Managed via npm (from `package.json`).

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/charan291206/Portfolio-Pal.git
   ```
2. Navigate to the project directory:
   ```
   cd Portfolio-Pal
   ```
3. Install dependencies:
   ```
   npm install
   ```

## Usage
### Local Development
1. Start the server:
   ```
   node server.js
   ```
   or
   ```
   npm start
   ```
2. Open your browser and visit `http://localhost:3000` (or the configured port).
3. Access the login page and use credentials to explore the app.

### Deployment
- Deployed on Render.com for static and dynamic hosting. 

## Data Overview
- **projects-data.json**: Contains data for student projects, such as titles, descriptions, and other details.
