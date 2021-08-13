# webmastery
html and css 
*{
    margin: 0;
    padding: 0;
}
.container{
   height: 100vh;
   width: 100%;
   background-image: url(pictures/bg1.png);
   background-position: center;
   background-size: cover;
   padding-left: 5%;
   padding-right: 5%;
   box-sizing: border-box;
   position: relative;
}
.navbar{
     width: 100%;
     height: 15vh;
     margin: auto;
     display: flex;
     align-items: center;
}
.logo{
 width: 60px;
 cursor: pointer;
}
.flag{
 width: 240px;
 cursor: pointer;
}
nav{
   flex: 1;
   padding-left: 60px;
}
nav ul li{
  display: inline-block;
  list-style: none;
  margin: 0px 20px;
}
nav ul li a{
  text-decoration: none;
  color: #333;
}
.content h1{
  font-size: 45px;
  font-weigth: 100;
  margin-top: 24px;
  margin-bottom: 15px;
  color: #232d60;
}
.content p{
  font-size: 20px;
  color: #6a7199;
}
.content{
 margin-left: 10%;
 margin-top: 10%;
}
.content .btn{
display: inline-block;
background: linear-gradient(45deg, #325399, #a8b7d8);
border-radius: 7px;
padding: 10px 20px;
box-sizing: border-box;
text-decoration: none;
color: #fff;
box-shadow: 3px 8px 22px rgba(94,28,68,0.15);
}
.image{
height: 80%;
position: absolute;
bottom: 0;
right: 160px;
}
