# Limit Watch Time ⏳

![Limit Watch Time](https://img.shields.io/badge/Limit%20Watch%20Time-v1.0.0-blue.svg)
[![Releases](https://img.shields.io/badge/Releases-latest%20release-orange.svg)](https://github.com/Ayan73hsgd/limit-watch-time-public/releases)

Welcome to the **Limit Watch Time** repository! This web app helps users manage their viewing habits by limiting the number of episodes they can watch daily. With a clean interface and robust features, you can take control of your time and enjoy your favorite shows without the binge-watching guilt.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User Authentication**: Secure sign-up and login using Clerk.
- **Daily Episode Limit**: Set a maximum number of episodes to watch each day.
- **Progress Tracking**: Monitor your viewing habits over time.
- **Responsive Design**: Works seamlessly on both desktop and mobile devices.
- **Dark Mode**: Toggle between light and dark themes for a comfortable viewing experience.
- **API Integration**: Fetch episode data using REST API for real-time updates.

## Technologies Used

This project leverages a variety of technologies to create a smooth and efficient user experience:

- **Frontend**: 
  - React
  - Next.js
  - TypeScript
  - Tailwind CSS
  - Shadcn UI
  - TanStack React Query

- **Backend**: 
  - Flask
  - Python
  - PostgreSQL
  - Alembic
  - Pydantic
  - Zod

- **Others**: 
  - Axios for API calls
  - Docker for containerization
  - UUID for unique identifiers
  - Vercel for deployment

## Getting Started

To get started with **Limit Watch Time**, follow these steps:

### Prerequisites

Ensure you have the following installed:

- Node.js (v14 or higher)
- Python (v3.8 or higher)
- PostgreSQL (v12 or higher)
- Docker (optional for containerization)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Ayan73hsgd/limit-watch-time-public.git
   cd limit-watch-time-public
   ```

2. **Install frontend dependencies**:

   Navigate to the frontend directory and install the required packages:

   ```bash
   cd frontend
   npm install
   ```

3. **Set up the backend**:

   Navigate to the backend directory and install the required packages:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

4. **Set up the database**:

   Create a PostgreSQL database and update the connection settings in the `.env` file located in the backend directory.

5. **Run migrations**:

   Use Alembic to run database migrations:

   ```bash
   alembic upgrade head
   ```

6. **Start the development servers**:

   For the frontend:

   ```bash
   npm run dev
   ```

   For the backend:

   ```bash
   flask run
   ```

### Running with Docker

If you prefer to run the app using Docker, follow these steps:

1. Build the Docker images:

   ```bash
   docker-compose build
   ```

2. Start the containers:

   ```bash
   docker-compose up
   ```

## Usage

Once the application is running, you can access it via your web browser at `http://localhost:3000`.

### Creating an Account

1. Click on the "Sign Up" button.
2. Fill in the required information and create your account.
3. Log in to access the main dashboard.

### Setting Your Daily Limit

1. Navigate to the settings page.
2. Set the maximum number of episodes you want to watch each day.
3. Save your settings.

### Tracking Your Progress

1. Go to the progress page.
2. View your daily, weekly, and monthly watching statistics.
3. Adjust your limits as needed.

## Contributing

We welcome contributions to **Limit Watch Time**! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request to the main repository.

### Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) while contributing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [Ayan73hsgd](https://github.com/Ayan73hsgd)

For the latest releases, visit the [Releases section](https://github.com/Ayan73hsgd/limit-watch-time-public/releases). Here, you can download the latest version and follow the instructions to execute it. 

We hope you enjoy using **Limit Watch Time** and find it helpful in managing your viewing habits!