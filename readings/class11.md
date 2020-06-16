# Jonathon Lee 
# Class 301
# Read 11

## Ejs
Install by using npm install --save ejs. Set up by using app.set. In parameter x we add view engine, and in y we add ejs.
We can make strings available in the ejs view by adding madulo in elements inside of html; inside the carrots. Similar to a class or id tag. Also, similar to mustache.

# Using ejs with for loops and arrays.
Using madulo inside of html we can build a for loop to run through an array. We can then call an object from js from inside of html. We would call it in the same way we call objects in js. Something like object.name or object.animal.

# Using ejs and if/else statements
If else statements may also be used with ejs inside of html. 

# Ejs layouts
We can install ejs layouts using npm install package. We then use a variable at the top and add express-ejs-layouts. After we call it with app.use(expressLayouts). With this we can create a layout in html that will help us keep one layout through multiple web pages.