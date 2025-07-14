# E-Commerce_Platform
A React-Router based E-Commerce Platform

 Website Link: https://buyzaar.ccbp.tech

 Core Technical Features – E-Commerce Web Application
# 🔐 Authentication & Authorization

  Implements secure login/logout functionality using JWT (JSON Web Tokens).

  Tokens are stored in browser cookies for session persistence.

  Protected routes are enforced using conditional rendering and React Router guards.

  Unauthorized access is blocked, and users are redirected based on auth state (e.g., logged-in users can’t access login page).

# 🌐 React Router for SPA Navigation

  Utilizes React Router to create a single-page application (SPA) experience.

  Route-level protection is handled using Redirect and history.push() methods.

  Pages like Products, Cart, and Dashboard are accessible only to authenticated users.

# 📡 Backend Communication & Data Handling

  Performs API calls for login, registration, and product retrieval using fetch or axios.

  GET requests handle credential input during login, and POST requests validate access.

  User data, product info, and cart details are persisted in a backend database.

  Backend supports authentication checks and user management via secure API endpoints.
