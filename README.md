<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>News</title>
  <link rel = "stylesheet" href="colorfirstpage.css"/>

</head>
<body>
<div class="awal">
    <div class = "identitas">
      <h2>HELLOWW</h2>
    </div>
    <div class = "menu">
        <ul>
            <li><a href="#Music">Musicians</a> </li>
            <li><a href="#kontak1">Kontak</a> </li>
        </ul>
    </div>
    <p>  </p>
</div>

<div class ="homeawal">
    <img src = "gerhana.jpeg">
    <h1><span></span></h1>
    <p>This is our musicians</p>
</div>
<br><br><br>
<div class = "Member">
    <h1 id ="Music">Musicians</h1>
    <div class ="kotaksatu">
        <p><img src = "Ed.jpeg"></p>
        <p><h4>Ed Sheeran</h4></p>
        <p>Edward Christopher Sheeran MBE is an English singer-songwriter.</p>
        <a href="https://www.instagram.com/teddysphotos?igsh=dzQ2ZXV2NWdrOGoz"><img src="insta.png"> </a>
        <a href="https://www.linkedin.com/in/EdSheeran"><img src="link.png"> </a>
    </div>

    <div class ="kotakdua">
        <p><img src = "taylor.jpeg"></p>
        <p><h4>Taylor Swift</h4></p>
        <p>Taylor Alison Swift is an American singer-songwriter.</p>
        <a href="https://www.instagram.com/taylorswift?igsh=aXAxMTc2NXd3em9l"><img src="insta.png"> </a>
        <a href="https://www.linkedin.com/in/taylorSwift"><img src="link.png"> </a>
    </div>

    <div class ="kotaktiga">
        <p><img src = "ariana.jpeg"></p>
        <p><h4>Ariana Grande</h4></p>
        <p>Ariana Grande-Butera is an American singer, songwriter, and actress. </p>
        <a href="https://www.instagram.com/arianagrande?igsh=MXFpZjVpYnZxcjdhMQ=="><img src="insta.png"> </a>
        <a href="https://www.linkedin.com/in/arianaGrande"><img src="link.png"> </a>
    </div>
    <div class ="kotakempat">
        <p><img src = "justin.jpeg"></p>
        <p><h4>Justin Bieber</h4></p>
        <p>Justin Drew Bieber is a Canadian singer. </p>
        <a href="https://www.instagram.com/justinbieber?igsh=MTh3ZWYxNGplOXRpMg=="><img src="insta.png"> </a>
        <a href="https://www.linkedin.com/in/justinBieber"><img src="link.png"> </a>
    </div>

    <div class ="kotaklima">
        <p><img src = "billie.jpeg"></p>
        <p><h4>Billie Eilish</h4></p>
        <p>Billie Eilish Pirate Baird O'Connell is an American singer and songwriter.</p>
        <a href="https://www.instagram.com/billieeilish?igsh=cTVpNWhiNW1rbXN5"><img src="insta.png"> </a>
        <a href="https://www.linkedin.com/in/billieEilish"><img src="link.png"> </a>
    </div>

</div>
<div class = "kontak">
    <h2 id = "kontak1">Hubungi Kontakku</h2>
    <img src ="kucing.jpeg">
    <h3>Jesica Amanda</h3>
    <p>c14230042</p>
    <h4> whatsapp: 081336248282</h4>

    <h3><a href="https://www.instagram.com/jesicamanda__?igsh=MWQ0aXYzM3Z4OThtZA=="> <img src="insta.png">Instagram</a> </h3>
</div>
<br><br><br>
<div class = "footer">
    <h2>Thank you >_< </h2>

</div>
</body>
</html>


body{
margin: 0;
padding: 0;
font-family: "Times New Roman", sans-serif;
background-color: #E0FFFF;
}
.awal {
background-color: #4682B4;
width: 100%;
height: 70px;
color: white;
text-shadow: 2px 2px 4px black;
position: fixed;
}
.identitas{
float: left;
padding-top: 10px;
padding-bottom: 10px;
padding-left: 20px;
}
.menu{
margin-left : 800px;
padding-top: 20px;
}
.menu ul li{
list-style: none;
display: inline-block;
margin-right: 30px
}
.menu ul li a {
text-decoration: none;
color: white;
}
.menu ul li a:hover{
color: purple;
font-style: italic;
}
.homeawal{
background-image: url('gerhana.jpeg');
background-repeat: no repeat;
background-attachment:fixed;
background-size: 100% 100%;
height: 400px;
padding-top: 200px;
text-align: center;
color: white;
text-shadow: 2px 2px 4px black;
}
.homeawal img{
border: 5px solid white;
border-radius: 100%;
width: 350px;
height: 240px;

}
.homeawal h1{
margin-top: 30px;
margin-bottom: 10px;
}
h1 span:before{
content: '';
animation: gerak infinite 8s ease;
transform: translateY(-50%);
color: light blue;
font-family: 70px;
}
@keyframes gerak {
0%{
content: "Hello!"}
50%{
content: "Welcome to my website"}
100%{
content: "Enjoy!!"}
}

.Member h1{
text-align: center;
color: #4d4d4d;
margin-top: 40px;
align-content: center;
background-color: white;
width: 1300px;
height: 70px;
padding-top: 30px;
text-shadow: 2px 2px 4px gray;
}
.Member a img {
height: 200px;
width: 200px;
float: center;
padding-left: 5px;
padding-right: 5px;

}
.Member p img {
border-radius: 100%;
height: 200px;
width: 200px;
float: center;
padding-left: 5px;
padding-right: 5px;
border: 3px solid white;
}
.Member img:hover{
color: white;
}
.kotaksatu, .kotakdua, .kotaktiga {
float: left;
width: 300px;
height: 320px;
text-align: center;
padding-top: 30px;
padding-bottom:70px;
margin: 80px 20px 20px 80px;
border-radius: 10%;
border: 5px solid #000080;
text-shadow: 2px 2px 4px gray;
}

.kotakempat, .kotaklima{
float: left;
width: 300px;
height: 320px;
text-align: center;
padding-top: 30px;
padding-bottom:70px;
margin: 80px 50px 100px 200px;
border-radius: 10%;
border: 5px solid #000080;
text-shadow: 2px 2px 4px gray;
}
.kotaksatu, .kotaktiga{
background-color: #4682B4;
}
.kotakdua, .kotakempat, .kotaklima{
background-color: #87CEEB;
}
.kotaksatu:hover, .kotakdua:hover, .kotaktiga:hover, .kotakempat:hover, .kotaklima:hover{
background-color: #87CEFA	;
color: white;
}
.kotaksatu a img, .kotakdua a img, .kotaktiga a img, .kotakempat a img, .kotaklima a img{
height: 20px;
width: 20px;
}
.Member h4, p{
margin: 10px,5px,12px,5px;
padding: 0px 20px;
}
.kontak {
text-align: center;
padding: 1000px, 200px, 150px, 10px;
margin-top: 1200px;
color: #4d4d4d;
text-shadow: 2px 2px 4px white;
}
.kontak h2 {
background-color: #B0E0E6

}
.kontak img {
border: 5px solid #B0E0E6;
border-radius: 100%;
height: 190px;
width: 190px;
}
.kontak h3 img{
height: 20px;
width: 20px;
}
.footer{
background-color: #4682B4;
text-align: center;
color: white;
text-shadow: 2px 2px 4px black;
padding-top: 10px;
padding-bottom: 10px;
padding-left: 20px;
}
