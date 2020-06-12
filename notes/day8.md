npm init should be the first thing that goes in.
we can install all npm libraries at once by typing the names of the libraries one after the other without commas, but using 1 space.
npm start nodeserver .js nodemon
filter return an array of the items you want. it will filter the times with fewer items.
brew services start postgres
brew services stop postgres

# relational storage base

we ask for information using a query
select give me infor
insterst we put info in
update you have infor we will change
delete is cut information out
select *from students where facorite drink= 'coffee;
- all the facoritefoods of the studens select fraveorte
- name of the table= from students
- select * from students where favfood="thai;
- not case sensetive
- Select * From where
- instert startents. = inster into studens (name, facorite_drink) values ('laura', "tea);
- postgres holds database
- postgres runs on a port on our machine
- username is default databas

# to create a database
- create database name;
- create database hello;
\c hello; connects tp tje data base
\c name connects to the name database
- \l lists all databases
- \q quits
- psql hello will connect to the database called hello
- drop database deletes it 
- must add semi colon to execute things in psql
- \c goes into the database of your choosing
- select * from books
- \dt gives all the tables in the database; must be in the databse of search

DROP TABLE IF EXISTS people;

CREATE TABLE people;
id SERIAL PRIMATY KEY, = columns in a database
first_name VARCHAR (255), = characters , 255 is te amout of characters so 255,
last_name VARCHAR(255) = 
- data types are keywords to use in psql
- INSERT INTO people (first_name. last_name)VALUES('diane', 'stephani'),
- psql -f schema.sql -d test = file and database 
- SELEC * FROM people; = means select everything fomr people 

# Do not 
- don't put user names in a database
- safe values $1 , $2, $3, 
- let sql = "inster into people (first_name. last_name) VALUES ($2, $2);
let safeValues = ['bob', 'dylan];
client.query(sql, safeValues).the().cath()

const express = requeir('express);
requir('dotevn).confit();
 (port=300, )

 