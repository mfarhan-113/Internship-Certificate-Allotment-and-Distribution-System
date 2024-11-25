# Source Code Directory (`/src`)

## Purpose
The `/src` directory is the core of our application, containing all source code files that define the application's functionality and logic. This folder is structured to maintain clarity, scalability, and maintainability.

## Structure and Guidelines
Below is a brief overview of the expected folder structure and the type of code to be placed in each section:

### `/routes/`
- Define all API endpoints and route handlers.
- Example files: `userRoutes.js`, `authRoutes.js`.

### `/controllers/`
- Implement business logic for each API endpoint.
- Controllers interact with models and return responses to routes.
- Example files: `userController.js`, `authController.js`.

### `/models/`
- Define database schemas or models.
- Models represent the structure of data used in the application.
- Example files: `userModel.js`, `orderModel.js`.

### `/middleware/`
- Custom middleware functions for handling requests.
- Example: Authentication, validation, or logging middleware.
- Example files: `authMiddleware.js`, `errorHandler.js`.

### `/config/`
- Configuration files and settings, such as database connections or environment variable setups.
- Example files: `dbConfig.js`, `appConfig.js`.

### `/utils/`
- Helper functions and utilities that can be reused across the application.
- Example files: `logger.js`, `emailHelper.js`.

### Main File
- `index.js` or `app.js`: The main entry point for starting the application.

## Best Practices
- Ensure each module or component serves a single purpose.
- Add comments and documentation to improve code readability.

