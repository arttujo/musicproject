**Music Upload Project.**

**How to Deploy.**
 1. Download this project to your machine
 2. with node run NPM intstall package.json. This will get you all of the required dependencies 
 3. For the App to be ran you'll need an SQL database. Our database structure is in the musicproject.sql file.
    - Also a .env file needs to be setup with the following:
    
       DB_HOST: "host address for the database here" E.g. DB_HOST=localhost for localhost usage
       
       DB_USER: "database username here"
       
       DB_NAME: "database name here"
       
       DB_PASS: "database password here"
       
       
 4. After setting up a database and running the app for example with nodemon the app should work by going to your browser and typing in to 
    the address bar: localhost:3000
