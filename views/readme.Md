<%=myvar%>  this sign is used to replace the file in app.js
<%- include('header')-%> we can render the layout from one age to another page.
<%- include header.ejs -%> this is another methaod to render the layout.

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
