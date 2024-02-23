# Node-js-Login-and-Registration-with-MySQL
Implementing login and registration functionality with Node.js and MySQL involves creating endpoints to handle user authentication and database operations. 

Node.js Registration and Login with Mysql

An example of user registration and user login application developed using Node.js, Express.js and MySQL.

The application allows users to register, login and access to the user's private page session information.

<h1> Install </h1>
Make sure you have Node.js and MySQL installed.

npm install
1.Import
Upload sql-file.sql to MySQL

CREATE TABLE IF NOT EXISTS `users` (
	id int(11) NOT NULL AUTO_INCREMENT,
	name varchar(50) NOT NULL,
	password varchar(32) NOT NULL,
	email varchar(50) NOT NULL,
	CONSTRAINT id PRIMARY KEY(user_id),
);

2.Configure
Edit the db.js file.

3.Start
npm start
Your app should now be running on localhost:3000.
