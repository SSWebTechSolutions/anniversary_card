<!DOCTYPE html>
<html>
<head>
	<title>Anniversary Card | shyam</title>
	<style type="text/css">
		body{
 
    height: 100%;
    margin: 0;
    background-repeat: no-repeat;
    background-attachment: fixed;
	cursor: url("icons8-cake-48.svg"), auto;
}

.card {
	 position: relative;
	 width: 300px;
	 height: 425px;
	 border: 10px solid #9612eb;
	 margin: 60px auto 0 auto;
	 box-shadow: inset 10px 0px 15px 0px rgba(0, 0, 0, 0.1);
     background-image: url("mom&dad.png");

	background-position: center; /* Center the image */
    background-repeat: no-repeat; /* Do not repeat the image */
    background-size: cover;
	background-color: #e6f0e6;
}
 .card .text-container {
	 width: 80%;
	 height: 80%;
	 margin: auto;
}
 .strikethrough {
	 text-decoration: line-through;
}
 .card .text-container #head {
	 font-family: 'Nobile', sans-serif;
	 font-size: 1.5em;
	 margin: 60px auto 60px auto;
}
 .card p {
	 font-size: 1.1em;
	 line-height: 1.4;
	 font-family: 'Nobile';
	 color: #331717;
	 font-style: italic;
	 text-align: center;
	 margin: 30px auto 0px auto;
}
 .card .front {
	 position: absolute;
	 width: 100%;
	 height: 100%;
	 margin: -10px 0px 0px -10px;
	 border: 10px solid #9612eb;
	 backface-visibility: hidden;
	 background-color: #9612eb;
	background-image: url("images/mom&dad.png");
	
	 background-size: contain;
	 transform-style: preserve-3d;
	 transform-origin: 0% 50%;
	 transform: perspective(800px) rotateY(0deg);
	 transition: all 0.8s ease-in-out;
}
 .card:hover .front {
	 transform: perspective(800px) rotateY(-170deg);
	 background-color: #41718d;
}
 .card:hover .back {
	 transform: perspective(800px) rotateY(-170deg);
	 box-shadow: 7px 0px 5px 0px rgba(0, 0, 0, 0.3), inset 2px 0px 15px 0px rgba(0, 0, 0, 0.1);
	 background-color: #d2dcd2;
}
 .card .back {
	 position: absolute;
	 width: 100%;
	 height: 100%;
	 border: 10px solid #9612eb;
	 margin: -10px 0px 0px -10px;
	 backface-visibility: visible;
	 filter: drop-shadow(2px 2px 4px rgba(0, 0, 0, .5));
	 transform-style: preserve-3d;
	 transform-origin: 0% 50%;
	 transform: perspective(800px) rotateY(0deg);
	 transition: all 0.8s ease-in-out;
	 background-color: #e6f0e6;
	 box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 0.1);
}

.imgset
{
  position: relative;
  z-index: 1;
  margin-bottom: -215px;
}
.imgset img
{
    box-shadow: 0px 6px 11px 7px rgba(0, 0, 0, 0.22);
    border-radius: 5px;
}
@media only screen and (max-width: 769px) {
  
}
	</style>
</head>
<body>

<body>
<div class="card">
  <div class="back"></div>
  <div class="front">
    <div class="imgset">
         <img width="100%" src="images/anniversary.png">
       </div>
  </div>
  <div class="text-container">
    <p id="head"></p>
    
  </div>
</div>

 
</body>
</body>
</html>
