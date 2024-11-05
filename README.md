
<html lang="en">
<head>



  <body style="background-color:black;">
  <link rel="stylesheet" href="Style.css">

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}


/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}
#Inicio {background-color: black;}
#Flaps {background-color: black;}
#Slats {background-color: black;}
#Spoilers {background-color: black;}
#Aleta {background-color: black;}
#Control {background-color: black;}
#Protocolo {background-color: black;}
#Secundarios {background-color: black;}
</style>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}



















/* From Uiverse.io by neerajbaniwal */ 
.Titulo {

  padding: 10px 2px;
  color: #fff;
  background: linear-gradient(to right, #11d697 0, #00ffe4 10%, White 90%);
  background-position: 0;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: shine 3s infinite linear;
  animation-fill-mode: forwards;
  -webkit-text-size-adjust: none;
  font-weight: 800;
  font-size: 26px;
  text-decoration: none;
  white-space: nowrap;
  font-family: "Poppins", sans-serif;
}
@-moz-keyframes shine {
  0% {
    background-position: 0;
  }
  60% {
    background-position: 180px;
  }
  100% {
    background-position: 180px;
  }
}
@-webkit-keyframes shine {
  0% {
    background-position: 0;
  }
  60% {
    background-position: 180px;
  }
  100% {
    background-position: 180px;
  }
}
@-o-keyframes shine {
  0% {
    background-position: 0;
  }
  60% {
    background-position: 180px;
  }
  100% {
    background-position: 180px;
  }
}
@keyframes shine {
  0% {
    background-position: 0;
  }
  60% {
    background-position: 180px;
  }
  100% {
    background-position: 180px;
  }
}







/* From Uiverse.io by Yaya12085 */ 
.cuadros {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.ilustracion {
  height: 10rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}

.text-1 {
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.text-23 {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text-23 span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text-23 span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.acButton {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}

.Dato {
  margin-top: 1rem;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  color: rgba(156, 163, 175, 1);
}








/* From Uiverse.io by Li-Deheng */ 
#btn-message {
  --text-color: #000;
  --bg-color-sup: #d2d2d2;
  --bg-color: #f4f4f4;
  --bg-hover-color: #ffffff;
  --online-status: #00da00;
  --font-size: 16px;
  --btn-transition: all 0.2s ease-out;
}

.button-message {
  display: flex;
  justify-content: center;
  align-items: center;
  font: 400 var(--font-size) Helvetica Neue, sans-serif;
  box-shadow: 0 0 2.17382px rgba(0,0,0,.049),0 1.75px 6.01034px rgba(0,0,0,.07),0 3.63px 14.4706px rgba(0,0,0,.091),0 22px 48px rgba(0,0,0,.14);
  background-color: var(--bg-color);
  border-radius: 68px;
  cursor: pointer;
  padding: 6px 10px 6px 6px;
  width: fit-content;
  height: 40px;
  border: 0;
  overflow: hidden;
  position: relative;
  transition: var(--btn-transition);
}

.button-message:hover {
  height: 56px;
  padding: 8px 20px 8px 8px;
  background-color: var(--bg-hover-color);
  transition: var(--btn-transition);
}

.button-message:active {
  transform: scale(0.99);
}

.content-avatar {
  width: 30px;
  height: 30px;
  margin: 0;
  transition: var(--btn-transition);
  position: relative;
}

.button-message:hover .content-avatar {
  width: 40px;
  height: 40px;
}

.avatar {
  width: 100%;
  height: 100%;
  border-radius: 50%;
  overflow: hidden;
  background-color: var(--bg-color-sup);
}

.user-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.status-user {
  position: absolute;
  width: 6px;
  height: 6px;
  right: 1px;
  bottom: 1px;
  border-radius: 50%;
  outline: solid 2px var(--bg-color);
  background-color: var(--online-status);
  transition: var(--btn-transition);
  animation: active-status 2s ease-in-out infinite;
}

.button-message:hover .status-user {
  width: 10px;
  height: 10px;
  right: 1px;
  bottom: 1px;
  outline: solid 3px var(--bg-hover-color);
}

.notice-content {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
  padding-left: 8px;
  text-align: initial;
  color: var(--text-color);
}

.username {
  letter-spacing: -6px;
  height: 0;
  opacity: 0;
  transform: translateY(-20px);
  transition: var(--btn-transition);
}

.user-id {
  font-size: 12px;
  letter-spacing: -6px;
  height: 0;
  opacity: 0;
  transform: translateY(10px);
  transition: var(--btn-transition);
}

.lable-message {
  display: flex;
  align-items: center;
  opacity: 1;
  transform: scaleY(1);
  transition: var(--btn-transition);
}

.button-message:hover .username {
  height: auto;
  letter-spacing: normal;
  opacity: 1;
  transform: translateY(0);
  transition: var(--btn-transition);
}

.button-message:hover .user-id {
  height: auto;
  letter-spacing: normal;
  opacity: 1;
  transform: translateY(0);
  transition: var(--btn-transition);
}

.button-message:hover .lable-message {
  height: 0;
  transform: scaleY(0);
  transition: var(--btn-transition);
}

.lable-message, .username {
  font-weight: 600;
}

.number-message {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin-left: 8px;
  font-size: 12px;
  width: 16px;
  height: 16px;
  background-color: var(--bg-color-sup);
  border-radius: 20px;
}

/*==============================================*/
@keyframes active-status {
  0% {
    background-color: var(--online-status);
  }

  33.33% {
    background-color: #93e200;
  }

  66.33% {
    background-color: #93e200;
  }

  100% {
    background-color: var(--online-status);
  }
}










/* From Uiverse.io by eduardo-amaro-maciel */ 
.scroll-1::-webkit-scrollbar {
  width: 8px;
  height: 8px;
}

.scroll-1::-webkit-scrollbar-thumb {
  border-radius: 20px;
  background: #888;
}

.container * {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  color: #fff;
}

.container {
  display: flex;
  overflow-x: scroll;
  padding: 14px;
  width: 1150px;
  scroll-snap-type: x mandatory;
  scroll-padding-top: 24px;
  border-radius: 8px;
  gap: 20px;
}

.container .card {
  flex: 0 0 100%;
  overflow: hidden;
  border-radius: 8px;
  background-color: #141414;
  scroll-snap-align: start;
}

.card .card__image {
  flex: 1;
  height: 140px;
}

.card:nth-child(1) .card__image {
  background-image: linear-gradient(
      to right top,
      #051937, 
      #004d7a, 
      #008793, 
      #00bf72, 
      #a8eb12
  );
}

.card:nth-child(2) .card__image {
  background-image: linear-gradient(
    to right top, 
    #dc09a5, 
    #ce00b4, 
    #ba00c5, 
    #9c00d8, 
    #6f12eb
  );
}

.card:nth-child(3) .card__image {
  background-image: linear-gradient(
    to right top, 
    #dc1009, 
    #e55f00, 
    #e49200, 
    #dac000, 
    #c7eb12
  );
}

.card .card__content {
  display: flex;
  flex-direction: column;
  gap: 10px;
  padding: 40px;
}

.card .card__content .card__title {
  font-size: 32px;
  color: #fff;
  text-transform: capitalize;
}

.card .card__content .card__describe {
  color: #fff;
  font-size: 16px;
}











/* From Uiverse.io by Javierrocadev */ 
.Perla {
  width: 550px;
  height: 260px;
  background: #f7f9f9;
  padding: 10px;
  border-radius: 16px;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: flex-start;
}

.TextPe {
  font-size: 1.4em;
  font-weight: 800;
}

.TextAle {
  font-weight: 500;
}





/* From Uiverse.io by abhusha08 */ 


.red-btn {
  width: 900px;
  height: 300px;
  margin: 15px;
  background: rgb(255, 0, 0);
  background: rgb(131, 58, 180);
  background: linear-gradient(
    90deg,
    rgba(131, 58, 180, 1) 0%,
    rgba(253, 29, 29, 1) 50%,
    rgba(252, 176, 69, 1) 100%
  );
  color: white;
  border: none;
  border-radius: 0.625em;
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
  position: relative;
  z-index: 1;
  overflow: hidden;
}
.blue-btn {
  width: 900px;
  height: 300px;
  margin: 15px;
  background: rgb(0, 8, 144);
  background: linear-gradient(
    90deg,
    rgba(0, 8, 144, 1) 0%,
    rgba(16, 0, 255, 1) 22%,
    rgba(86, 255, 247, 1) 100%
  );
  color: white;
  border: none;
  border-radius: 0.625em;
  font-size: 20px;
  font-weight: bold;
  cursor: pointer;
  position: relative;
  z-index: 1;
  overflow: hidden;
}

button:hover {
  color: rgb(0, 0, 0);
}

button:after {
  content: "";
  background: white;
  position: absolute;
  z-index: -1;
  left: -20%;
  right: -20%;
  top: 0;
  bottom: 0;
  transform: skewX(-45deg) scale(0, 1);
  transition: all 0.5s;
}

button:hover:after {
  transform: skewX(-45deg) scale(1, 1);
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}







/* From Uiverse.io by Yaya12085 */ 
.cookie-card {
  max-width: 1320px;
  padding: 1rem;
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 20px 20px 30px rgba(0, 0, 0, .05);
}

.title {
  font-weight: 600;
  color: rgb(31 41 55);
}

.description {
  margin-top: 1rem;
  font-size: 0.875rem;
  line-height: 1.25rem;
  color: rgb(75 85 99);
}

.description a {
  --tw-text-opacity: 1;
  color: rgb(59 130 246);
}

.description a:hover {
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
}

.actions {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 1rem;
  -moz-column-gap: 1rem;
  column-gap: 1rem;
  flex-shrink: 0;
}

.pref {
  font-size: 0.75rem;
  line-height: 1rem;
  color: rgb(31 41 55 );
  -webkit-text-decoration-line: underline;
  text-decoration-line: underline;
  transition: all .3s cubic-bezier(0.4, 0, 0.2, 1);
  border: none;
  background-color: transparent;
}

.pref:hover {
  color: rgb(156 163 175);
}

.pref:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.accept {
  font-size: 0.75rem;
  line-height: 1rem;
  background-color: rgb(17 24 39);
  font-weight: 500;
  border-radius: 0.5rem;
  color: #fff;
  padding-left: 1rem;
  padding-right: 1rem;
  padding-top: 0.625rem;
  padding-bottom: 0.625rem;
  border: none;
  transition: all .15s cubic-bezier(0.4, 0, 0.2, 1);
}

.accept:hover {
  background-color: rgb(55 65 81);
}

.accept:focus {
  outline: 2px solid transparent;
  outline-offset: 2px;
}






/* From Uiverse.io by Kagamiie */ 
.project-info {
  padding: 100px 40px;
  display: flex;
  flex-direction: column;
  gap: 20px;
  position: relative;
  top: -50px;
}

.project-title {
  font-weight: 900;
  font-size: 1.5em;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  color: black;
}

.lighter {
  font-size: 0.9em;
}

.flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.tag {
  font-weight: lighter;
  color: grey;
}

/*DELETE THIS TWO LINE*/
.delete {
  background-color: #15ce99;
}

.card-img div {
  width: 90%;
}
/*IF USING IMAGES*/

.cota {
  background-color: #d9d9d9;
  color: black;
  width: 300px;
  max-height: 280px;
  border-radius: 8px;
  box-shadow: rgba(50, 50, 93, 0.25) 0px 50px 100px -20px,
    rgba(0, 0, 0, 0.3) 0px 30px 60px -30px;
}

.card-img {
  position: relative;
  top: -20px;
  height: 100px;
  display: flex;
  justify-content: center;
}

/* Change the .card-img div to .card-img img to use img*/
.card-img a,
.card-img div {
  height: 150px;
  width: 90%;
  /* Change this width here to change the width of the color/image */
  object-fit: cover;
  border-radius: 8px;
  box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
}

.card-imgs {
  transition: all 0.5s;
}










/* From Uiverse.io by Creatlydev */ 
.Google {
  margin: auto;
  width: min(300px, 100%);
  background-color: #fefefe;
  border-radius: 1rem;
  padding: 0.5rem;
  color: #141417;
}
.card__hero {
  background-color: #fef4e2;
  border-radius: 0.5rem 0.5rem 0 0;
  padding: 1.5rem;
  font-size: 0.875rem;
}
.card__hero .card__job-title {
  margin: 2rem 0;
  font-size: 2rem;
  font-weight: 600;
  padding-right: 2rem;
}
.card__hero-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-direction: row;
  flex-wrap: nowrap;
  gap: 1rem;
  font-weight: 700;
}
.card__footer {
  display: flex;
  justify-content: flex-start;
  align-items: start;
  flex-direction: column;
  flex-wrap: nowrap;
  padding: 0.75rem;
  row-gap: 1rem;
  font-weight: 700;
  font-size: 0.875rem;
}
@media (min-width: 340px) {
  .card__footer {
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
  }
}
.card__job-summary {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  flex-wrap: nowrap;
  gap: 0.75rem;
}
.card__Secundario {
  width: 100%;
  font-weight: 400;
  border: none;
  display: block;
  cursor: pointer;
  text-align: center;
  padding: 0.5rem 1.25rem;
  border-radius: 1rem;
  background-color: #141417;
  color: #fff;
  font-size: 1rem;
}
@media (min-width: 340px) {
  .card__Secundario {
    width: max-content;
  }
}














</style>





<div class="topnav">
<center><h3 class="Titulo">CONTROLES DE VUELO PRIMARIOS Y SECUNDARIOS</h3></center>


</div>
<br>
<br>



<div id="Inicio" class="tabcontent">






















<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Verdana, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 12.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>


<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 5</div>
  <center><img src="https://i.pinimg.com/564x/51/c5/da/51c5dade6771b29e663874d4a169d9f9.jpg"  width="991" height="400"></center>
  <div class="text">Flaps</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 5</div>
  <center><img src="https://i.pinimg.com/564x/cd/a2/ad/cda2ad018bca8199381ef880e9a93f34.jpg"  width="991" height="400"></center>
  <div class="text">Flaps</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 5</div>
  <center><img src="https://i.pinimg.com/564x/72/8f/43/728f43f530d30c8f803aef26347be2f4.jpg"  width="991" height="400"></center>
  <div class="text">Flaps</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 5</div>
  <center><img src="https://i.pinimg.com/564x/77/bc/be/77bcbe3d2da06f683b6179deca2dfd71.jpg"  width="991" height="400"></center>
  <div class="text">Flaps</div>
</div>


<div class="mySlides fade">
  <div class="numbertext">4 / 5</div>
  <center><img src="https://i.pinimg.com/564x/d5/58/18/d55818d31052757d5d38f530bf6928f4.jpg"  width="991" height="400"></center>
  <div class="text">Flaps</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
    <span class="dot"></span> 
      <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 4000); // Change image every 2 seconds
}
</script>

</body>
</html> 

<br>
<br>
















<center>


<button id="btn-message" class="button-message">
  <div class="content-avatar">
    <div class="status-user"></div>
    <div class="avatar">
    <center><img src="https://i.pinimg.com/736x/ea/b7/04/eab704f7a6e95ae80adc842426c7b1b8.jpg" class="img-circle" alt="Cinque Terre" width="50" height="40"></center>
      <svg class="user-img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,12.5c-3.04,0-5.5,1.73-5.5,3.5s2.46,3.5,5.5,3.5,5.5-1.73,5.5-3.5-2.46-3.5-5.5-3.5Zm0-.5c1.66,0,3-1.34,3-3s-1.34-3-3-3-3,1.34-3,3,1.34,3,3,3Z"></path></svg>
    </div>
  </div>
  <div class="notice-content">
    <div class="username">Dani_14.2</div>
    <div class="lable-message">LUIS DANIEL<span class="number-message">1</span></div>
    <div class="user-id">Instagram</div>
  </div>
</button>

<br>
</center>
















<center>
<table>
  <tr>
    <th>
<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/5f/75/24/5f75246297e809b357ae2a2e082eb1d5.jpg" class="img-circle" alt="Cinque Terre" width="300" height="180"></div>
  <div class="content">


  <div class="text-23">
      <span>
        FLAPS
      </span>
    <span>DESCRIPCION</span>

   </div>

   <button class="acButton" onclick="openPage('Flaps', this)">
      Mas INFORMACION
    </button>

   <p class="Dato">
Luis Daniel
    </p>
  </div>
</div>
</th>




<th>


<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/f3/76/79/f37679b8bf6d077d8014863ccaeadd14.jpg" class="img-circle" alt="Cinque Terre" width="271" height="180"></div>
  <div class="content">


   <div class="text-23">
      <span>
        SLATS
      </span>
    <span>DESCRIPCION</span>
    </div>
    <button class="acButton" onclick="openPage('Slats', this)">
      Mas INFORMACION
    </button>
    <p class="Dato">
Luis Daniel
    </p>
  </div>
</div>

</th>


<th>

<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/f4/11/c6/f411c6ed80deb8f9eed0ea7109e839ab.jpg" class="img-circle" alt="Cinque Terre" width="271" height="180"></div>
  <div class="content">


  <div class="text-23">
      <span>
        Spoilers
      </span>
    <span>DESCRIPCION</span>
    </div>
    <button class="acButton" onclick="openPage('Spoilers', this)">
      Mas INFORMACION
    </button>
    <p class="Dato">
Luis Daniel
    </p>
  </div>
</div>

</th>


<th>


<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/35/d9/e9/35d9e9a29ab9b37ffc8b3e15804a9c81.jpg" class="img-circle" alt="Cinque Terre" width="271" height="180"></div>
  <div class="content">


  <div class="text-23">
      <span>
        Aletas
      </span>

<span>DESCRIPCION</span>

</div>

<button class="acButton" onclick="openPage('Aletas', this)">
      Mas INFORMACION
    </button>

  <p class="Dato">
Luis Daniel
    </p>
  </div>
</div>
</th>




</tr>
</table></center>
<br>










  <br>


<center>
<button id="btn-message" class="button-message">
  <div class="content-avatar">
    <div class="status-user"></div>
    <div class="avatar">
    <center><img src="https://i.pinimg.com/736x/39/c4/1a/39c41af5a1f62f350e92b9ca0beb390a.jpg" class="img-circle" alt="Cinque Terre" width="50" height="40"></center>
      <svg class="user-img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,12.5c-3.04,0-5.5,1.73-5.5,3.5s2.46,3.5,5.5,3.5,5.5-1.73,5.5-3.5-2.46-3.5-5.5-3.5Zm0-.5c1.66,0,3-1.34,3-3s-1.34-3-3-3-3,1.34-3,3,1.34,3,3,3Z"></path></svg>
    </div>
  </div>
  
  
  <div class="notice-content">

  
  
  
   <div class="username">lxpvmmg</div>
    <div class="lable-message">Perla Alexa<span class="number-message">2</span></div>
    <div class="user-id">Instagram</div>
  </div>
</button>


<br>
<br>
<div class="Perla">
  <FONT COLOR="black"><span class="TextPe">Controles de Vuelo</span>
  <p class="TextAle">Los controles de vuelo son los sistemas y dispositivos que permiten a un piloto manejar y dirigir un avión durante el vuelo. Estos controles se dividen en dos categorías principales</p></FONT>

  <button class="acButton" onclick="openPage('Control', this)">Mas Informacion</button>
</div>



















<br>
<br>





<button id="btn-message" class="button-message">
  <div class="content-avatar">
    <div class="status-user"></div>
    <div class="avatar">
    <center><img src="https://i.pinimg.com/736x/fa/99/fd/fa99fd3e409a9c906de4fe147d60dc34.jpg" class="img-circle" alt="Cinque Terre" width="50" height="40"></center>
      <svg class="user-img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,12.5c-3.04,0-5.5,1.73-5.5,3.5s2.46,3.5,5.5,3.5,5.5-1.73,5.5-3.5-2.46-3.5-5.5-3.5Zm0-.5c1.66,0,3-1.34,3-3s-1.34-3-3-3-3,1.34-3,3,1.34,3,3,3Z"></path></svg>
    </div>
  </div>
  
  
  <div class="notice-content">
  
  
  
   <div class="username">Casango_</div>
    <div class="lable-message">Jose Casango<span class="number-message">3</span></div>
    <div class="user-id">Instagram</div>
  </div>
</button>

<br>
<br>

<div class="Perla">
  <FONT COLOR="black"><span class="TextPe">Protocolos de Seguridad e Innovacion</span>
  <p class="TextAle">Consisten en una inspección rápida en la que se comprueban aspectos generales de la aeronave como el estado de los neumáticos, el nivel de aceite, la posible existencia de algún daño estructural.</p></FONT>

  <button class="acButton" onclick="openPage('Protocolo', this)">Mas Informacion</button>
</div>





















<br>
<br>




<button id="btn-message" class="button-message">
  <div class="content-avatar">
    <div class="status-user"></div>
    <div class="avatar">
    <center><img src="https://i.pinimg.com/736x/be/cc/05/becc05e8aa630958004f34d387747f43.jpg" class="img-circle" alt="Cinque Terre" width="50" height="40"></center>
      <svg class="user-img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,12.5c-3.04,0-5.5,1.73-5.5,3.5s2.46,3.5,5.5,3.5,5.5-1.73,5.5-3.5-2.46-3.5-5.5-3.5Zm0-.5c1.66,0,3-1.34,3-3s-1.34-3-3-3-3,1.34-3,3,1.34,3,3,3Z"></path></svg>
    </div>
  </div>
  
  
  <div class="notice-content">
  
  
  
   <div class="username">d.lunna_</div>
    <div class="lable-message">Diego Luna<span class="number-message">5</span></div>
    <div class="user-id">Instagram</div>
  </div>
</button>


<br>
<br>



























<div class="cookie-card">
    <span class="title"> Velocidades y Controles</span>
    <p class="description">En aviones de alta velocidad, los controles de vuelo se dividen en controles de vuelo primarios y controles de vuelo secundarios o auxiliares. Los controles de vuelo primarios maniobran la aeronave sobre los ejes de cabeceo, alabeo y dirección (o guiñada).
</p>
    
  <br>
         <p class="description">Se incluyen los alerones, elevadores y timón. Los controles de vuelo secundarios o auxiliares incluyen compensadores, flaps de borde de ataque, flaps de borde de fuga, spoilers, y slats.

</p>
  <br>

   <p class="description">Los spoilers se utilizan en el extradós alar para
deteriorar o reducir la sustentación. Las aeronaves de alta velocidad, debido a su diseño limpio de baja resistencia utilizan spoilers como frenos de velocidad
para reducir la velocidad. Los spoilers se extienden inmediatamente después de aterrizar para eliminar sustentación y así transferir el peso de la aeronave desde las alas a las ruedas para un mejor rendimiento de frenado.

</p>
  <br>
 

</div>


































































<br>
<br>


<button id="btn-message" class="button-message">
  <div class="content-avatar">
    <div class="status-user"></div>
    <div class="avatar">
    <center><img src="https://i.pinimg.com/736x/23/96/a8/2396a8f1d95c0fece05366467da79c89.jpg" class="img-circle" alt="Cinque Terre" width="50" height="40"></center>
      <svg class="user-img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M12,12.5c-3.04,0-5.5,1.73-5.5,3.5s2.46,3.5,5.5,3.5,5.5-1.73,5.5-3.5-2.46-3.5-5.5-3.5Zm0-.5c1.66,0,3-1.34,3-3s-1.34-3-3-3-3,1.34-3,3,1.34,3,3,3Z"></path></svg>
    </div>
  </div>
  
  



  <div class="notice-content">
  


  
  
   <div class="username">albertocota_667</div>
    <div class="lable-message">Cota (Beto)<span class="number-message">4</span></div>
    <div class="user-id">Instagram</div>
  </div>
</button>

<br>
<br>


















































<div class="cookie-card">
    <span class="title">🍪 Controles De vuelo Secundario</span>
    <p class="description">Los controles de vuelo secundarios son componentes críticos de un avión que ayudan a controlar su movimiento y estabilidad. A continuación, te presento una lista de los controles de vuelo secundarios más comunes:</p>
        <br>
  <br>
  <table>
    <tr>
    <th>
  
  <div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/7b/00/5d/7b005dd7cc864c652aeffa3442cf1a86.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Alerones</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Controlan el movimiento de balanceo (rol) del avión.
</span
    >
  </div>
</article>

  
  
  </div>

</th>


<th>
<div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/2f/bf/4c/2fbf4c2b11133dd30503c6ff12a45590.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Elevadores</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Controlan el movimiento de cabeceo (pitch) del avión.

</span
    >
  </div>
</article>

  
  
  </div>

</th>






<th>
<div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/48/86/20/4886204dd04d1237bda1cfc684f5a9a1.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Timon</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Controla el movimiento de guiñada (yaw) del avión.


</span
    >
  </div>
</article>

  
  
  </div>

</th>



<th>
<div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/19/4a/14/194a14b4159ddba5f20f9ced270915df.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title"> Flaps</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Dispositivos que aumentan la superficie alar para reducir la velocidad durante el aterrizaje.



</span
    >
  </div>
</article>

  
  
   </div>

</th>






</tr>
</table>



<br>

<p class="description">Otros controles secundarios:
</p>
<br>
















 <br>
  <br>
<table>
  <tr>
    <th>
  
   <div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/47/0c/43/470c4397761ae62cde250c0b68eccd1b.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Trim</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Ajusta la posición de los controles para mantener la estabilidad.

</span
    >
  </div>
</article>

  
  
  </div>

</th>


<th>
<div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/e1/16/9e/e1169ef28ac3229a3109d4d84faff46e.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Speedbrakes</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Dispositivos que reducen la velocidad rápidamente.


</span
    >
  </div>
</article>

  
  
   </div>

</th>






<th>
<div class="actions">
  

  
  

<article class="cota">
  <div class="card-img"><img src="https://i.pinimg.com/564x/06/35/e4/0635e4c7f6dce86f7fc7fda70e7e10b5.jpg" class="img-circle" alt="Cinque Terre" width="59971" height="150">
    <div class="card-imgs pv delete"></div>
  </div>

  <div class="project-info">
    <div class="flex">
      <div class="project-title">Airbrakes</div>
      <span class="tag">type</span>
    </div>
    <span class="lighter"
      >Dispositivos que reducen la velocidad y altitud.



</span
    >
  </div>
</article>

  
  
  </div>
</th>



</tr>
</table>











<br>

<p class="description">Estos controles secundarios trabajan en conjunto con los controles primarios (como la palanca de control) para proporcionar un control preciso y seguro del avión.
</p>
<br>








  <br>




</div>






























</div>


















<div id="Protocolo" class="tabcontent">






<center><h3>La tecnología ha revolucionado la industria de la aviación, con avances que mejoran la experiencia del pasajero y la seguridad de los vuelos: </h3></center>

<center><p>Biometría y reconocimiento facial
Permite a los viajeros realizar el check-in sin necesidad de mostrar documentos, lo que acelera el proceso de seguridad y embarque. 
Realidad virtual y realidad aumentada
Estas tecnologías pueden recopilar datos en tiempo real y pronosticar reparaciones. 
Asistentes de robótica
Ayudan a los pasajeros a moverse por el aeropuerto y a mantener un registro de la información de los vuelos. 
Pantallas en los asientos
Permiten a las aerolíneas "empujar" contenido y ofertas directamente a los pasajeros. 
Sensores en los aviones
Monitorean continuamente partes de la aeronave y predicen fallas del equipo. 
Mantenimiento predictivo
Permite a las aerolíneas optimizar los recursos y reducir los costos operativos. 
Aviones eléctricos, híbridos o con combustibles de cero emisiones
Se orientan a la descarbonización. 
Impresión 3D o fabricación aditiva
Se utilizan para disminuir el peso y mejorar las prestaciones de los aviones. </p></center>
<br>




<center>
<table>
  <tr>
    <th>
<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/5a/59/62/5a59627f21ec658773182c3cf22bf7c5.jpg" class="img-circle" alt="Cinque Terre" width="300" height="180"></div>
  <div class="content">


   <div class="text-23">
      <span>
        Protocolo
      </span>

  <span>Inspecciones pre-vuelo</span>

   </div>



   <p class="Dato"><FONT COLOR="black">
Se realizan inspecciones rápidas para verificar el estado de la aeronave, como el nivel de aceite, los neumáticos y la presencia de daños estructurales. 
    </p></FONT>
  </div>
</div>
</th>




<th>


<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/6f/7d/a1/6f7da106b685ad2a3197f9c247cc615f.jpg" class="img-circle" alt="Cinque Terre" width="301" height="180"></div>
  <div class="content">


  <div class="text-23">
      <span>
        Protocolo
      </span>

  <span>Mantenimiento preventivo</span>

   </div>

 

   <p class="Dato"><FONT COLOR="black">
Se realizan revisiones periódicas para evitar fallos en la aeronave, como la reparación de los neumáticos y amortiguadores del tren de aterrizaje.
    </p></FONT>
  </div>
</div>

</th>


<th>

<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/b2/b7/1a/b2b71a9a51ca1852a41df51a7f658c12.jpg" class="img-circle" alt="Cinque Terre" width="301" height="180"></div>
  <div class="content">


   <div class="text-23">
      <span>
        Protocolo
      </span>
    <span>Equipos de respiración</span>

   </div>



   <p class="Dato"><FONT COLOR="black">
Se utilizan equipos de respiración para controlar el polvo proveniente de operaciones de esmerilado o lijado.
Aquel que se lleva a cabo en base al seguimiento
    </p></FONT>
  </div>
</div>

</th>


<th>


<div class="cuadros">
  <div class="ilustracion"><img src="https://i.pinimg.com/564x/7a/95/c5/7a95c569ac143d5ce7b34733b02ff953.jpg" class="img-circle" alt="Cinque Terre" width="301" height="180"></div>
  <div class="content">


  <div class="text-23">
      <span>
        Protocolo
      </span>

   <span>Dispositivos de ayuda</span>

   </div>



   <p class="Dato"><FONT COLOR="black">
Se utilizan dispositivos de ayuda o se pide ayuda para levantar materiales grandes y voluminosos. 
Se utilizan tapones u orejeras para protegerse del ruido de los aviones. 

  </p></FONT>
  </div>
</div>
</th>




</tr>
</table></center>



  <br>



<button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>











































<div id="Flaps" class="tabcontent">
  <center><h1>Flaps</h1><center>



<center>
<div>


<div class="container scroll-1">
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Descripción</span>
        <p class="card__describe">
            Son superficies móviles situadas en el borde de salida del ala, cerca del fuselaje.
        </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Función</span>
        <p class="card__describe">
            Aumentan la sustentación y resistencia de las alas. Al bajar los flaps, cambia la curvatura del ala, lo que permite mayor sustentación a menor velocidad.
        </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Usos</span>
        <p class="card__describe">
            Se utilizan en despegues y aterrizajes, permitiendo que la aeronave vuele a velocidades más bajas, algo esencial para las maniobras de ascenso y descenso seguro
        </p>
    </div>
  </div>
</div>



</div></center>





<br>

  <button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>






<div id="Slats" class="tabcontent">

   <center><h1>Slats</h1><center>






<center>
<div>


<div class="container scroll-1">
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Descripción</span>
        <p class="card__describe">
  Son dispositivos en el borde de ataque del ala que, al extenderse, crean una abertura entre el borde de ataque y el ala.
      </p>
  </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Función</span>
        <p class="card__describe">
          Mejoran el flujo de aire sobre la superficie del ala, retrasando la entrada en pérdida a altos ángulos de ataque.

  </p>
  </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Usos</span>
        <p class="card__describe">
            Al igual que los flaps, se despliegan durante el despegue y el aterrizaje, permitiendo que el avión mantenga un mayor ángulo de ataque sin perder sustentación.
     </p>
    </div>
  </div>
</div>



</div></center>






<br>



<button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>












<div id="Spoilers" class="tabcontent">
  <center><h1>Spoilers</h1></center>







<center>
<div>


<div class="container scroll-1">
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Descripción</span>
        <p class="card__describe">
Son paneles situados en la superficie superior del ala que se levantan para interrumpir el flujo de aire.
    </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Función</span>
        <p class="card__describe">
        Reducen la sustentación y aumentan la resistencia. Actúan como frenos aerodinámicos y ayudan a reducir la velocidad del avión.


   </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Usos</span>
        <p class="card__describe">
 Se usan en el aterrizaje para disminuir rápidamente la velocidad y en algunas maniobras de vuelo para controlar el alabeo (movimiento de inclinación lateral) de la aeronave.


   </p>
    </div>
  </div>
</div>



</div></center>


<br>







  <button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>












<div id="Aletas" class="tabcontent">
  <center><h1>Aletas</h1></center>






<center>
<div>


<div class="container scroll-1">
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Descripción</span>
        <p class="card__describe">
Son pequeñas superficies verticales ubicadas en las puntas de las alas.
Similar a los spoilers, pero ubicados en otras partes de la estructura, generalmente en la parte trasera del fuselaje.


   </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Función</span>
        <p class="card__describe">
   Reducen la resistencia inducida por el vórtice en la punta del ala, mejorando la eficiencia del combustible y disminuyendo la resistencia aerodinámica.
Su función principal es aumentar la resistencia sin reducir la sustentación.


  </p>
    </div>
  </div>
  <div class="card">
    <div class="card__image"></div>
    <div class="card__content">
        <span class="card__title">Usos</span>
        <p class="card__describe">
Aunque no son dispositivos de control en el sentido tradicional, optimizan la aerodinámica en vuelos de larga distancia.5. Aerofrenos (air brakes)

Son útiles para frenar la aeronave en el aire, especialmente en descensos pronunciados o cuando se requiere una reducción rápida de la velocidad sin perder altura.

   </p>
    </div>
  </div>
</div>



</div></center>


<br>








   <button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>

































































<div id="Control" class="tabcontent">


<center><div class="cuaColor">

  <button class="red-btn">
     <h3>Controles primarios: Incluyen los mandos que afectan directamente la actitud y dirección del avión. Los principales son:</h3>
     <br>
  Alerones: Controlan el movimiento lateral del avión (roll).
  <br>
  <br>
  Elevador: Controla la inclinación hacia arriba o abajo (pitch).
  <br>
  <br>
  Rudder (timón): Controla el movimiento horizontal (yaw).

  <br>
</button>

<br>

  <button class="blue-btn">
    <h3>Controles secundarios: Incluyen dispositivos que afectan el rendimiento y la estabilidad, como:
</h3>
<br>
  Flaps: Aumentan la sustentación durante el despegue y el aterrizaje.
  <br>
  <br>
  Spoilers: Disminuyen la sustentación y aumentan la resistencia para desacelerar el avión.

  
  </button>
</div>
</center>






<br>



<button class="tablink" onclick="openPage('Inicio', this)" id="defaultOpen">Regresar</button>
</div>




















































<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>







</body>

</html>
