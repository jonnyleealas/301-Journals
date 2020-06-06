# Servers Back end


Front end is dynamic. We will be connecting this to a server.
Dynamicly rendering pages. Create templates for mustache.

create a let in js.  and use int in the template for mustache.

{{ will read let}} {{{will read lets plus html ex. bold or strong}}}

Write a template using formatted query.
<script type="text/x-tmpl-mustache: id="title-template">
<h2>search results: for {{formatted_query}}</h2>
</script>
<script type="text/x-tmpl-mustache: id="image-template">
<p>{{restarautn}}</p>
<p>{{cuisines}}</p>
<p>{{locality}}</p>
</script>


# Goal: when the user enters a dity , we wat to get that city , diplay the locaction, dipslajt the map, and displaty the restaurants.

- put a linster on the input box.
- use ajax to get the info from the location.json and run it through a constructor function. 
- mustache render prototype.
- and display on the map page.
- display on the summary
- mustache render prototype.
- use ajax to get the infromation from the reastaurants and run it through a contstrucort ansd display on the the restaurants par of the page.


- putting a listener on the input so put it on the form itself
- submit is the event
- use ajax in the funciton 
- ../ gets us out of a place
- getting something always take a while so we need to use a promoise by using .then
- inside the .then parameter is the info we need to receive which we can call bananas
- add a e.preventDefault(); this mean event prevent Default
- then run function through constructor to normalize results

1) build the function to add an event listener to the sumbit form.

2) build constructor
- the .push(this) means push the constructor fucntion in to the array on line 62.

3) add new Location(locationInformoant); into the event listener function
    
4) create Location.prototype.redner = function(){
} put this underneath construcrot event function

5) attatch render to new Location instarance = new Location(locationInformation).render();

6) add Locatrion.prototype.mapRender = function(){
    let template = $('#image-template').html();
    let target = $('#map');
    target.append(Mustache.render(template,this));
}
7) add .then(()=>{
        allLocationInfromation.forEach(location => {
            location.maprRender
        })

8) use ajax to get information from the restaurant. a new ajax to chaing using .then.

9) make a constructor for retaurants

10) run infor throu constructor function .ajazx
11) create a restaurant prototyp for the new constructor to render target the template that was made in html. 

12)
- variable, constructo, prototyp, helper function, event handlers, event listeners.


let allRestaruantsLocaiont = [];
let allLocationInformation=[];

function RTestaurants(obj){
    hte.restaraunt = obj.restaratn;
    this.cuisines = obj.cuisinces;
    this.locality = ojb.locality;
    allReastarantlocation.push(this);
}
function Location(obj){
    this.formatted_query = obj.formatted_query;
    this.search_query = obj.search_query;
    this.latitude = obj.latitude;
    allLocationInformation.push(this);
}


Location.prototype.redner = function(){
    let template = $('#title-template').html();
    let target = $('title');
    target.append(Mustache.render(template,this))
}

 Location.prototype.mapRender = function(){
    let template = $('#image-template').html();
    let target = $('#map');
    target.append(Mustache.render(template,this));
}


 $('#search-form').on(submit, handleSubmit);


function handleSUbmit(){
    e.preventDefault();
    $.ajax('../fake-data/location.json',{method: 'Get', dateType: 'JSON'})
    .then(locastionInformation=> {
        new Location(locationInformation).render();
        console.log('this is my location info', locationInformation)
    })
    .then(()=>{
        allLocationInfromation.forEach(location => {
            location.maprRender
        })
    })
 .then(()=> {
     $.ajax('../fake-date/restaurants.json'), {method: 'GET', dataType: 'JSON'}
     .then(restaurantInfromaio )=> {
     restaurantInformaon.foreEcah(valur => {
         new Reatarant(value);
     })
     }
 })
 .then(()=> {
     allrestaurantInformat.forEach( restaruatn =>{
         new Restartant(value);
     })
     }
 })
}


# back end vs front end

front end tells back end \. Im instersted in infomration for boston. and iback end sends infrom about boston to front end. 
- this is called web request respnse cyslt
- WRRC
- a server is not always a server. server sometimes sgo es to another server . becomes a client when it asks another server for information.
- the asker becomes the client. 
- the giver is the server.
- giving information and sending information
- request or responses.
- github cannot handle servers.
- horoku can hangle servers so we use horoku.


# node environment
- allow you to write js on the backend.

# creating a server
- npm int 
- use a library to write a sever called express.
- put the compoty off te express into server.js. 
- add use strict.
- bring in library on the bak end.
- npm i -S express after adding the library to server.js

const express = requer('express'); // brings in livbray which is our server
const app = express();      // intializes library into a variable
app.get('/', function (re, res){
    res.send('hello world')
})
- 3000 is the server where this is going to live. the port where its going to live.
app.listen(3000)
- npm start to start server
- express has build in methods
- it has get which is the same as ajax
- req = request res= response
- '/' inofrmoation this is a rout= '/bananas'
- then run function requaeast
- then response
- localhost3000 means my computer
- nodemomn looks for changes in the server so you dont have to restart npm.

# back end secret file

- .env 
- PORT=3000 nnnoooo semi-colons
- requier('dotenv').config();
- const PORT = process.env.PORT;
- app.listen(PORT,()=> {
    respse.send
})

- console.log in back end only show up in terminal.
- put keys into env files
# express find public folder and ser files from there.
- app.use(express.tstsic('./public'));



pull request from git hub

1) Go to my class repo fork
2) new pull request
3) compare across forks
4) then create pull request and merg.
5) git pull origin master in terminal.