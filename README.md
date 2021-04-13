# Server_Monks_Employee_Onboarding


## Table of Contents

[Description](#Description)  

[User Story](#User_Story)  

[Video Walkthrough](#Video_Walkthrough)  

[Installation Instructions](#Installation_Instructions)  

[APIs](#Apis)

[Questions](#Questions)  


## Description

I created this application with some of my colleagues as a way to help small businesses onboard their new employers quickly. The app can add, edit, and remove employees. The admins can also change employee roles.



## Installation_Instructions

In order to run this application you'll need to install the following:

    "bcrypt": "^5.0.1",
    "connect-session-sequelize": "^7.1.1",
    "dotenv": "^8.2.0",
    "express": "^4.17.1",
    "express-handlebars": "^5.2.1",
    "express-session": "^1.17.1",
    "mysql": "^2.18.1",
    "mysql2": "^2.2.5",
    "pdf.js": "^0.1.0",
    "sequelize": "^6.6.2"

You will need to run the below file in your MySQL database to create the database:

    /db/schema.sql

Once the database has been created and the above applications installed you can run the below commands in your terminal to seed the database and start your server:

    npm run seed

    npm start

Lastly you will need a way to make API calls. You can use a tool like [Postman](https://www.postman.com/) or [Insomnia](https://insomnia.rest/products/insomnia) or build an application of your own.
    

## APIs

A collection of the API endpoints can be found in the below directory. Import this file into [Postman](https://www.postman.com/) or [Insomnia](https://insomnia.rest/products/insomnia) to quickly be able to call the endpoints.

    assets/api_collection

## Questions

For any questions please reach out to me on [GitHub](https://github.com/FarisKadir).