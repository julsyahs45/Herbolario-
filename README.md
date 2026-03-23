<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Herbolaria Natural</title>

<style>

body{
font-family: Arial;
background:#e8f5e9;
margin:0;
}

header{
background:#2e7d32;
color:white;
text-align:center;
padding:20px;
}

nav{
background:#388e3c;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

section{
padding:20px;
}

.categoria{
background:#a5d6a7;
padding:10px;
margin-top:20px;
border-radius:5px;
}

.card{
background:white;
padding:15px;
margin:20px;
border-radius:10px;
box-shadow:0 0 10px gray;
text-align:center;
}

img{
width:200px;
border-radius:10px;
}

button{
background:#2e7d32;
color:white;
padding:10px;
border:none;
border-radius:5px;
cursor:pointer;
}

form{
background:white;
padding:20px;
border-radius:10px;
width:300px;
margin:auto;
box-shadow:0 0 10px gray;
}

input{
width:100%;
padding:8px;
margin:5px;
}

footer{
background:#2e7d32;
color:white;
text-align:center;
padding:10px;
}

</style>
</head>

<body>

<header>
<h1>🌿 Herbolaria Natural</h1>
<p>Plantas medicinales y remedios naturales</p>
</header>

<nav>
<a href="#plantas">Plantas</a>
<a href="#tienda">Tienda</a>
<a href="#registro">Registro</a>
</nav>

<section id="plantas">

<h2>Categorías de Plantas</h2>

<div class="categoria">
<h3>🌿 Relajantes</h3>

<div class="card">
<h2>Menta</h2>
<p><b>Nombre científico:</b> Mentha spicata</p>
<img src="menta.jpg">

<p><b>¿Para qué sirve?</b><br>
Ayuda a la digestión, reduce el estrés y refresca el aliento.</p>

<p><b>¿Cómo se usa?</b><br>
Se prepara en infusión (té) o se puede masticar la hoja.</p>

<p><b>Consejos:</b><br>
No consumir en exceso si se tiene gastritis.</p>

</div>
</div>

<div class="categoria">
<h3>🌸 Naturales</h3>

<div class="card">
<h2>Bugambilia</h2>
<p><b>Nombre científico:</b> Bougainvillea glabra</p>
<img src="Bugambilia.jpg">

<p><b>¿Para qué sirve?</b><br>
Ayuda a aliviar la tos y problemas respiratorios.</p>

<p><b>¿Cómo se usa?</b><br>
Se prepara en té con las flores hervidas.</p>

<p><b>Consejos:</b><br>
Tomar máximo dos veces al día.</p>

</div>
</div>

<div class="categoria">
<h3>🤧 Gripe</h3>

<div class="card">
<h2>Vick VapoRub</h2>
<p><b>Tipo:</b> Ungüento medicinal</p>
<img src="vick.jpg">

<p><b>¿Para qué sirve?</b><br>
Ayuda a aliviar congestión nasal, tos y síntomas de resfriado.</p>

<p><b>¿Cómo se usa?</b><br>
Se aplica en el pecho, cuello o espalda antes de dormir.</p>

<p><b>Consejos:</b><br>
No aplicar dentro de la nariz ni en heridas.</p>

</div>
</div>

</section>

<section id="tienda">

<h2>🛒 Tienda de Herbolaria</h2>

<div class="card">
<h3>Té de Menta</h3>
<p>Precio: $40</p>
<button>Comprar</button>
</div>

<div class="card">
<h3>Té de Bugambilia</h3>
<p>Precio: $35</p>
<button>Comprar</button>
</div>

<div class="card">
<h3>Vick VapoRub</h3>
<p>Precio: $60</p>
<button>Comprar</button>
</div>

</section>

<section id="registro">

<h2>👤 Registro de Usuario</h2>

<form>

<label>Nombre</label>
<input type="text" placeholder="Tu nombre">

<label>Correo</label>
<input type="email" placeholder="Tu correo">

<label>Contraseña</label>
<input type="password" placeholder="Tu contraseña">

<button>Registrarse</button>

</form>

</section>

<footer>
<p>Proyecto escolar de Herbolaria</p>
<img src="1.jpg">
<video width="200" controls autoplay loop muted>
  <source src="2.mp4" type="video/mp4">
</video>
</footer>

</body>
</html>