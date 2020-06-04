# Jonathon Lee 
# Class 301
# Read 4



## CSS Grid

Columns and rows that form grid containers. Like the parent element that holds the child items.
Grid track are the spaces between the lines on the grid. Grid cell are the smallest units on the grid. Grid areas are multiple cells used to contain an element.  
- we can use the display property with grid.
- The dev tools are helpful when using grid.









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
