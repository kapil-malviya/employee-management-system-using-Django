# Employee Management 

This is a simple Django project for Employee Management, which demonstrates the basic CRUD (Create, Read, Update, Delete) operations using Django's function-based 
views. This project allows you to perform CRUD operations in Enmployee Management Project.

## Installation

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/kapil-malviya/employee-management-system-using-Django
   ```

2. Navigate to the project directory:

   ```
   cd employee-management-system-using-Django
   ```

3. Start the development server:

   ```
   python3 manage.py runserver
   ```

The project should now be running locally at `http://localhost:8000/`.

## Usage

### Django Admin

You can access the Django admin panel at `http://localhost:8000/admin/`. Use the superuser credentials ```python3 manage.py createsuperuser```. 
In the admin panel, you can manage employee records.

## Endpoints

This project provides the following endpoints for CRUD operations :

#### 1. List all employees (GET)

- Endpoint : `http://localhost:8000/all_emp/`

Send a GET request to the above URL to retrieve a list of all employees in the system.

#### 2. Create a new employee (POST)

- Endpoint : `http://localhost:8000/add_emp/`

Send a POST request to this URL with the employee data in the request body to create a new employee.

#### 3. Delete an existing employee

- Endpoint : `http://localhost:8000/remove_emp/`
- Endpoint : `http://localhost:8000/remove_emp/<employee_id>`

Replace `<employee_id>` with the actual ID of the employee you want to delete and Send a request to this URL with the employee id in the request body to remove an existing employee.

#### 4. Filter employee Details

- Endpoint : `http://localhost:8000/filter_emp/`

Send a request to this URL to filter details of an existing employee.


## Technologies Used

- Django : The web framework used for the backend.
- SQLite : The default database used for this project (for simplicity).
- Bootstrap : A popular front-end framework for creating responsive and visually appealing web interfaces.
- Python : The programming language used for the project's backend logic.

## Contributing

If you'd like to contribute to this project or report issues, please feel free to create a pull request.
Feel free to customize and extend this project for your specific needs.
