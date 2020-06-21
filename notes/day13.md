order matters in schema 
pg lets us talk to our database. 
app.listen is inside a promise because we need to turn on database before we turn on server.
app.ust(express.urlencoded({extended: true})) allows us to see the request.body- parses it
and serve files from our public folder.
app.set('view engine, ejs) allows your ejs to work and look in the views folder for your template.
= sign will run code in partials. 
posgress always sends an array. use 0 to send the first thing back.
unhandeled promis means we dont have the catch to handle an error.
when we use promises we only need one catch.
before promises we used try to handle errors. now we use .then promises with one catch in it to catch the error.
results.rows checks that i am getting results from the id.
results.rows[0].id will get results from only id. 
put updates information
get reads info
post creates info
detail form are where we will put our update. 
send it with update/task_id
form action='<%= `/update/${taskinfo.id}`%>
put taskid in my update route.
html only does a get or post
method ovveride lets us translate the post to a put. App.use method override.
npm i method-override
app.delet with an id that says delete book. 

npm i express dotenv pg superagent method-override ejs 

// this command matche datavase with shema table.
psql -d pokimon -f shcema.sql

// access table from psql
\c database name
\dt enter
SELECT * FROM  tablename