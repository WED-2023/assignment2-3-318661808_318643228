# 🍲 Recipes Full Stack Project

**Client:** Vue.js, Bootstrap-Vue  
**Server:** Node.js, Express.js, MySQL  
**API Documentation:** Swagger

This project is a full-stack recipe web application that allows users to search, add, and manage recipes. The server-side is built using Node.js and Express, with a MySQL database for storing recipes and user data. The client-side is developed with Vue.js and Bootstrap-Vue for a modern and responsive UI. Users can register, log in, and manage their favorite and personal recipes.

## 🌟 Features

- **Search Recipes:** Search recipes by name, cuisine, diet, or intolerances. Sort results by preparation time or rating.
- **Personal Recipes:** Add and view your own personal recipes.
- **Favorites:** Mark recipes as favorites and view your list of favorites.
- **User Authentication:** Secure user registration, login, and session management.
- **API Documentation:** Well-documented API using Swagger.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (Download Node.js)
- [NPM](https://www.npmjs.com/) (Included with Node.js)

### Server Setup

1. Clone the repository from GitHub:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. Install necessary libraries:

   ```bash
   npm install express
   npm install nodemon
   ```

3. Run the server:

   ```bash
   nodemon index.js
   ```

### Client Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Compiles and hot-reloads for development:

   ```bash
   npm run serve
   ```

3. Compiles and minifies for production:

   ```bash
   npm run build
   ```

---

## 📄 API Documentation

The API is documented using Swagger (OpenAPI 3.0). You can find the Swagger documentation in the following file:

- **Swagger API Documentation**
- ![Swagger Documentation](readmeimages/swagger.png)

### Key API Endpoints:

- **User Authentication:**
  - `/register`: Register a new user.
  - `/login`: Login and start a session.
  - `/logout`: End the user session.
  
- **Recipes:**
  - `/recipes/search`: Search for recipes by name, cuisine, or other filters.
  - `/recipes/favorites`: Get a list of favorite recipes.
  - `/recipes/personal`: Manage personal recipes.

---

## 🛠️ How the Project Was Developed

### Client-Side Development
- Built the UI using Vue.js and Bootstrap-Vue.
- Created several components like `RecipePreview`, `SearchPage`, `RecipeFullView`, etc.
- Implemented Vue Router for handling different pages and user navigation.
- Used Vuex for managing the state of the application.

### Server-Side Development (Node.js and Express.js)
- Developed the backend using Node.js and Express.js.
- Connected the application to a MySQL database to store user data and recipes.
- Used Postman to test API requests with the database and third-party Spoonacular API.

### Database Integration
- Designed and connected a MySQL database for handling user data and recipes.
- Optimized queries for faster access to personal and favorite recipes.

### Connecting Client to Server
- Axios was used for sending HTTP requests from the client to the server.
- Handled user sessions and cookie-based authentication to ensure secure login.
- Optimized the application to store last searches and personal data on the server-side.


**Developed by:** [Ido Doron, Matan Vaknin]  


