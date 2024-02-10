<li><a href="https://pythontutor.com/render.html#mode=display/"> python </a></li>


<li><a href="https://jsitor.com/">анимация</a></li>



<html>

<head></head>

<body>
	<p style="text-align: center">

		<button>ПЕЛЬМЕШКИ!</button>
		<p>Горошка и морковки хватит, МММ... салатик. МММ... отлично...МММ... салатик</p>

		<style>
			body {
				height: 200px;
				background: beige;
			}

			.dot {
				height: 8px;
				width: 8px;
				border-radius: 4px;
				/* скруглённые углы */
				background: blue;
				position: absolute;
			}

			#myImg {
				height: 250px;
			}
		</style>



		

</p>
		<script>
			var cat = document.querySelector("img");
var angle = 0, lastTime = null;
function animate(time) {
if (lastTime != null)
angle += (time - lastTime) * 0.002;
lastTime = time;
cat.style.top = (Math.cos(angle) * 50      ) + "px";
cat.style.left = (Math.sin(angle) * 100) + "px";
requestAnimationFrame(animate);
}

var button = document.querySelector("button");
button.addEventListener("click", function() {
alert("OUCH!!!!");
});

document.getElementById('myImg').onclick = myFunction;

function myFunction() {
  alert('НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!');
}
requestAnimationFrame(animate);
		</script>
		<script type="text/javascript">
		<script>

var button = document.querySelector("button");
button.addEventListener("click", function() {
alert("НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!!");
});

document.getElementById('img').onclick = myFunction;



requestAnimationFrame(animate1);





		</script>
		<script type="text/javascript">



<li><a href="https://jsitor.com/">анимация</a></li>

		</script>
</body>
</html>








<html>

<head>

<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">

<title>Трансформации</title>


<style>

body {
 font-family: Tahoma, Verdana, Geneva, sans-serif;
 margin: 6em 6em; font-weight: bold;
}

ul {
 list-style-type: none; padding: 0;
	margin: 0;
}

li { float: left; margin-right: 10px;
}

li:last-of-type {
 margin-right: 0;
}


a { display: block;
}


img { width: 200px; height: 150px; box-shadow: 2px 2px 2px rgba(0,0,0,.4);

transition: transform .3s ease-in-out; 
}


a:hover img {
	box-shadow: 6px 6px 6px rgba(0,0,0,.3);
}

a:hover #img1
 box-shadow: 6px 6px 6px rgba(0,0,0,.3);

}

a:hover #img2, a:focus #img2  {
	transform: scale(3.0 rotate(5deg);
}

a:hover #img3, a:focus #img3  {
	transform: scale(3.0) rotate(-7deg);
}

a:hover #img4, a:focus #img4  {
	transform: scale(3.0) rotate(2deg);
}


</style>


</head>



<body>


<ul>

  <li><a href=""><img src="![image](https://github.com/rostoSonya/-1/assets/153977631/ac0d6d4a-7745-4145-bd4c-5fa43eec29f5)" id="img1" alt ""></a</li>

  <li><a href=""><img src="jellyfish1.jpg" id="img2" alt=""></a></li>

  <li><a href=""><img src="bluejellyfish.jpg" id="img3" alt=""></a></li>

  <li><a href=""><img src="seadragon.jpg" id="img4"alt=""></a></li>
</ul>


</body>

</html>


                                    
