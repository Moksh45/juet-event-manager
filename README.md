# College Event Manager

Welcome to the **College Event Manager** GitHub repository! This project is a web application designed to streamline the organization and management of college events. It provides a user-friendly interface for students and faculty to create, manage, and participate in various college events.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Event Creation**: Easily create events with detailed descriptions, dates, and locations.
- **User Registration**: Allow students and faculty to register for events.
- **Event Management**: Manage event details, track registrations, and send notifications.
- **Calendar View**: View all upcoming events in a calendar format.
- **Search and Filter**: Quickly find events using search and filter options.
- **Responsive Design**: Mobile-friendly design to access the application from any device.

## Tech Stack

- **Frontend**: React.js, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Hosting**: Vercel
- **Version Control**: Git, GitHub

## Installation

To get a local copy up and running follow these simple steps.

### Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Setup

1. Clone the repository
   ```sh
   git clone https://github.com/Moksh45/juet-event-manager.git
   ```
2. Navigate to the project directory
   ```sh
   cd college-event-manager
   ```
3. Install dependencies
   ```sh
   npm install
   ```

### Configuration

1. Create a `.env` file in the root directory and add the following environment variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=5000
   MAIL="your-mail"
   PASS=""password
   ```

### Running the Application

1. Start the development server
   ```sh
   npm start
   ```
2. Open your browser and navigate to `http://localhost:5000`

## Usage

1. **Register/Login**: Users can register or log in using their email and password.
2. **Create Events**: Authorized users can create new events by filling out the event form.
3. **View Events**: Users can view all events in a list or calendar view.
4. **Register for Events**: Users can register for events they are interested in.
5. **Manage Events**: Event organizers can edit event details, view participant lists, and send notifications.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Moksh Gupta - [mokshgupta567@gmail.com](mailto:mokshgupta567@gmail.com)

Project Link: [https://github.com/moksh45/college-event-manager](https://github.com/Moksh45/juet-event-manager)
