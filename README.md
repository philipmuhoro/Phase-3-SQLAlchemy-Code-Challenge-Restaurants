# Phase-3-SQLAlchemy-Code-Challenge-Restaurants
This repository contains the code implementation for a restaurant review domain using SQLAlchemy. The project includes models for `Restaurant`, `Customer`, and `Review`, establishing relationships and implementing various methods for querying and aggregating data.
## Getting Started
Follow the steps below to set up and run the project locally.
### Requirements
- Python version 3
- SQLAlchemy
- SQLite or another supported database
### Installation
1. Clone the repository:
 `git clone https://github.com/Philipmuhoro/
 Phase-3-SQLAlchemy-Code-Challenge-Restaurants`
cd into it.
3. Install dependencies:
`pipenv install` 
`pipenv shell`
4. Apply migrations:
`python manage.py db upgrade`
5. Run the seed script to populate the database with sample data:
`python seeds.py`
### Usage
Explore the provided methods in the code to interact with the restaurant review data. You can use the SQLAlchemy models to query and manipulate the database.
### Project Structure
`models.py`: Contains the SQLAlchemy models for `Restaurant`, `Customer`, and `Review`.
`manage.py`: Script for managing migrations.
`migrations/`: Directory containing migration files.
`seeds.py`: Script for populating the database with sample data.
## Contributing
Contributions are welcome! If you find issues or have improvements, feel free to open a pull request.
## License
This project is licensed under the MIT License - see the LICENSE file for details.

Author 
## Author 
Philip Muhoro,
