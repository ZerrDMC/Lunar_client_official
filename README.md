<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Lunar Client | Página Oficial</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0d0d0d;
color:white;
overflow-x:hidden;
}

section{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:30px;
}

h1{
font-size:3rem;
margin-bottom:20px;
}

h2{
font-size:2.2rem;
margin-bottom:15px;
}

p{
max-width:800px;
font-size:1.1rem;
line-height:1.7;
}

button{
padding:15px 35px;
margin-top:30px;
border:none;
border-radius:12px;
background:#5865F2;
color: white;
font-size:1rem;
font-weight:600;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.05);
}

.card{
width:100%;
max-width:800px;
background:#171717;
padding:25px;
border-radius:15px;
margin-top:20px;
}

input, textarea{
width:100%;
padding:15px;
margin-top:10px;
background:#222;
border:none;
border-radius:10px;
color:white;
}

textarea{
height:120px;
resize:none;
}

.links{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:8px;
margin-top:15px;
}

.links a{
text-decoration:none;
padding:15px 25px;
background:#222;
border-radius:12px;
color:white;
transition:.3s;
}

.links a:hover{
background:#5865F2;
}

#overlay{
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:black;
opacity:0;
pointer-events:none;
transition:2s;
z-index:9999;
}

.credit{
margin:10px 0;
font-size:1.2rem;
}

</style>
</head>
<body>

<div id="overlay"></div>

<!-- INTRODUCCIÓN -->

<section id="intro">

<h1>Lunar Client</h1>

<p>
Bienvenido a la página oficial de Lunar Client.
Aquí encontrarás información sobre registros,
rangos, whitelist, mods, SPRX y mucho más.
</p>

</section>

<!-- REGISTRO -->

<section id="registro">

<h2>Registro Lunar Client</h2>

<div class="card">

<input type="text" placeholder="Nombre">

<input type="text" placeholder="PSN">

<input type="text" placeholder="Discord">

<textarea placeholder="¿Por qué deseas registrarte?"></textarea>

<button>
Enviar Registro
</button>

</div>

</section>

<!-- RANGOS -->

<section id="rangos">

<h2>Rangos y WhiteList</h2>

<div class="card">

<p><b>Owner:</b> Máximo administrador.</p>
<p><b>Developer:</b> Desarrollador oficial.</p>
<p><b>Helper:</b> Ayuda a los usuarios.</p>
<p><b>Tester:</b> Prueba nuevas versiones.</p>
<p><b>Usuario:</b> Miembro normal.</p>

<br>

<p>✅ WhiteList = Usuario aprobado.</p>
<p>❌ BlackList = Usuario bloqueado.</p>

</div>

</section>

<!-- MODS -->

<section id="mods">

<h2>Mods y SPRX</h2>

<div class="links">

<a href="#">SPRX V1</a>
<a href="#">SPRX V2</a>
<a href="#">Mods</a>
<a href="#">Tutorial</a>

</div>

</section>

<!-- OPINIONES -->

<section id="opiniones">

<h2>Opiniones del Mod</h2>

<div class="card">

<textarea placeholder="Escribe tu opinión aquí"></textarea>

<button>
Publicar Opinión
</button>

</div>

</section>

<!-- REDES -->

<section id="redes">

<h2>Canales Oficiales</h2>

<div class="links">

<a href="#">YouTube</a>
<a href="#">Discord</a>
<a href="#">WhatsApp</a>

</div>

</section>

<!-- CRÉDITOS -->

<section id="creditos">

<h2>Créditos</h2>

<div class="card">

<div class="credit">
👑 Developer: RealDany
</div>

<div class="credit">
🛠 Helper: ZerrDMC 
</div>

<div class="credit">
🧪 Tester: Nombre
</div>

<div class="credit">
🎨 Diseño Web: Zv_Shadowboy_vZ
</div>

<div class="credit">
❤️ Gracias por utilizar Lunar Client
</div>

</div>

</section>


</body>
</html>
