tdd test driven deveoplment. build this thing but write out the test before. write the code to make the test pass. 

# Code Review
- In the read me we should always add the names of the collaborators. 
- how to run the appliication.
- instructions.
### filter function 
- identify wht was clicked on, remove everthing, show only what was clicked on.
- add class to our section
- = this.keyword
- function filter(){
    event.preventDefault();
    //find the thing that was clicked on
    let keywordImg = $('this', value);
    //hides the rest of the pics after a pic was clicked
    $('section').hide();
    //target thing I clicked on show
    $(`.${thingIclickedon}`).show();

}
//listens for a change in the event. change is an event like click is an event.
    $('#menu').on('change',filter);

### terenary
- //ternary//
if( a< b){
  return 1;
} else{
  return -1;
}

return a <b ? 1: -1 ;

 return a < b ? 1:
        b < c ? 2:
        c < d ? 3:
        4;



### Js sorts
sorts te elements on an array in place. kinda puts it in order.

- const myArr = ['jon',3,5,6,'apple','aapple',1,2,7,];

myArr.sort();

- const myArr = ['jon','apple','aapple'];

myArr.sort((a,b) => {
  if(a.toLowerCase() > b.toLowerCase()){
    return 1;
  } else if(a.toLowerCase() < b.toLowerCase()){
    return -1;
  } else{
    return 0;
  }
});


myObj.sort((a,b)=> {
  if(ja.name > b.name){
    return 1;
  } else if( a.name < b.name){
    return -1;
  } else {
    return 0;
  }
})




# Flexbox

#right{
    order:1;
    its like float but much easier and gives more control.
}

redisign site using flex. watch flex videos


### template
taking data sets and rendering onto the page. create a template that we can use over and over and over.
that renders to a page. 

### mustache
- https://unpkg.com/mustache@latest
- {{variables go here}}
- {{{3 means read this html dont render}}}
- create a template in html in order to render.

render ou neghborhoods to the page
- make a constructor to run the date grhough contsrutor
- render prototype to render each object inscate to the page using mustache

let hoods =[];

function Hood(obj){
    this.name= obj.name;
    this.city= obj,city;
    this.population= obj.poulation;
    this.founded= obl,founded;
    this.body = obj.body;
    hoods.push(this);
}

neighborhooddataset.forEach( neighborhood => {
    this sends neighborhood into hood. neighborhood is in another js file above the script in html.
    new Hood(neighborhood);
})


### render function for the above

Hood.prototype.toHtml = functionb(){
- get template
- use mustache to render new html by merging template with data
- return the html that we created. 

let template =$('neighborhood-template').html();
let html = Mustache.render(template, this);
return html;
}

### stick it on to the page

hoods.forEach(hood => {
   let hoodHtmle = hood.toHtml();
    - then append to the page
    $('#neighborhoods').append(hoodhtml);
})