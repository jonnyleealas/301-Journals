what we want in our tasks table
- id SERIAL PRIMAREY KEY,
title VARCHAR (255),
description VARCHAR (255),
completion VARCHAR(255),
);

go into seed.sql
INSTERST INTO task (titl, description, completion) VALUES ('meal plan', 'plan some meals', 'not done')

INSERT INTO task (title, description, completion) Values('fold clothes', 'wash clothes')
 -f = file name 
 pswl -f seed.sql -d task_app
 -d = database

CREATE DATABASE BANANAS creates bananas database 
you can do this to create a task app database
CREATE DATABASE task_app

get everthing from a table =    let sql= 'SELECT * FROM tasks;'

client.query(sql)//returns promise object
    .then(sqlResulst=>{
        console.log(sqlResults.rows);
        response.status(200).render('index.ejs', {myTodotask: tasks}


        - mytodotask sends to ejs
        
        - ice cream cones evaluate the code in ejs
        //because we need the rows sections in the sqlResults. this will return in terminal
    }


    function showadd form9request,response){
        respnose.status(200).render(add.ejs);
    }
    // this renders shit

    function addtask(request, response){
        let formquery = request.body;
        conosle.log(requestquery);
    }

    we can use a hidden input field to have and add to my favorites.
    

    #

    Render to the index set up a get request objectes from data base helps see that data base is pushing from the page. Title author info use the seed file. do that thing in the demo use app .get render to ejs. make sure youre connecting to psql. render function get.tasks let = Select star client . query render sql reuslt to render.ejs. plug in books instead of taks. connect both shema to psql in the terminal. -f -d thing. do it for both of them. 


    ejs must be refreneced in the env file.
    