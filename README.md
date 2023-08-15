# Cake Shop Web Application

Welcome to the Cake Shop Web Application project! This project is a web application for a cake shop built using JavaScript, HTML, CSS, Express in Node.js for the server, and MongoDB as the database. The project follows the MVC (Model-View-Controller) architectural pattern to organize its components and functionalities.

![image](https://github.com/chenB-Y/ApplicationProject/assets/129218828/b0b8f284-4dba-4ed8-8624-b55efbc24ac5)


## Features

- **User Authentication:** The application provides a secure login system that checks user credentials stored in MongoDB using hashed passwords. A session cookie is used to maintain user sessions.

- **Client Shop History:** Registered clients can view their order history, providing them with easy access to their past purchases.

- **Manager Dashboard:** The manager has access to an admin dashboard that allows them to perform various tasks:
  - **Website Management:** The manager can change the website's content and layout.
  - **Product Management:** The manager can add, delete, edit, and update products in the MongoDB.
  - **Order Tracking:** The manager can view all orders made by customers.

- **API Integrations:**
  - **Facebook API:** The manager can add new cakes to the website, and they will be automatically posted on the store's Facebook page.
  - **Microsoft Bing Map API:** The application integrates with the Bing Map API to provide location-related features.
  - **Google Chart API:** The application uses the Google Chart API to display data visually.

- **WebSockets:** The application utilizes WebSockets to enable real-time communication between clients and the server, enhancing the user experience.

## Technologies Used

- Frontend: HTML, CSS, JavaScript, AJAX
- Backend: Node.js with Express
- Database: MongoDB
- API Integrations: Facebook API, Microsoft Bing Map API, Google Chart API
- WebSockets for real-time communication

## Getting Started

1. Clone the repository: `git clone https://github.com/chenB-Y/cake-shop-web-app.git`
2. Install dependencies: `npm install`
3. Set up your MongoDB connection string in the configuration files.
4. Obtain API keys for Facebook, Bing Map, and Google Chart, and add them to the configuration files.
5. Start the server: `node app.js`
6. Access the application in your web browser: `http://localhost:3000`

## Folder Structure

- `public/`: Contains static assets like CSS, images, and client-side JavaScript.
- `views/`: Contains the HTML templates for rendering different views.
- `controllers/`: Implements the application logic and interacts with models.
- `models/`: Handles interactions with the MongoDB database.
- `routes/`: Defines the routes and their corresponding controller methods.
- `config/`: Contains configuration files for APIs, database, and other settings.
- `sockets/`: Manages WebSocket functionality.
- `app.js`: Entry point of the application.

## Contributions

Contributions are welcome! If you find any bugs or want to enhance the project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

Enjoy using the Cake Shop Web Application! If you have any questions, feel free to contact us.
