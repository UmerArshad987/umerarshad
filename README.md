# umerarshad
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Umer's Portfolio</title>
    <style>
        body{
            margin: 0px;
            background-color: black;
            background: -webkit-linear-gradient(-45deg, rgba(84,84,84,0) 0, rgba(84,84,84,0) 40%, rgba(29,29,29,1) 40%, rgba(0,0,0,1) 59%, rgba(58,58,58,0) 59%, rgba(63,63,63,0) 100%), -webkit-linear-gradient(-45deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), -webkit-linear-gradient(-225deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), rgba(33,29,29,1);
  background: -moz-linear-gradient(135deg, rgba(84,84,84,0) 0, rgba(84,84,84,0) 40%, rgba(29,29,29,1) 40%, rgba(0,0,0,1) 59%, rgba(58,58,58,0) 59%, rgba(63,63,63,0) 100%), -moz-linear-gradient(135deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), -moz-linear-gradient(315deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), rgba(33,29,29,1);
  background: linear-gradient(135deg, rgba(84,84,84,0) 0, rgba(84,84,84,0) 40%, rgba(29,29,29,1) 40%, rgba(0,0,0,1) 59%, rgba(58,58,58,0) 59%, rgba(63,63,63,0) 100%), linear-gradient(135deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), linear-gradient(315deg, rgba(0,0,0,1) 0, rgba(0,0,0,1) 7%, rgba(79,79,79,0) 7%, rgba(63,63,63,0) 100%), rgba(33,29,29,1);
  -webkit-background-origin: padding-box;
  background-origin: padding-box;
  -webkit-background-clip: border-box;
  background-clip: border-box;
  -webkit-background-size: 10px 10px;
  background-size: 10px 10px;
        }
        #menu__toggle {
  opacity: 0;
}
#menu__toggle:checked + .menu__btn > span {
  transform: rotate(45deg);
  margin-top: 12px;
}
#menu__toggle:checked + .menu__btn > span::before {
  top: 0;
  transform: rotate(0deg);
}
#menu__toggle:checked + .menu__btn > span::after {
  top: 0;
  transform: rotate(90deg);
}
#menu__toggle:checked ~ .menu__box {
  right: 0 !important;
}
.menu__btn {
  position: fixed;
  top: 20px;
  right: 20px;
  width: 26px;
  height: 26px;
  cursor: pointer;
  z-index: 1;
  /* background-color: rgb(129, 127, 127); */
  border-radius: 100px;
 
  
}
.menu__btn > span,
.menu__btn > span::before,
.menu__btn > span::after {
  display: block;
  position: absolute;
  width: 100%;
  height: 2px;
  background-color: #616161;
  transition-duration: .25s;
}
.menu__btn > span::before {
  content: '';
  top: -8px;
}
.menu__btn > span::after {
  content: '';
  top: 8px;
}
.menu__box {
  display: block;
  position: fixed;
  top: 0;
  right: -100%;
  width: 300px;
  height: 100%;
  margin: 0;
  padding: 80px 0;
  list-style: none;
  background-color: #ECEFF1;
  box-shadow: 2px 2px 6px rgba(0, 0, 0, .4);
  transition-duration: .25s;
}
.menu__item {
  display: block;
  padding: 30px 24px;
  color: #333;
  font-family: 'Roboto', sans-serif;
  font-size: 30px;
  font-weight: 600;
  text-decoration: none;
  transition-duration: .25s;
}
.menu__item:hover {
  background-color: #CFD8DC;
}
.text { 
    display: flex;
    border: 1px dotted;
    height: 30px ;
    width: 120px;
    align-items: center;
    justify-content: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color: gray;
    
    color: black;
    border-radius: 20px ;
    margin-top: 10px;
    margin-left: 10px;
    box-shadow: 0 20px 20px 0 black;
    
    
}
.image1{
margin-left: 20px;
margin-top: 10px;
height: 100px;
width: 100px;
border-radius: 100px;
border: 1px solid black;
box-shadow: 0px 40px 40px 0 black ;
}
.image1 img{
  height: 100px;
  
  
}
.text1 {
    font-size: 50px;
    color: whitesmoke;
    display: flex;
    justify-content: center;
    margin-top: -50px;
}

.text2{
    font-size: 50px;
    color: whitesmoke;
    display: flex;
    justify-content: center;
    margin-top: -150px;
}
.hr1{
    border-top: 3px dashed red;
}
.text3{
  display: flex;
  justify-content: center;
  color: whitesmoke;
}
.button1{
  display: flex;
  justify-content: center;
}
.button1 button{
border: 1px solid;
height: 50px;
width: 200px;
border-radius: 100px;
background-image: linear-gradient(black,rgb(75, 5, 5),rgb(255, 0, 0),red);
color: black;
font-weight: bold;
font-size: 25px;
cursor: pointer;
box-shadow: 0 8px 8px 0 black;
}
.button1 button:hover{
  background-image:linear-gradient(black,rgb(13, 13, 41),rgb(0, 0, 109),blue) ;
  color: black;
  box-shadow: 0 8px 8px 0 rgb(0, 0, 48);
}
.vl{
  margin-top: 100px;
  margin-left: 50%;
  margin-bottom: 100px;
  border-left: 3px dashed red;
  height: 300px;
}
.container1{
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;

}
.item1 {
  font-size: 30px;
  color:white;
  margin-left: -110px;
}
.item2 {
  font-size: 30px;
  color:white;
  margin-left: -100px;
}
.container2{
  display: flex;
 flex-direction: row;
 justify-content: space-evenly;
}
.item3{
  margin-left: 10px;
  height: 500px;
  width: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50px;
  background-color: black;
box-shadow:  30px -20px 10px  rgb(17, 17, 17);

}
.item3 img{
  margin-left: 10px;
  height: 500px;
  width: 500px;
  border-radius: 50px;

}
.item4{
  /* margin-left: 10px; */
  height: 500px;
  width: 500px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50px;
  background-color: black;
box-shadow:  30px -20px 10px  rgb(17, 17, 17);
}
.item4 img{
  margin-left: 10px;
  height: 500px;
  width: 500px;
  border-radius: 50px;
}
.container3{
display: flex;
justify-content: center;
margin-top: 20px;
  
}
.item5{
  border: 1px solid;
  height: 700px;
  width: 700px;
  border-radius: 50px;
  background-color: black;
  box-shadow: 0px 40px 40px 0 black ;

}
.item5 h1{
  margin-top: 30px;
  margin-left: 25px;
  font-size: 40px;
  font-weight: bold;
  color: whitesmoke;
}
.item5 h2{
  font-size:25px;
  color: rgb(88, 88, 88);
  margin-left: 25px;
} 
.item5 img{
  height: 500px;
  width: 500px;
margin-left: 100px;
border-radius: 50px;
}
.container4{
  display: flex;
  justify-content: center;
  font-size: 30px;
  color: whitesmoke;
}
.container5{
display: flex;
justify-content: center;
}
.container5 img{
  height: 1000px;
  width: 1000px;
  box-shadow: 0px 40px 40px 0 black ;
}
footer{
  height: 150px;
  width: 100%;
}


    </style>
</head>
<body>
    <div>
      <div class="image1">
        <img src="fotor-2024012341939.png" alt="">
      </div>
        <div class="text">Umer Arshad</div>
    <div class="hamburger-menu">
        <input id="menu__toggle" type="checkbox" />
        <label class="menu__btn" for="menu__toggle">
          <span></span>
        </label>
    
        <ul class="menu__box">
          <li><a class="menu__item" href="#">Resources</a></li>
          <li><a class="menu__item" href="#">Work</a></li>
          <li><a class="menu__item" href="#">Blog</a></li>
          <li><a class="menu__item" href="#">Contact</a></li>
          <li><a class="menu__item" href="#">About</a></li>
        </ul>
      </div>
    </div>
    <div class="text1">
        <h1>Umer Arshad </h1>
    </div>
<div class="text2">
    <h1 >My Portfolio Website </h1> 
</div>
<div class="hr1">
</div>
<div class="text3">
  <h1>Freelance Page Interface Designer Using HTML And CSS </h1>
</div>
<div class="button1">
  <button>Hire Me!</button>
</div>
<div class="vl"></div>
<div class="container1">
<div class="item1">
  <h1>Interface Example</h1>
</div>
<div class="item2">
<h1>  Dashboard</h1>
</div>
</div>
<div class="container2">
<div class="item3">
  <img src="pasted image 0.png" alt="interface example">
</div>
<div class="item4">
  <img src="infograph-line-and-top-point-free-video.jpg" alt="dashboard example">
</div>
</div>
<div class="container3">
  <div class="item5">
    <h1>Websites </h1>
    <h2>Websites .Webshops .Landingpages</h2>
    <img src="best-homepage-23.png" alt="website example">
  </div>
</div>
<div class="container4">
  <h1>Latest Work</h1>
</div>
<div class="container5">
  <img src="RZlv1pLEOpovMKkP3lTw0xtVhP8.webp" alt="">
</div>
<footer>
  
</footer>
</body>
</html>
