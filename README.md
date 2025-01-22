# AirBnB Clone - MySQL

## Project Overview
This project implements a MySQL storage engine for the AirBnB clone, utilizing environment variables for configuration and supporting multiple storage types.

## Environment Variables
The following environment variables are required for configuration:

| Variable | Description | Possible Values |
|----------|-------------|-----------------|
| `HBNB_ENV` | Running environment | "dev", "test" ("production" coming soon) |
| `HBNB_MYSQL_USER` | MySQL username | Your MySQL username |
| `HBNB_MYSQL_PWD` | MySQL password | Your MySQL password |
| `HBNB_MYSQL_HOST` | MySQL hostname | Your MySQL host |
| `HBNB_MYSQL_DB` | MySQL database name | Your database name |
| `HBNB_TYPE_STORAGE` | Storage type | "file" (FileStorage) or "db" (DBStorage) |

## Learning Objectives

### Unit Testing
- Implementation of unit testing in large projects
- Test case creation and execution
- Test suite organization

### Python Features
- Understanding and usage of `*args`
- Understanding and usage of `**kwargs`
- Handling named arguments in functions

### MySQL
- Database creation and management
- User creation and privilege management
- Table structure and relationships

### ORM (Object-Relational Mapping)
- Fundamentals of ORM
- Mapping Python classes to MySQL tables
- Managing multiple storage engines (File and Database)

### Environment Variables
- Purpose and implementation
- Configuration management
- Storage type switching

## Prerequisites
- Python 3.x
- MySQL installed and configured
- Environment variables properly set

## Project Structure
```
.
├── models/          # Contains all class models
├── tests/           # Unit tests
├── engine/          # Storage engines (File and DB)
└── README.md        # This file
```

## Getting Started
1. Set up your MySQL database
2. Configure environment variables
3. Choose storage type
4. Run the application

## Testing
Run unit tests to ensure everything is working as expected:
```bash
python3 -m unittest discover tests
