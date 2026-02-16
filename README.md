# colors-lab

## Description
The COLORS web application is a website that allows users to manage their favorite colors. Users are able to add any color they want and search for them whenever they want. This repo contains everything needed for the website to work which includes: the HTML files for both login and the application itself, CSS styling for the website, JS files for basic website functionality and password hashing, and multiple APIs for retrieving data from the database.

### Technologies Used
This website uses the LAMP stack, which is a very popular software stack. LAMP stands for Linux, Apache, MySQL, PHP. Linux is the operating system used for the server where the website is hosted on. Apache is a web server that is the second layer of the LAMP stack. It stores the files for the website and handles requests from a user's browser. MySQL is the database system that stores a user's data which includes their username, password, and colors.  PHP is a scripting language that is used to create the API to allow users to request data like their colors to the web server.

## Setup
1) Setup a web server using a hosting server like AWS or DigitalOcean
2) Using Powershell or Terminal, login to your web server using your provided IP address and password.
3) Navigate to the root directory (cd ../)
4) Navigate to the default Apache folder for website files (cd var/www/html)
5) Add color.html and index.html to the folder
6) Create new directories called: api, css, js, img
7) Add the files from the repo to each folder
8) Connect to MySQL using the following command: "mysql -u root -p"
9) Copy the contents of database.sql and paste to the command line, then hit enter.
10) To add users, run "USE COP4331", then run "insert into Users (FirstName,LastName,Login,Password) VALUES ('replace with first name', 'replace with last name', 'replace with username, 'replace with password;);" (Note: Add your info to wherever it says "replace")
11) Update index.js with your domain name or website's IP address
12) Run the server if it isn't already running

## How to Run/Access Website
1) Start the Apache server
2) On your browser of choice, type your server's IP address to the address bar to access the website (if your have a domain connected then type in your domain name instead)
3) Login using your username and password
4) To add colors, click the Add Color button to add a color
5) To search for a color, type in a color's name to the search box
6) To logout, click the logout button

## Assumptions/Limitations/AI Usage
### Assumptions
- Assumes you know how to setup a web server using a provider like DigitalOcean
- Assumes you know basic Linux terminal navigation
- Assumes you know some JavaScript to edit the domain name

### Limitations
- Very limited website functionality
- Users cannot create an account from the website
- The website does not save a session key
- Users cannot reset their username or password

### AI Usages
No form of AI was used during the creation of this repository or web application.