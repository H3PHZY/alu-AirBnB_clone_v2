# AirBnB Clone - MySQL

## Background Context
This project is part of the AirBnB clone series, focusing on integrating MySQL for database management. 
Environment variables play a crucial role in configuring the application for various environments (e.g., development, testing, and production). Below is an overview of the environment variables and their purposes:

### Environment Variables:
- **`HBNB_ENV`**: Specifies the running environment. Options: `dev`, `test`, or `production` (upcoming).
- **`HBNB_MYSQL_USER`**: MySQL username.
- **`HBNB_MYSQL_PWD`**: MySQL password.
- **`HBNB_MYSQL_HOST`**: MySQL hostname.
- **`HBNB_MYSQL_DB`**: MySQL database name.
- **`HBNB_TYPE_STORAGE`**: Specifies the storage type. Options: `file` (FileStorage) or `db` (DBStorage).

---

## Learning Objectives
By the end of this project, you should be able to:

### General:
1. **Unit Testing**:
   - Understand unit testing and implement it in large projects to ensure code reliability.

2. **Understanding `*args` and `**kwargs`:**
   - Learn what `*args` is and how to use it for passing variable-length positional arguments.
   - Understand what `**kwargs` is and how to use it for named (keyword) arguments in functions.

3. **Named Arguments in Functions:**
   - Learn how to handle named arguments effectively for function calls.

4. **MySQL Database Management:**
   - Create a MySQL database.
   - Create a MySQL user and grant appropriate privileges.

5. **Object-Relational Mapping (ORM):**
   - Understand what ORM is and how to map a Python class to a MySQL table.

6. **Dual Storage Engines:**
   - Learn to handle two different storage engines (`FileStorage` and `DBStorage`) within the same codebase.

7. **Environment Variables:**
   - Utilize environment variables to manage configurations and separate development, testing, and production setups.

---

## Features
- Integration with MySQL for persistent data storage.
- Dual storage engine support for flexibility in development and production.
- Unit tests to ensure high code quality.
- Configuration management via environment variables.

---

## Installation

### Prerequisites:
- Python 3.x
- MySQL

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/AirBnB_clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AirBnB_clone
   ```
3. Set up a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set environment variables:
   ```bash
   export HBNB_ENV=dev
   export HBNB_MYSQL_USER=your_username
   export HBNB_MYSQL_PWD=your_password
   export HBNB_MYSQL_HOST=localhost
   export HBNB_MYSQL_DB=airbnb_db
   export HBNB_TYPE_STORAGE=db
   ```

6. Initialize the database:
   ```bash
   python3 models/engine/db_storage.py
   ```

---

## Usage
Run the application with:
```bash
python3 console.py
```

Available commands:
- `create` - Create a new object.
- `show` - Display an object.
- `destroy` - Delete an object.
- `all` - Show all objects.
- `update` - Update an object.

---

## Testing
To run tests, use the following command:
```bash
python3 -m unittest discover tests
```

---

## Authors
- Hephzibah Ofomi - H3PHZY (https://github.com/H3PHZY)
