
# MyRestaurant-reservation

## Project Overview
This **MyRestaurant-reservation** is a full-stack web application designed for managing restaurant reservations. The system allows different types of users—Administrator, Restaurant Manager, and Guest—to handle reservations, customize restaurant details, and provide feedback.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Implementation Details](#implementation-details)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)

## Features
- **User Roles**:
  - **Administrator**: Can access all areas of the application, including Django Admin for managing users, restaurants, and reservations.
  - **Restaurant Manager**: Can specify the restaurant's menu, manage reservations, and configure the seating schedule.
  - **Guest**: Can view available tables, reserve seats, invite friends to reservations, and rate the service.
  
- **Online Booking**: Guests can view and reserve available tables in real-time.
- **Menu Management**: Restaurant managers can customize their restaurant's menu.
- **Reservation Scheduling**: Managers can configure the seating schedule and manage reservations.
- **Ratings and Reviews**: Guests can rate their dining experience after a reservation.

## Technologies Used
### Frontend:
- **HTML5/CSS3**: For structuring and styling the web pages.
- **Bootstrap**: For responsive design.

### Backend:
- **Python 3.4**: The main programming language used for the project.
- **Django 1.9.2**: Web framework for building the backend logic and handling requests.
- **SQLite 3**: Database for storing restaurant and reservation data.

## Implementation Details
- **Programming Language**: Python 3.4
- **Framework**: Django 1.9.2
- **Database**: SQLite 3

## Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository:**
   
   git clone https://github.com/your-username/MyRestaurant-reservation.git
   cd MyRestaurant-reservation
   

2. **Create a virtual environment:**
   
   python3 -m venv venv
   source venv/bin/activate
   

3. **Install the dependencies:**
   
   pip install -r requirements.txt
   

4. **Run migrations to set up the database:**
   
   python manage.py migrate
   

5. **Create a superuser (admin):**
   
   python manage.py createsuperuser
   

6. **Run the development server:**
   
   python manage.py runserver
   

7. **Access the application:**
   - **Frontend and booking system:** `http://localhost:8000`
   - **Django Admin panel (for Administrator):** `http://localhost:8000/admin`

## Usage
- **Administrator**: Access the Django Admin panel to manage users, restaurants, and reservations.
- **Restaurant Manager**: Login and configure restaurant details, such as the menu and seating schedule.
- **Guest**: Browse the restaurant, make reservations, and rate the service after the dining experience.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and submit a pull request.




