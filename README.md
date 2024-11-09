# Payment_Slips
This project is a Python and R implementation designed to facilitate the weekly payments for workers at Highridge Construction Company.

# Project Structure
Highridge Construction Company Payment Slips.ipynb - Python code for generating worker payment slips with unique worker's name, salaries, genders, and employee levels.
Highridge Construction Company Payment Slips.R - R code that performs the same functionality as the Python code.
README.md - Instructions on how to run the project in both Python and R.

## Requirements
Python 3.x and 
R (version 3.5 or higher).
Random module was called in python for data manipulation while dplyr package was called on R.

# Installation
Download the Project Folder:
Download and unzip the folder containing the Highridge Construction Company Payment Slips.ipynb and Highridge Construction Company Payment Slips.R.
Open Jupiter Notebook for Python and RStudio for R then navigate to the project folder.

## Usage
Run the Python Script in Jupyter Notebook  (or a Python-compatible environment):
Navigate to the folder where Highridge Construction Company Payment Slips.ipynb is located.
Run the Script.
The script will generate payment slips for each of the 450 workers. Each payment slip includes the worker's name, gender, salary, and assigned employee level, based on specified conditions.

Running the R Script in RStudio (or an R-compatible environment):
Navigate to the folder where Highridge Construction Company Payment Slips.R is located.
Run the Script:
The R script will similarly generate and display payment slips for 450 workers, providing details such as worker's name, gender, salary, and employee level based on the specified conditions.

### Employee Level Assignment Criteria
The employee level is determined by specific conditions:
Level "A1": Assigned if a worker's salary is between $10,000 and $20,000.
Level "A5-F": Assigned if a worker's salary is between $7,500 and $30,000 and the worker is female.
Default Level "NA": Assigned to all workers who do not meet the above criteria.

# Error Handling
Both the Python and R scripts include exception handling to manage potential errors (e.g., invalid data types, undefined variables).

# Additional Notes
This project is a prototype and generates random data each time it is run, so worker's name, salaries, and levels may vary across executions.

This README file provides instructions for both Python and R, ensuring easy access for users of either language.

