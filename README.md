# NodeJS-ExpressJS-MYSQL CRUD app



## Instructions

- Download the code

```
download and unzip the repo
```

- Go into app folder

```
cd into nodejs_crud folder
```

- Install the dependencies

```
npm install express express-fileupload body-parser mysql ejs req-flash --save
```

- Install nodemon globally

```
npm install nodemon -g
```

- Run MySQL script below to create the database and table

```
CREATE DATABASE socka;
CREATE TABLE IF NOT EXISTS `players` (
  `id` int(5) NOT NULL AUTO_INCREMENT,
  `first_name` varchar(255) NOT NULL,
  `last_name` varchar(255) NOT NULL,
  `position` varchar(255) NOT NULL,
  `number` int(11) NOT NULL,
  `image` varchar(255) NOT NULL,
  `user_name` varchar(20) NOT NULL,
  `ranking` varchar(255) not null,
  `playervalue` decimal(9,2) not null,

  PRIMARY KEY (`id`)
) ENGINE=InnoDB  DEFAULT CHARSET=latin1 AUTO_INCREMENT=1;
```

- If nodemon does not work, start the app by using node

```
node app.js
```

Open the browser and go to http://localhost:5000
