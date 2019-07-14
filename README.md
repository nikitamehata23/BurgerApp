# BurgerApp

# Node - Express - Handlebars - SequelPro - Heroku

### Overview

An app that allows a user to build a custom burger, provide a name for it, and store the information in a database. Using JQuery, I was able to toggle images to show the burger as it is being built, and using Boostrap's modals, I query the database to display a list of ingredients of previously stored submissions.

## The link is below:

* Check out [this demo version of the site](https://still-chamber-68470.herokuapp.com/). Use this as a model for how we expect your assignment look and operate.

## Description

This application demonstrates a simple full stack application with a front end implemented with HTML/CSS and elements from the Materialize framework and the backend implemented with Node.js and Express. HTML templating is done with the help of Handlebars.

The user may enter any burger name to add it to the menu. This also adds the new burger entry into the MySQL database. The initial burger entry is added as *available* on the menu and placed on the left side of the screen. The user may then eat any burger by clicking on it, which moves it into the adjacent column and updates its status accordingly in the database.

## Installation

To run the application locally, first clone this repository with the following command.

	git@github.com:nikitamehata23/BurgerApp.git
	
Next, install the application dependencies.

	cd eat-da-burger
	npm install
	npm install express
	npm install express-handlebars
	npm install mySql
	
Finally, run the node server locally.

	node server.js
	
Now, open the local application on port 3000 at the URL: `http://localhost:3000/`.

**Enjoy and have a burger!**
