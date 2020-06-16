# ejs is a new engine
app.set('view engine', 'ejs');
app.get('/', (request, response)=>{
    response.render('index.ejs');
})

<p><%=myfarvoritefood%><p>

use = of you want it to read as a vareable and display.
without = it will run it as code.
method post= writing data or creating new data.
UNDIFINED ALWAYS MEANS WERE NOT RETURNING FROM A FUNCTION. SO ADD RETURN. MAP ALWAYS NEEDS A RETURN.
