<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Banner</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{

height:100vh;

display:flex;
justify-content:center;
align-items:center;

background:#0d1117;

}

.banner{

width:1000px;
height:350px;

border-radius:20px;

background:linear-gradient(135deg,#6a11cb,#2575fc,#00d4ff);

display:flex;

justify-content:space-between;
align-items:center;

padding:60px;

overflow:hidden;

position:relative;

box-shadow:0 20px 40px rgba(0,0,0,.5);

}

.banner::before{

content:"";

position:absolute;

width:400px;
height:400px;

background:rgba(255,255,255,.08);

border-radius:50%;

top:-120px;
right:-100px;

}

.banner::after{

content:"";

position:absolute;

width:300px;
height:300px;

background:rgba(255,255,255,.05);

border-radius:50%;

bottom:-120px;
left:-100px;

}

.text{

position:relative;

z-index:2;

color:white;

}

.text h1{

font-size:60px;

}

.text h2{

margin-top:15px;

font-weight:400;

font-size:28px;

}

.text p{

margin-top:25px;

font-size:18px;

color:#ececec;

}

.buttons{

margin-top:35px;

}

button{

padding:15px 28px;

margin-right:15px;

border:none;

border-radius:30px;

font-size:16px;

cursor:pointer;

font-weight:600;

transition:.3s;

}

.linkedin{

background:white;

color:#2575fc;

}

.github{

background:#0d1117;

color:white;

border:2px solid white;

}

button:hover{

transform:scale(1.08);

}

.image{

position:relative;

z-index:2;

}

.image img{

width:260px;
height:260px;

border-radius:50%;

border:8px solid white;

object-fit:cover;

box-shadow:0 0 30px rgba(255,255,255,.3);

}

</style>

</head>

<body>

<div class="banner">

<div class="text">

<h1>Simranjeet Kaur</h1>

<h2>Computer Science Student</h2>

<p>
Python • Machine Learning • SQL • Git & GitHub
</p>

<div class="buttons">

<button class="linkedin">LinkedIn</button>

<button class="github">GitHub</button>

</div>

</div>

<div class="image">

<img src="profile.jpg">

</div>

</div>

</body>

</html>
