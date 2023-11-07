# MakersBnB

## Introduction

MakersBnB is an experimental clone of AirBnB, developed as a collaborative effort by our team using agile methodologies. Over the course of four days, we built a web application that allows users to register, log in, find accommodations, and book or offer lodging.

## Tech Stack

- Flask, HTML5, CSS, Python, PostgreSQL 

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



