# ParkEazy
##### Project 2 - Group 9

An AirBnB-esque web application... but for parking, where users search for available parking permits/spaces that other's have posted.  It is web application using a MySQL database to store the user data, Sequelize as the ORM, Node & Express to run the server and app, and Handlebars as the templating engine.

## Screenshots

Home:

<img width="1437" alt="s1" src="https://user-images.githubusercontent.com/38221513/50046164-a8cd3700-006c-11e9-998f-6caf7f12eba5.png">


Create a Listing:

<img width="1439" alt="s2 - create" src="https://user-images.githubusercontent.com/38221513/50046169-ec27a580-006c-11e9-9f83-7aa549bd42f1.png">


View Available Listings:

<img width="1437" alt="s3 - search" src="https://user-images.githubusercontent.com/38221513/50046172-03ff2980-006d-11e9-8268-6e0af68d643f.png">


### Prerequisites

In order to install and run ParkEazy you will need the following:

```
Node.js
Express.js
Sequelize
MySQL
Handlebars
```

### Installing

You will need to do the following steps after cloning the repo to your device in order to ensure that it works properly.

To ensure Node.js is running within the package and configure all modules for use:

```
npm install (or npm install -y)
```

This should install all the requisite modules, but just in case, you will need:

Dependencies:
```
express     (npm install -s express)
handlebars  (npm install -s express-handlebars)
mysql2      (npm install -s mysql2)
sequelize   (npm install -s sequelize)
body-parser (npm install -s body-parser)
dotenv      (npm install -s dotenv)
```

Dev Dependencies:
```
chai                    (npm install --save-dev chai)
chai-http               (npm install --save-dev express-handlebars)
eslint                  (npm install --save-dev eslint)
eslint-config-prettier  (npm install --save-dev eslint-config-prettier)
eslint-plugin-prettier  (npm install --save-dev eslint-plugin-prettier)
mocha                   (npm install --save-dev mocha)
nyc                     (npm install --save-dev nyc)
prettier                (npm install --save-dev prettier)
```


## Running 'ParkEazy'

The Sequel is run locally using Node.js, but first you must load the MySQL database, which can be done a number of ways.  The file to create the database is inside the 'db' folder, so it can be opened and run in a MySQL GUI to set up the database, or you can path into the 'db' folder and run it from the MySQL command line (after logging in) using:
 
```
source schema.sql
```
Once the database has been set up, you can then begin the server simply by path into the root folder for the application and running:

```
node server.js
```

This starts the server which is currently set to run at PORT 8080 (http://localhost:8080/), at the same time the model 'listing.js' will create, via Sequelize, the pertinent tables for the application to use.
That is really all there is to starting the application running, after that everything else is run in your browser.

## Deployment

* [Deployed Site](https://parkeazy.herokuapp.com/)



## Built With

* [Node.js](https://nodejs.org/en/) - Runtime Environment
* [MySQL](https://www.mysql.com/) - Database
* [Sequelize](http://docs.sequelizejs.com/) - ORM
* [Handlebars](https://handlebarsjs.com/) - Templating Engine
* [Express.js](https://expressjs.com/) - Web Framework
* [Bootstrap](https://getbootstrap.com/) - CSS Framework
* [WebStorm](https://www.jetbrains.com/webstorm/) - JavaScript IDE
* [DataGrip](https://www.jetbrains.com/datagrip/) - Database IDE

## Authors

* **Dalton Ricker** - [SasquatchXYZ](https://github.com/SasquatchXYZ)
* **Eric Remoroza** - [ericremoroza](https://github.com/ericremoroza)
* **Rodney Stephenson** - [RodneyGT2018](https://github.com/RodneyGT2018)
* **Matt Crowe** - [mjcr223](https://github.com/mjcr223)

## Acknowledgments
* Many thanks to our instructors & TAs, as well as the O'Reilly reference books.
