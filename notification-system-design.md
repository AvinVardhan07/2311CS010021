Notification System Design

This project is developed using Node.js and Express.js. The main objective of the application is to fetch notifications from the provided API and generate a priority inbox based on notification type and time.

The project is divided into different modules such as routes, controllers, services and repositories. Each module has its own responsibility, which keeps the code clean and easy to understand.

The notification API is called using Axios. Authentication is handled using an access token, and a logging middleware is used to record API logs.

The Priority Inbox endpoint calculates a priority score for every notification and returns them in descending order so that the most important notifications appear first.

The application also handles common errors such as invalid authorization tokens, API failures and unexpected server errors.

Overall, the project follows a simple and modular structure, making it easy to maintain and extend in the future.
