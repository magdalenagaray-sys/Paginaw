<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mundo IA</title>

<!-- Fuente moderna -->
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">

<!-- Iconos Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<link rel="stylesheet" href="style.css"
</head>
<body>
  <header>
    <h1><i class="fas fa-robot"></i> Mundo IA</h1>
    <p>Explorando el futuro de la inteligencia artificial</p>
  </header>

  <nav>
    <a href="#articulos"><i class="fas fa-newspaper"></i> Artículos</a>
    <a href="#contacto"><i class="fas fa-envelope"></i> Contacto</a>
  </nav>

  <section id="articulos">
    <h2>Últimos artículos</h2>
    <div class="cards">
      <div class="card">
        <i class="fas fa-heartbeat"></i>
        <h3>IA en la medicina</h3>
        <p>Cómo los algoritmos ayudan a diagnosticar enfermedades y mejorar tratamientos.</p>
      </div>
      <div class="card">
        <i class="fas fa-industry"></i>
        <h3>Automatización inteligente</h3>
        <p>Robots y sistemas que optimizan procesos industriales y logísticos.</p>
      </div>
      <div class="card">
        <i class="fas fa-paint-brush"></i>
        <h3>Creatividad artificial</h3>
        <p>La IA generativa en música, arte y escritura está transformando la cultura.</p>
      </div>
    </div>
  </section>
  <center><img src="ia1.jpeg" width="300" height="300"></center>
  <section id="contacto">
    <h2>Contáctanos</h2>
    <form action="https://formspree.io/f/tu-endpoint" method="POST">
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="email">Correo electrónico:</label>
      <input type="email" id="email" name="email" required>

      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" rows="4" required></textarea>

      <!-- Redirección a página de agradecimiento -->
      <input type="hidden" name="_next" value="gracias.html">

      <button type="submit"><i class="fas fa-paper-plane"></i> Enviar</button>
    </form>
  </section>
  <a href="https://www.facebook.com" target="_blank">
   <center> <img src="facebook.png" alt="Visita nuestro Facebook" width="30"></center>
</a>
  <a href="https://www.instagram.com" target="_blank">
   <center> <img src="instagram.jpeg" alt="Visita nuestro Facebook" width="30"></center>
</a>
  
 <a href="paginaW.html" class="boton-inicio">Inicio</a>
  <footer>
    <p>&copy; 2026 Mundo IA. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
# Paginaw
<style>
.titulo
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: 'Montserrat', sans-serif;
}

body{
  background: #f4f6f9;
  color: #333;
  overflow-x: hidden;
}

/* Fondo animado */
body::before{
  content:"";
  position:fixed;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background: linear-gradient(135deg,#e0f7fa,#f4f6f9);
  z-index:-2;
}

body::after{
  content:"";
  position:fixed;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background: repeating-linear-gradient(
    90deg,
    rgba(0,120,255,0.05) 0px,
    rgba(0,120,255,0.05) 2px,
    transparent 2px,
    transparent 4px
  );
  z-index:-1;
  animation: movimiento 12s linear infinite;
}

@keyframes movimiento{
  from{transform:translateY(-100%);}
  to{transform:translateY(100%);}
}

header{
  text-align:center;
  padding:50px 20px;
}

header h1{
  font-size:3rem;
  color:#0078ff;
  text-shadow:0 0 8px rgba(0,120,255,0.4);
}

header p{
  margin-top:10px;
  color:#555;
}

nav{
  background:#0078ff;
  display:flex;
  justify-content:center;
  gap:20px;
  padding:15px;
  flex-wrap:wrap;
}

nav a{
  color:#fff;
  text-decoration:none;
  font-weight:bold;
  transition:0.3s;
}

nav a:hover{
  color:#ffeb3b;
}

section{
  padding:50px 20px;
  max-width:1100px;
  margin:auto;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:20px;
  margin-top:30px;
}

.card{
  background:#fff;
  border:1px solid #0078ff;
  padding:20px;
  border-radius:12px;
  transition:0.3s;
  text-align:center;
}

.card:hover{
  transform:translateY(-10px);
  box-shadow:0 0 20px rgba(0,120,255,0.3);
}

.card h3{
  margin-bottom:10px;
  color:#0078ff;
}

.card i{
  font-size:40px;
  margin-bottom:15px;
  color:#0078ff;
}

footer{
  text-align:center;
  padding:30px;
  background:#0078ff;
  margin-top:40px;
  color:#fff;
}

/* botón */
.btn{
  display:inline-block;
  margin-top:20px;
  padding:12px 25px;
  background:#0078ff;
  color:white;
  text-decoration:none;
  font-weight:bold;
  border-radius:8px;
  transition:0.3s;
}

.btn:hover{
  background:#005bb5;
}

/* formulario */
form{
  background:#fff;
  border:1px solid #0078ff;
  padding:20px;
  border-radius:12px;
  max-width:500px;
  margin:auto;
}

form label{
  display:block;
  margin-bottom:8px;
  color:#333;
}

form input, form textarea{
  background:#f4f6f9;
  color:#333;
  border:1px solid #ccc;
  padding:10px;
  margin-bottom:15px;
  border-radius:6px;
}

form button{
  background:#0078ff;
  color:#fff;
  font-weight:bold;
  cursor:pointer;
  border:none;
  padding:12px;
  border-radius:6px;
}

form button:hover{
  background:#005bb5;
}

/* responsive */
@media(max-width:600px){
  header h1{font-size:2rem;}
  .cards{grid-template-columns:1fr;}

</style>
