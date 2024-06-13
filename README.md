# Documentation Sharing Platform

## Project Description
This project allows developers to document algorithms, real problems, commands, and discoveries, and share these documents with others with view or edit access. It demonstrates skills in full-stack development, user authentication, and access control.

## Tech Stack
- **Frontend**: Vue.js, hosted on Netlify or GitHub Pages.
- **Backend**: Python with Flask, hosted on Heroku.
- **Database**: SQLite for local development, PostgreSQL on Heroku (free tier).
- **Authentication**: Firebase Authentication.

## Development Steps

### 1. Develop Locally
- **Frontend**: Create a Vue.js application.
  - Use Vue CLI to bootstrap your project.
  - Implement a rich text or Markdown editor for creating and editing documents.
  - Create UI components for document sharing and permission settings.
- **Backend**: Create a Flask server.
  - Set up routes for user registration, login, document CRUD operations, and sharing.
  - Use SQLite for local development.

### 2. Use SQLite
- For local development, use SQLite to simplify setup.
- Define a simple schema for users, documents, and permissions.

### 3. Deploy
- **Frontend**: Deploy the Vue.js application to Netlify or GitHub Pages.
- **Backend**: Deploy the Flask server to Heroku.
  - Switch to PostgreSQL for the production database.
  - Ensure environment variables for database connection and Firebase credentials are set in Heroku.

### 4. Authentication
- Integrate Firebase Authentication for user management.
  - Set up Firebase project and enable email/password authentication.
  - Use Firebase SDK in your Vue.js application for handling authentication.

### Notes
- Focus on demonstrating core features such as document creation, editing, sharing, and permission management.
- Ensure proper security practices for user data and document access.
