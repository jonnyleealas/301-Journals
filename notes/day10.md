I have some level of understanding of how to build a fullstack app. node.js is what I need for my career. We spend 4 weeks in nojde js. we used pstgress we used mango db. We have persisted data. We will be adding more tool later on with aditional features and services. 
The main concept of 301 is the web rewuest respsonse cycle. conceptual model of how the internet works. Front end and back end means a fullstack app. 

# Web request response cycle.
- wrrc
- comminciation process betewen client and server.
- client mean some sort of communicstion point from client to server. 
- server can also be the client. 
- front end to back end.
- back end can ask information to goodle.
- hyper text transfer protocol.
- http is a stateless protocol.
- no prior knowlegde of previous request; stateless.

# Rest
- representational
- state- transfer
- Get Post
- rest and http work together. 
- how do we communcate over to http.
- get request is a rest verb over the http protocol

# Request and response stradegdy 
- path needs to match the client
- path goes to get= app.get
- Method is a get request the next piece is the path 
- 3 parts of every request.
- method get post ; i must learn the rest
- to the method we can attatch the body.
- method body headers
- body is data
- status codes like 2001 500 404
- get put post; express will send out status codes
- need to know what status codes are issued to what.
- server means the responder and client meant the requester.

# simple express app
- handles meta information
- dependencies are the most important piece
- things we need to build our app.
- all packages build under node.js model
- express also has 50 packages inside of it.
- node opens express and express opens up other shit.
- why do we care about the version? Because someone else can use my package.json
- npm i goes into the dependency block and installs everything in it.
- packagjosn holds dependencies
- server set up a server to send all that info out?
- process.env = accessess .env file that has the port inside of it. 
- we are building things like an api with ends point to be ablel to capture data.
- localhost point to my local ip
- curl comand line url is like live server in you term
- what is the node js eco system. we use express to build routes or end point. we also spin up a server using an express.
- node modules are additional packages.
- we ignore them by avoiding pushing them up to git repo using gitignore.
- sql is a persistence layer. its a sql based data based system. 
- post request makes data.
- get reads data
- updata make a put request
- pg is the posgrees conector from my app to the data base.

# dependencies, port, and then the routes

pull in package we need to utilize
require package means js will go ingo pj to see if its in there. its the connecting point.
.emv .config loads everthing


- row counts is an array
- what is this data type?
- name the things as long as they want?

# reverse an array
- do you want to do this in place or create a new array?
- produce an array.
- inputs > array
- out put > array reversed.
- visualization
- write out the exact example that Im gonna use.
- [123456]
- [654321]

# edge cases
- things we may not expect.
- what if i get strings instead of an array?
- what if i get objects instead of an array?
- array of all the same thing; would be hard to verify if it was reversed?

# algorithm
- what would i do to revverse an array?
- declare a function that takes in an array
- declare a new array.
- loop through set imput array.
- we can unshift into the new array.
- return the new array.

# pseudo code
- looks simple to read. like python.
- function( arr)
    newArr = []
    arr.forEach()
        newArr.unshift
        return newArr
- write the code
- function reversedArray(arr){
    let newArr =[]
    arr.forEach(value)=> {
        newArr.unshift(value);
    }
    return newArr,
}
- make a chart


# chance interview
- takes first 1 file of every 1000 files
- what kind of data type am i getting sent to me.
- some of them are objects or strings.
- the files themselves are in an array.
- this question is from blue origin.
- do i need to account for the array being empty?
- how do i want them returned?
- output is an array that containts the first file per 1000 files.
- is there a limit? no.
- so if its an array i would assume i dont need to care abgout what the data type is.
- i just need to care about 1 out of every 1000
- need to establish some type of return array.
- i dont nececeraliy need to make this.
- i could use a map.
- but i need to come up with a data structure.
- make a visual.
- pull [0, 1000]
- pick an index and add 1000
- as soon as i return 


# power hour
kris minkel isoft. make your experiences relateable to tech. what are my core values? Meeting deadlines. Work ethic. Talk about what ive learned in my career. how ive changed jobs. Dont forget the fundamentals of what translates to the work field. I must prepare myself. Give them the best representation of myself. how I helped a team mate. How i helped with a task i wasn't assigned to do. what tools have i learned that i can use in my new career? use words that i know. dont make shit up. show that you want to learn. be open to learning. dont over due it. be yourself and show the best of you.


- wrrc web response request cycle
