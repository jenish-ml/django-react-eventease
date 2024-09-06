# Event Management App

This is a simple React-based Event Management App that allows users to create, view, and delete events. The app communicates with a backend API using Axios to perform CRUD operations.

## Features

- **View Events:** Displays a list of events fetched from the backend API.
- **Create Events:** Allows users to create new events by filling out a form with title, date, time, location, and description.
- **Delete Events:** Allows users to delete events from the list.

## Tech Stack

- **Frontend:** React, Axios
- **Backend:** Django (or any API providing CRUD operations for events)
- **Styling:** Basic CSS (customizable as needed)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/event-management-app.git
   cd event-management-app
2. **Install dependencies:**

    ```bash
    npm install

3. **Configure the Backend:**

    ```bash
    python manage.py runserver

4. **Start the React app:**

   ```bash
   npm start

## Usage

1. **Viewing Events:**

    On loading the app, a list of events will be fetched from the backend and displayed.
2. **Creating an Event:**

    Fill out the event form with a title, date, time, location, and description.
    Click the "Create Event" button to add the event to the list.
   
4. **Deleting an Event:**

    Click the "Delete" button next to an event to remove it from the list.

## API Endpoints

  - **GET /api/events/ - Fetch all events**
  - **POST /api/events/ - Create a new event**
  - **DELETE /api/events/**
  - **/ - Delete an event by ID**
## License
This project is licensed under the MIT License - see the LICENSE file for details.
