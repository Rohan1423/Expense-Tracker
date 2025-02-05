# Expense Tracker

## Description
A web application for tracking expenses, allowing users to add, edit, and delete transactions.

## Technologies Used
- React
- Node.js
- Express
- MongoDB
- Ant Design

##Live Deployment
-The application is deployed live on Render. You can access it at the following URL: [https://expense-tracker-y6l7.onrender.com).


## Installation Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the client directory:
   ```bash
   cd client
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Navigate back to the root directory:
   ```bash
   cd ..
   ```
5. Install server dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the server:
   ```bash
   npm start
   ```
2. Start the client:
   ```bash
   cd client
   npm start
   ```

## API Endpoints
- `POST /api/v1/transections/get-transection`: Retrieve transactions based on filters.
- `POST /api/v1/transections/add-transection`: Add a new transaction.
- `POST /api/v1/transections/edit-transection`: Edit an existing transaction.
- `POST /api/v1/transections/delete-transection`: Delete a transaction.

## Deployment
To deploy the application on Render:
1. Create a Render account at [Render.com](https://render.com).
2. Create a new web service and connect to your GitHub repository.
3. Configure the service with the appropriate build and start commands.
4. Add any necessary environment variables.
5. Click "Create Web Service" to deploy.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
