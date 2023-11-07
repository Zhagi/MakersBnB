# MakersBnB

## Introduction
MakersBnB is an AirBnB clone created as part of a team project. Utilising agile work practices, our group designed and integrated a SQL database with Python to develop a fully functional web application within 4 days. Users can register, log in, find accommodation, book stays, or list their own property.


## Tech Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffd54f)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)


## Running the Project

```bash
# Clone the repository to download the source code to your local machine
git clone https://github.com/Zhagi/MakersBnB.git

```

```bash
# Change into the project directory
cd MakersBnB
'''


# Install the project dependencies using Pipenv
pipenv install

# Activate the Pipenv virtual environment
pipenv shell

# Install PostgreSQL, an open-source relational database system
brew install postgresql

# Start the PostgreSQL service using Homebrew services (macOS)
brew services start postgresql

# Create the main application database
createdb makers_bnb

# Seed the development database with initial data
python seed_dev_database.py

# Start the Flask application
python app.py

# Open a web browser and navigate to http://localhost:5000/ to view the running application.



## Running the Tests

To ensure the application works as expected, follow these steps to run the tests:

# Install the project dependencies
pipenv install

# Install the playwright library to run the tests
playwright install

# Activate the Pipenv virtual environment
pipenv shell

# Create the database for test mode
createdb makers_bnb_test

# Add the tables locally to the test database
psql -d makers_bnb_test -f seeds/makersbnb.sql

# Run the tests
pipenv run pytest

# Check the test results in your terminal






