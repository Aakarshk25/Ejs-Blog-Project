to start the ejs server in github bash you havr to wirte cmd 
nodemon app.js.



<%=myvar%>  this sign is used to replace the file in app.js
<%- include('header')-%> we can render the layout from one age to another page.
<%- include header.ejs -%> this is another methaod to render the layout.
 

 1
 app.get('/about',function(req,res){
  res.render('about',{see:aboutContent})
}) 

explanation ,
'/about' -> this is the area where you want to show your folder.
'about' -> this your file name.
          <li id="about"><a href="/about">ABOUT US</a></li>
 this is the way you have to link your files = /about only this you have to write no root or file directory .


 note =>
  to create a javascript object in ejs 
  var objectName ={ key : value} 
  ex- var myobj={title:req.body.title,
   content:req.body.main}
}) this is two alue pair seprated with coma.


Route Parameter is very important topic .
https://expressjs.com/en/guide/routing.html

note -> rs is used to restart your noadman server.
note -> lodash is very usefull to escape or get rid with upper case and lower case of tite when you search in a search bar

truncate the chareters into a limited words by using 
        ex =  <p><%=post.content.substring(0 , 100) + "..."%></p>
