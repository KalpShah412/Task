# Task

<!DOCTYPE html>
<html lang="en">
<head>
<title>Task</title>

<style>

.header{
    padding-left: 10%;
    word-spacing: 100px;
    background-color: black;
    color: white;
    padding: 10px;
    cursor: pointer;
    font-size: large;
    display: block;
}
.left{
    float: left;
    line-height: 3;
    border-right: solid black;
    height: 330px;
    cursor: pointer;
    background-color:khaki;
}
.center{
    padding-left: 10%;
    text-align-last: center;
    display: block;
    padding-right: 10%;
}
.right{
    float: right;
    line-height: 3;
    border-left: solid black;
    height: 330px;
    cursor: pointer;
    background-color:khaki;
}
h1{
    text-align: center;
    color: rebeccapurple;
    font-weight: bold;
    text-decoration: underline;
    background-color: lawngreen;
    display: block;
}
footer{
    padding: 10px;
    text-align: center;
    background-color: grey;
    font-size: x-large;
    
}
.img{
    position: relative;
}
.text-block {
    position: absolute;
    bottom: 20px;
    right: 20px;
    background-color: black;
    color: white;
    padding-left: 20px;
    padding-right: 50px;
}
.text-block{
    font-size: x-large;
}
a:visited{
    color: green;
}
a:hover{
    color: red;
}

.column 
{ 
   float: left; 
   width: 33%; 
   padding: 5px; 
} 
      
.row { 
    margin: 0 -5px; 
} 
  
.row:after { 
    content: ""; 
    display: table; 
} 
  

.card { 
    padding: 10px; 
    text-align: center; 
    background-color: gray; 
    color: white; 
    } 
      
.card:hover { 
    transform: scale(1.1); 
    background-color: black; 
    transition-duration: 2s; 
    color: white; 
} 
      
.fa { 
    font-size: 50px; 
} 
h4{
    text-align: center;
}
</style>
</head>
<body>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<div class="header">
<input type="text" placeholder="Search for Name">
Home
Watch
Group 
Gaming
</div>

<div class="left">
    Profile <br>
    Covid-19 <br>
    Friends <br>
    Events <br>
    Memories <br>
    Saved <br>
</div>

<div class="right">
    Birthdates <br>
    Contacts <br>
    Group <br>
    Notification <br>
    Add Friend <br>
    Message <br>
</div>

<body> 
    <h1>Title</h1> 
    <h4>Section Counter</h4> 
    <br><br> 
    <div class="row"> 
        <div class="column"> 
            <div class="card"> 
                <p><i class="fa fa-user"></i></p> 
                <h3>750+</h3> 
                <p>Classes</p> 
            </div> 
        </div> 
        <div class="column"> 
            <div class="card"> 
                <p><i class="fa fa-book"></i></p> 
                <h3>600+</h3> 
                <p>Interfaces</p> 
            </div> 
        </div> 
        <div class="column"> 
            <div class="card"> 
                <p><i class="fa fa-smile-o"></i></p> 
                <h3>7000+</h3> 
                <p>Abstract Classes</p> 
            </div> 
        </div> 
    </div> 
</body> 


  <section>
      <img src="data:image/jpeg;base64,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"  width="300" height="300">
  </section>
<div class="img">
    <div class="container">
  <img src="data:image/jpeg;base64,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" width="100%">
</div>
  <div class="text-block">
        <h4>Snow</h4>
        <p>What a beautiful Mountain</p>
    </div>
</div>
<footer>
    <a href="#">Facebook</a> <br>
    <a href="#">pinterest</a><br>
    <a href="#">twitter</a><br>
    <a href="#">linkedin</a><br>
    <p>
      Powered by <a href="#">Kalp Shah</a>
    </p>
  </footer>
</body>
</html>
