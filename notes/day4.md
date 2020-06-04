# Jonathon Lee 
# Class 301
# Read 4



## CSS Grid

Columns and rows that form grid conainters. Like the parent element that holds the child items.
Grid track are the spaces between the lines on the grid. Grid cell are the smallest units on the grid. Grid areas are multiple cells used to contain an element.  
- we can use the display property with grid.
- The dev tools are helpful when using grid.








## Regex 
Regular expressions extract info from text. They search for search patterns. Used in validation to parsing. This is used in most code languages. A powerful way of parsing text.

 # Anchors 
- ^The matches string with 'Try it!"
- end$ "ends with end"

## Quantifiers
- 


# Class Lecture
Event listeners do not go in event listeners.
What is pagination?
what is mustache?

echnique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic  template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client  can be used for HTML, config files, source code — anything  no if statements, else clauses, or for loops. Instead, there are only tags-   two braces  {{ ____ }}. This is Mustache syntax to show that it is a placeholder. When mustache compiles this, it looks for the property between the two braces and replace it with a value 

## Regex


let str = "abob"
//starts with
let regex = /^[aeiou]/
//ends with
//let regex = /[aeiou]$/

console.log(regex.test(str));


## grid
main{
display: grid;
grid-template-columns: 200px austo 200px;
this takes aways 400px from the height
heigt:calc(100%-400px);
}

div{
    height:100%;

}
body{
   height: 100%;
}

#left{
    order:1;
}
#main{
    order:2;
}
#right{
    order:3;
}
