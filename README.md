# Car Inventory Dashboard

## Description

Car Inventory Dashboard is a web application built with ReactJS, Material-UI, and Data Grid components to manage a collection of cars. It allows users to view, add, update, and delete car records in the inventory through an intuitive dashboard interface.

## Features

- View a list of all cars in the inventory using a Data Grid component.
- Add new cars to the inventory with a user-friendly form using `react-hook-form`.
- Update existing car details directly from the dashboard.
- Delete cars from the inventory with a simple click.

## Technologies Used

- Frontend: ReactJS, Material-UI, Data Grid (`@mui/x-data-grid`), `react-hook-form`
- Backend: Node.js, Express.js (API endpoints not provided in this project)
- Database: MongoDB (or any backend and database of your choice)

## Prerequisites

- Node.js and npm installed on your machine.
- The backend API set up with CRUD operations for the car inventory data.

## Installation

1. Clone the repository.

```bash
git clone https://github.com/HussainAther/CarInventoryDashboard
cd car-inventory-dashboard
npm install
```

2. Set up the backend API (not provided in this project) with the necessary endpoints to handle CRUD operations for the car inventory data.

Update the `src/components/Dashboard.js` file with the correct API endpoints and data handling functions to connect to your backend.

## Usage
Start the development server.

```bash
npm start
```

Access the car inventory dashboard at http://localhost:3000 (or whatever URL is given) in your web browser.

Use the form to add new cars, update existing car details, and delete cars from the inventory directly from the dashboard.

## Contributing
Contributions are welcome! If you find a bug or want to add a new feature, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

