# E-commerce-Backend
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)]

# Description
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

My challenge was to build the back end for an e-commerce site. I took a working Express.js API and configure it to use Sequelize to interact with a MySQL database.
# Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Questions](#questions)
# Installation 
After you have cloned the repo, use npm i to install all of the dependencies. Add a .env file to the root of your project directory. This will allow you to connect to your MySQL database. Ex.
```
DB_NAME=ecommerce_db
DB_Password=""
DB_USER="root"
```
# Usage
After the installation is finished...

1. Create a MySQL database on your local machine using the schema.sql file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)
2. Seed the database with sample data to be used for testing purposes(Run npm run seed from inside the root directory of the project)
Now you're ready to start the application! You can start the server by running:
```
node server.js
```
In order to gather data on the backend of the application, you can make request through Insomnia (https://insomnia.rest/download).
```
[Walkthrough Video](https://drive.google.com/file/d/151EXTmqQJpZHULX4Yw6Ze2-pPHWYIibt/view).
```
# License 
This project is licensed under the MIT license.
## Licenses
    This project is covered under the MIT license. To learn more about what this means, click the license button at the top.
# Questions:
* Email: ezinmark@gmail.com
* Github: https://github.com/Ezmaa
* LinkedIn: [[Ezinma-Nwankwo](linkedin.com/in/ezinma-nwankwo-3b7905234)]
