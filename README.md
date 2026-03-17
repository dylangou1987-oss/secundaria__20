<!DOCTYPE html>
<html>

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Secundaria N°20 Ricardo Rojas</title>

<style>

body{
font-family: Arial;
margin:0;
background:#eef1f5;
}

header{
background:#1e3a5f;
color:white;
padding:25px;
text-align:center;
}

nav{
background:#2c4d73;
display:flex;
justify-content:center;
flex-wrap:wrap;
}

nav a{
color:white;
padding:15px 20px;
text-decoration:none;
font-weight:bold;
}

nav a:hover{
background:#1e3a5f;
}

.container{
max-width:1000px;
margin:auto;
padding:20px;
}

.card{
background:white;
padding:20px;
margin:20px 0;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.news{
display:grid;
grid-template-columns:1fr 1fr;
gap:15px;
}

.news div{
background:white;
padding:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

footer{
background:#1e3a5f;
color:white;
text-align:center;
padding:20px;
margin-top:30px;
}

@media (max-width:700px){

.news{
grid-template-columns:1fr;
}

}

</style>

</head>

<body>

<header>

<h1>Escuela Secundaria N°20 Ricardo Rojas</h1>
<p>Secundaria N°20 ubicada en Ricardo Rojas. Aquí recibirán actualizaciones sobre lo que pasa en la escuela.</p>

</header>

<nav>

<a href="#inicio">Inicio</a>
<a href="#noticias">Noticias</a>
<a href="#eventos">Eventos</a>
<a href="#institucion">Institución</a>
<a href="#estudiantes">Estudiantes</a>
<a href="#contacto">Contacto</a>

</nav>

<div class="container">

<div class="card" id="inicio">

<h2>🏫 Inicio</h2>

<p>La Escuela Secundaria N°20 forma estudiantes con valores, conocimiento y compromiso con la comunidad de Ricardo Rojas y el Partido de Tigre.</p>

</div>

<div class="card" id="noticias">

<h2>📰 Noticias</h2>

<div class="news">

<div>
<h3>Nuevo Centro de Estudiantes</h3>
<p>La escuela inaugura un nuevo centro de estudiantes (próximamente).</p>
</div>

<div>
<h3>Torneo</h3>
<p>Se realizará un torneo entre cursos.</p>
</div>

<div>
<h3>Proyectos escolares</h3>
<p>Los estudiantes presentarán proyectos escolares.</p>
</div>

<div>
<h3>Proyectos de programación</h3>
<p>Actividad para aprender tecnología.</p>
</div>

</div>

</div>

<div class="card" id="eventos">

<h2>📅 Eventos</h2>

<ul>
<li>Próximamente — Proyectos escolares</li>
<li>Próximamente — Torneo deportivo</li>
<li>Próximamente — Acto escolar</li>
</ul>

</div>

<div class="card" id="institucion">

<h2>🏫 Institución</h2>

<p>Cuenta con proyectos educativos y actividades deportivas.</p>

</div>

<div class="card" id="estudiantes">

<h2>🎓 Estudiantes</h2>

<p>Los estudiantes participan en actividades como:</p>

<ul>
<li>Centro de estudiantes</li>
<li>Eventos deportivos</li>
</ul>

</div>

<div class="card" id="contacto">

<h2>📞 Contacto</h2>

<p>Email: secundaria20@escuela.edu</p>
<p>Teléfono: 22024845</p>
<p>Dirección: Ricardo Rojas, Tigre, Buenos Aires</p>

</div>

</div>

<footer>

<p>Página creada por Dylan</p>

</footer>

</body>

</html>
