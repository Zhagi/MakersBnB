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

1. Clone the repository to download the source code to your local machine:

   git clone https://github.com/Zhagi/MakersBnB.git

2. Change into the project directory:
   
   cd MakersBnB

3. Install the project dependencies using Pipenv, which ensures that you have a dedicated virtual environment:
   
   pipenv install
   
4. Activate the Pipenv virtual environment:
   
   pipenv shell

5. Install PostgreSQL, an open-source relational database system:

   brew install postgresql

6. Start the PostgreSQL service using Homebrew services (macOS):

   brew services start postgresql

7. Create the main application database:

   createdb makers_bnb

8. Seed the development database with initial data:

   python seed_dev_database.py

9. Start the Flask application:

   python app.py

10. Open a web browser and navigate to http://localhost:5000/ to view the running application.



## Running the Tests

To ensure the application works as expected, follow these steps to run the tests:

1. Install the project dependencies if you haven't already:
   
   pipenv install

2. Install Playwright, which is used for end-to-end testing:

   playwright install

3. Activate the Pipenv virtual environment:

   pipenv shell

4. Create a separate database for testing purposes:

   createdb makers_bnb_test

5. Seed the test database with initial data:

   psql -d makers_bnb_test -f seeds/makersbnb.sql

6. Run the tests using pytest:

   pipenv run pytest

7. You can check the test results in your terminal to verify everything is working correctly.





