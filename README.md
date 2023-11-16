# LeadCraft Pro

Welcome to the Customer Relations Manager (CRM) project built with Django and PostgreSQL. This CRM system is designed to streamline customer interactions, allowing administrators to manage leads, sales agents to track and update leads, and overall facilitating effective customer relationship management.

## Features

### 1. Lead Management

- **Create:** Administrators can add new leads to the system.
- **Read:** View detailed information about leads.
- **Update:** Modify lead details as needed.
- **Delete:** Remove leads that are no longer relevant.

### 2. Sales Agent Interaction

- **View Leads:** Sales agents can access a list of leads for effective communication.
- **Mark as Converted:** Sales agents can mark leads as converted or not, updating the status of potential deals.

### 3. Administrator Control

- **Manage Sales Agents:** Administrators have the ability to add or remove sales agents, ensuring efficient team management.

## Technologies Used

- **Django:** The high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **PostgreSQL:** A powerful, open-source relational database system for storing and retrieving data.

## Getting Started

To run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/samtechy26/LeadCraft-Pro.git`
2. Navigate to the project directory: `cd djcrm`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up the PostgreSQL database and update the database configuration in the `settings.py` file.
5. Apply migrations: `python manage.py migrate`
6. Create a superuser account: `python manage.py createsuperuser`
7. Run the development server: `python manage.py runserver`

Access the application at `http://localhost:8000` and the admin panel at `http://localhost:8000/admin` using the superuser credentials.

## Usage

1. Log in as an administrator to manage leads and sales agents.
2. Sales agents can log in to view leads and update their status.

## Contributions

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
