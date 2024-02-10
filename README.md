<li><a href="https://pythontutor.com/render.html#mode=display/"> python </a></li>


<li><a href="https://jsitor.com/">анимация</a></li>



<!doctype html><html><head></head><body><!doctype html>
<html>

<head></head>

<body>
	<p style="text-align: center">

		<button>Покорми меня!</button>
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



		<img id="myImg" src="https://meat-expert.ru/files/uploads/obzor/_2023/30/01.jpg" style="position: relative">

</p>
		<script>
			var cat = document.querySelector("img");
var angle = 0, lastTime = null;
function animate(time) {
if (lastTime != null)
angle += (time - lastTime) * 0.002;
lastTime = time;
cat.style.top = (Math.cos(angle) * 50      ) + "px";
cat.style.left = (Math.sin(angle) * 200) + "px";
requestAnimationFrame(animate);
}

var button = document.querySelector("button");
button.addEventListener("click", function() {
alert("НЕ ТРОГАЙ МОИ ПЕЛЬМЕНИ!!!!");
});

document.getElementById('myImg').onclick = myFunction;

function myFunction() {
  alert('Ouch!!!');
}

requestAnimationFrame(animate);





		</script>
		<script type="text/javascript">




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


a:hover #img1, a:focus #img1  {
	transform: scale(2.5) rotate(-6deg);
}

a:hover #img2, a:focus #img2  {
	transform: scale(2.5) rotate(8deg);
}





  


                                    
