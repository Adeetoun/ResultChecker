<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="author" content="Adetoun Adewale">
<title>Result Checker</title>
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="https://fonts.google.com/specimen/Hanken+Grotesk">
</head>

<body>
<section class="container">
<div class="container1">
 <h1>Your Result</h1>
<div id="score">
<h2>76</h2>
<span style="opacity: 0.5;">0f 100</span></div>
<h3>Great</h3>
<p> <span style="opacity: 0.5;">You scored higher than 65% of the people who have taken these tests.</span></p>
</div>
<div class="container2">
 <h1>Summary</h1>
<div class="box">
<div class="box-1">
 <p> <img src="../result checker/img/icon-reaction.svg">Reaction <span style="color:black"><strong>80</strong><span style="opacity: 0.5;">/100</span></span></p>
</div>
<div class="box-2">
 <p> <img src="../result checker/img/icon-memory.svg">Memory <span style="color:black"><strong>92</strong><span style="opacity: 0.5;">/100</span></span></p> 
</div>
<div class="box-3">
 <p> <img src="../result checker/img/icon-verbal.svg">Verbal <span style="color:black"><strong> 61</strong><span style="opacity: 0.5;">/100</span></span></p>
</div>
<div class="box-4">
 <p> <img src="../result checker/img/icon-visual.svg">Visual
 <span style="color:black"><strong>72</strong><span style="opacity: 0.5;">/100</span></span></p>
</div>
 <a href="#" class="btn">Continue</a>
</div>
</div>
</section>
</body>
</html>

    * {
margin: 0;
padding: 0;
box-sizing: border-box;
}
body {
margin: auto;
background: whitesmoke;
font-family: 'Hansek Grotesk'; 
}
p {
font-size: 16px;
}
h1 {
font-size: 14px;
}
h3 {
margin-top: 20px;
}
.btn {
background:  hsl(224, 30%, 27%);
color: white;
text-decoration: none;
display: block;
padding: 5px;
margin: 10px;
margin-top: 20px;
text-align: center;
border-radius: 10px;
width: 100%;
}
.container {
display: flex;
justify-content: center;
margin: auto;
max-width: 450px;
height: 100%;
margin-top: 50px;
}
.container .container1 {
background: hsl(241, 81%, 54%);
text-align: center;
color:white;
padding:20px 30px;
border-radius: 10px;
width:50%;
}
.container .container1 p {
margin-top: 30px;
font-size: 14px;
}
.container .container1 #score{
 border: 1px solid hsla(241, 72%, 46%, 0); 
 width: 100px;
 height:100px;
 border-radius: 50%;
 background: hsla(256, 72%, 46%, 1);
 margin: auto;
 margin-top: 20px;
}
.container .container1 #score h2 {
font-size: 40px;
margin-top: 20px;
font-family:'Times New Roman', Times, serif;
display:block;
}
.container .container2{
background: hsl(0, 0%, 100%);
border-radius: 10px;
color:black;
width:50%;
padding: 20px;
}
.container .container2 .box .box-1{
background: rgb(254, 238, 241);
border-radius: 5px;
padding:5px;
margin: 10px;
width: 100%;
}
.container .container2 .box .box-1 p{
    color:rgb(255, 184, 196);
    word-spacing: 3em;
}
.container .container2 .box .box-2{
    background: rgb(253, 240, 221);
    border-radius: 5px;
    padding:5px;
    margin: 10px;
    width: 100%;
}
.container .container2 .box .box-2 p {
    color:rgb(255, 210, 125);
    word-spacing: 3em;
}
.container .container2 .box .box-3{
    background: rgb(235, 244, 235);
    border-radius: 5px;
    padding:5px;
    margin: 10px;
    width: 100%;
}
.container .container2 .box .box-3 p {
    color:rgb(119, 252, 119);
    word-spacing: 4em;
}
.container .container2 .box .box-4 {
background: rgb(254, 242, 254);
border-radius: 5px;
padding:5px;
margin: 10px;
width: 100%;
}
.container .container2 .box .box-4 p{
 color:rgb(66, 66, 247);
 word-spacing: 4em;
}
@media(max-width:768px) {
.container{
flex-direction: column;
max-width: 500px;
}
.container .container2 .box{
justify-content: start;
}
}
