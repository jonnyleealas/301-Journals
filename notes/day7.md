zomato api 5e9791d578106faf7280bca8211f1f13


map(value,i,arr)=>{
return value * value
}
returns array


# superAgent is an npm library. it goes and gets information. must be npm install for this.
const superagent = require('superagent);
tihs will gimve me the parts of the body from superagents
let url = 'http://pokeapi.co/api/v2/pokemon/';
superagent.get(url)
.then(resultsfromsuperagent =>{
    console.log(resulstfromsuperagnet.body);
})

# hot info is transmitted on the web

http - hyper text transfer protocal
set of rules for transfering info online.  

- Get we you in ajax to get informtaion
- http also goes and gets reading information.
- put is also update. it updates informtaion.
- post creates information.
- Delete deletes information.

const express = rewuqeir('express');
const cors = requer('cors');
cosnt superagent = require ('SUPeragent')
require('donenv").config();

const app = exrpess();
const PORT = process.env.PORT || 3001;

//got to the web and get real infromataion using super agent
run that finromation through thte constructor 
sendi tito tht front end.



app.get('/location', (request, respnose) => {
    let city = request.query.city;
    let url = GET https://us1.locationiq.com/v1/search.php?key=${process.env.GEO_DATA_A{IO-Key}}=${city}&format=json)

    suyperagent.get(url)
    .then(resultsFromSuperAgent =>
    {
        let finalOBJ = new LOCataion(city, reulstFromSuperAgen.body[0])
        respnose.statrus(200).send(finalobj)
 console.log(resulteforomsuperagent.body)

    })
}

in .env name it banana = token

function Location(searchquery, obj){
    this.search_query = searchquery;
    this.formatted_query = obj.display_name;
    this.lattitude = this.lat;
    this.longitude = this.lon;
}

app.use(cors());
 app.listen(PORT , ()=>{

 })

pkill node kills all servers.