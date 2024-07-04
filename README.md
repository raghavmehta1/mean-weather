
# MEAN Weather App

This is a weather application built using the MEAN stack (MongoDB, Express.js, Angular, Node.js). It allows users to search for and display weather information for different locations.

## Features

- **Search Weather**: Users can search for weather information by entering a location.
- **Display Weather**: Current weather conditions, temperature, and other relevant data are displayed.
- **Responsive Design**: The application is designed to work well on both desktop and mobile devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** and **npm** installed.
- **MongoDB** installed and running.

## Getting Started

Follow these instructions to set up and run the project locally.

### Clone the Repository

```bash
git clone https://github.com/raghavmehta1/mean-weather.git
cd mean-weather
```

### Install Dependencies

#### Backend

Navigate to the `server` directory and install dependencies:

```bash
cd server
npm install
```

#### Frontend

Navigate to the `client` directory and install dependencies:

```bash
cd ../client
npm install
```

### API Keys Setup

1. Sign up for a weather API key from [WeatherStack](https://weatherstack.com/documentation) or any other weather API provider.
2. Create a `.env` file in the `server` directory and add your API key:

   ```env
   WEATHER_API_KEY=your_api_key_here
   ```

### Running the Application

#### Backend

1. Start the MongoDB server.
2. Run the backend server:

   ```bash
   cd server
   npm start
   ```

   The backend server will start on `http://localhost:3000`.

#### Frontend

1. Run the Angular development server:

   ```bash
   cd client
   ng serve
   ```

   The frontend server will start on `http://localhost:4200`.

### Access the Application

Open your web browser and navigate to `http://localhost:4200/` to use the application.

## Project Structure

- `client/`: Contains the Angular frontend code.
- `server/`: Contains the Node.js backend code.
- `models/`: Mongoose schemas for MongoDB.
- `routes/`: Express routes for handling API requests.

## Contributing

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Create a pull request.



---

