# Team Profile Generator

## Description
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated

## Demo
YOUTUBE LINK : https://youtu.be/oICLgIQQEuc
## Installation

To install this application, first, branch the Github Repo and clone the repo to your local machine. Then, you will need to install the node dependencies which can be done by running the npm install command in your terminal/bash shell. Once this has been completed, you are ready to use the
application!

## Usage

To use this application, first, pull up the repo's folder in your terminal/bash shell and run the command node app,js. This will then prompt you with the welcome message and how to use the program. Read the messages and either select from the list what you want to submit, or submit the requested
information. You will be prompted for information such as full names, emails, employee ID numbers, github profiles, office numbers, and university/schools depending on the type of team member you are submitting. When submitting the team member roles, there will only be one team manager to submit.
Once the manager has been added, you will be prompted to add either a new engineer or a new intern. You can add as many engineers or interns as you wish. Once your team has been added in full to the application, you can select the No option for adding new team members. This will complete the
application and export the HTML file to the output folder. You can now view this HTML file or host it on your website to display your team profiles.


## Tests

The repo folder for this application includes four tests that are designed to test the functionality and information validation for the employee class and its three extended inheritance classes for Manager, Engineer, and Intern. These tests can be ran with the Jest node package dependency (which
will be installed when npm install is ran) and will detail how the structure of the class constructor and its extensions pass all validation tests.

