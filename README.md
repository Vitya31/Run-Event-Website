# Run Event Website

## Overview

The Run Event Website is a vibrant and responsive platform designed for organizing and participating in running events. This project includes features for both administrators and users, providing a comprehensive system for event management and participation.

## Features

### General

- **Colorful and Responsive Design**: The website features a colorful, radiant, and glowing background, with a responsive design suitable for all devices.
- **Countdown Timer**: A countdown timer to the event day.
- **Flip Hover Elements**: Interactive elements with flip hover effects.
- **Horizontal Navigation Bar**: A stylish horizontal navigation bar at the top.
- **Event Gallery**: A gallery showcasing pictures from the event.
- **Organizer Picture**: A section displaying the picture of the event organizer.

### Administrator

- **Default Admin Account**: Create a default admin account using MySQL.
- **Authentication**: Admin login and logout with session management.
  - Ensure all fields are filled before submission using required form attributes or JavaScript. Display a dialog message "Please enter all fields" if any field is blank.
- **Subprogram/Category Management**: Add at least one subprogram or category.
- **View Participants**: View registered participants' details, including their registered categories.
- **Delete Participants**: Delete registered users.
- **Search Participants**: Search for registered users.
- **Quota Management**: Set a quota for each subprogram or category.

### User

- **Member Registration**: Allow users to register as members.
  - Ensure username is unique.
  - Password and confirmed password must match.
  - Validate all fields using required form attributes or JavaScript. Display a dialog message "Please enter all fields" if any field is blank.
- **Authentication**: User login and logout with session management.
  - Ensure all fields are filled before submission using required form attributes or JavaScript. Display a dialog message "Please enter all fields" if any field is blank.
- **Subprogram/Category Registration**: Allow users to register for at least one subprogram or category.
- **User Profile Management**: Display and edit user profile information, with the exception of the username. Allow users to change their registered category.
- **Quota Restriction**: Restrict users from registering for an event if the quota is full.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Installation

### Prerequisites

- XAMPP or any other local server environment
- Git

### Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Vitya31/Run-Event-Website.git
    cd Run-Event-Website
    ```

2. **Set Up the Environment**:
    - Make sure you have XAMPP or another local server environment running.
    - Create a new database in MySQL (e.g., `run_event_db`).

3. **Configure Database**:
    - Update the database configuration in your PHP files to match your local setup.

4. **Run the Project**:
    - Place the project files in the `htdocs` directory of your XAMPP installation.
    - Start Apache and MySQL from the XAMPP control panel.
    - Access the application at `http://localhost/Run-Event-Website`.

## Usage

### Admin

1. **Login**: Access the admin login page and log in with the default credentials.
2. **Manage Subprograms/Categories**: Add new subprograms or categories.
3. **View Participants**: View details of registered participants.
4. **Delete Participants**: Remove participants from the system.
5. **Search Participants**: Find participants using the search function.
6. **Set Quotas**: Define quotas for each subprogram or category.

### User

1. **Register**: Create a new account by filling out the registration form.
2. **Login**: Access the login page and enter your credentials.
3. **Register for Subprograms/Categories**: Choose and register for available subprograms or categories.
4. **Manage Profile**: View and edit your profile information.
5. **Change Category**: Update your registered category, if allowed.
6. **Logout**: Log out from the session.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please contact us at:
- **Name**: Vityasri Ramachendren
- **Email**: Vityasri31@gmail.com

## Acknowledgements

- Thanks to all contributors and supporters of this project.
