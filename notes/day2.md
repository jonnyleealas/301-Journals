border-boxing at the biggingin of every css. This does somthing good. Not sure what lol. Main { margin:auto centers the page}


passing by value vs passing by reference. pass by reference are array and objects. pass by value are numbers booleans strings. 

jquery selectors.
a library like chart.js. We have to link it into html. 

cdn- content delivery network. its linking to a library.
anything you can do in css you can do in jquery.

data attibute
<li data-favortieFood="cherries">cherries</li>

$('li[data-favoriteFood="cherreis"])

setter vs getters
 $(li).text ()= gets text
 $(li).text(laskdjf)= sets text

 Jquery events
 selector.on(even,callback);

 $().ready(callback)
 $(document).ready(callback)

$().ready(()=> {

    jquery code goes in here
}

this means...
this is the event.target. the thing that was clicked. event was the clicking. the target is the thing that was clicked on. in jquery 'this' is the thing that was clicked on.

- prevent default stop it from reloading the page.

cdn for jquery goes under footer with a script tag rigth about the app.js.

exucutable code goes in the $().ready 
code that depends on the html goes outside the ready function.

### Event delegation
$(ul li).on('click',callback)

better

$(ul).on('click', li, callback)

### jquesry allows us to go in the big wide world and get information.

### ajax calls with jquery
asynchronous js requests
#
$.ajax can go to google and get info.
$.ajax ('/path/to/file') will get data from the local file path. 
first get the data
$.ajaz('/filepath)
second tell what type do f data and what format the daya is.
$.ajax('filepath',{method:"get",dataytrpe:json}
then tell what to do with thte datat)
$.ajax('/filpath',{method:"get", datype:"json})
.the(data=?//do something)

constructor function to normalis the date
name, image_url, hobbies
name:ginger, destroys of pens
imat:gings.jpeg
hobbeis: easting cables
i ned to get the data.json and make the new object instances with it.
pus into an array so that i have all my objes instance in one place.
every object instance needs a protogype
get my template
make a copy of it
 fill ith with my object instance
 append to the dom



