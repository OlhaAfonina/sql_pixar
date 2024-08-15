# Pixar Movies Database Project

## Description
This project is designed to showcase my SQL skills by analyzing a database of Pixar movies. I have used a database that includes 
information about Pixar movies, such as their titles, release dates, budgets, ratings, and more. The project includes various SQL 
queries to analyze this data.

## Installation and Setup

### 1. Clone the Repository
Clone this repository to your local machine:
   git clone https://github.com/OlhaAfonina/sql_pixar.git


2. Create the Database
Log into your SQL environment (e.g., MySQL, PostgreSQL, etc.) and create a new database:

CREATE DATABASE pixar;

3. Import Data
source pixar.sql;

Usage

In this project, you will find examples of various SQL queries, such as:

Retrieving all movies released after 2010:

SELECT 
	moviename, 
	releaseyear 
FROM pixar 
WHERE releaseyear > 2010;

Counting the total number of movies in the database:

SELECT COUNT(*) 
	FROM pixar;

Counting the average budget

SELECT AVG(budget) as average_budget
FROM pixar;


## Database Structure

### Table

- **pixar**: Stores information about Pixar movies.
  - `Moviename` (TEXT): The title of the movie.
  - `Releaseyear` (INT): The year the movie was released.
  - `Budget(million)` (INT): The movie's budget in millions of dollars.
  - `US and canada(million)` (INT): The movie's box office revenue in the US and Canada in millions of dollars.
  - `Other territories(million)` (INT): The movie's box office revenue in other territories in millions of dollars.
  - `Worldwide(million)` (INT): The movie's worldwide box office revenue in millions of dollars.
  - `Rotten Tomatoes` (TEXT): The movie's rating on Rotten Tomatoes.

License

This project is licensed under the MIT License.

Contact

If you have any questions or suggestions, please contact me at afonina.olha@gmail.com.
