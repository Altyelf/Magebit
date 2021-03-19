# Web Developer Test


This project was created with ReactJS and MySQL database.

---

# Run client side

### `npm install`

To install missing modules.

### `npm start`

To start the application.

---

# Server-side

MySQL server has been set up locally using NodeJS.

Call your database 'mydb'.

Then to siplify things, you can use this command in your MySQL to create a table:
``CREATE TABLE `newdb`.`subscriptions` ( `id` INT NOT NULL AUTO_INCREMENT , `email` VARCHAR(320) NOT NULL UNIQUE, `provider` VARCHAR(100) NOT NULL , `date` TIMESTAMP NOT NULL , PRIMARY KEY (`id`)) ENGINE = InnoDB``

When that is set up, you can open *server* folder and run

### `npm install`

To install missing modules.

### `node server.js`

To start the server and connect to your database.

You should see a message like this: 

*Server is running on port 8000.
Successfully connected to the database.*


