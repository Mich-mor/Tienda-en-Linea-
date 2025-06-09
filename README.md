# Tienda-en-Linea-
Obtén los mejores objetos de Alfredo Olivas 
body{
  font-family: 'segoe ui', Tahoa, Geneva, Verdana, sans-serif;
  background-color: wheat;
  margin: 0;
  text-align: center;
  
}
header, footer{
  background-color: blueviolet;
  color: red;
  padding: 1em;
  
}
nav ul{
  list-style: none;
  padding: 0;
}
nav ul li{
  display: inline;
  margin: 0 1em;
}
nav ul li a{
  color: chocolate;
  text-decoration: none;
}
busqueda{
  text-align: center;
  margin-bottom: 1px;
}
#buscador{
  width: 60%;
  padding: 0.5em;
  font-size: 1em;
  border: 1px solid pink;
  border-radius: 5px;
}
main{
  padding: 1em;
}
.productos{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.producto{
  background-color: yellow;
  border-radius: 5px;
  box-shadow: 0 2px 5px #3ef788(0, 0, 0.1);
  margin: 1em;
  padding: 1em;
  text-align: center;
  width: 220px;
  transition: transfore 0.25;
}
.producto,hover{
  transform: scale(1.05);
}
.producto img{
  width: 100%;
  height: auto;
  border-radius: 5px;
}
.descripcion{
  font-size: 0.9 em;
  color: rosybrown;
}
.precio{
  font-weight: bold;
  color: mediumturquoise;
  margin: 0.5em 0;
}
.rating{
  color:"blue";
  margin-bottom: 0.5em;
}
button{
  background-color: green;
  border: none;
  padding: 0.5en 1em;
  border-radius: 3px;
  cursor: pointer;
  font-weight: bold;
}
button:hover {
  background-color: blue;
}
<!DOCTYPE html>

<html lang="es">
<head>
  <meta charset="UTF-8" name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Mi tienda en linea</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/responsive.css">
</head>
<body>
  <header>
    <h1>Mi tienda</h1>
    <nav>
      <ul>
        <li><a href="index.html">Inicio</a></a></li>
      <li><a href="productos.html">Productos</a></li>
      <li><a href="carrito.html">Carrito</a></li>
      <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
  <section class="busqueda">
    <input type="text" id="buscador"  placeholder="Buscar producto..." oninput="filtrarProductos"/>
  </section>
  </header>
<main>
  <h2>Bienvenido a nuestra tienda en linea </h2>
  <p>Encuentra los mejores productos al mejor precio </p>
  <section class="ofertas">
    <h2> Oferta del dia </h2>
    <div class="productos">
      <figure class="productos">
        <img width="300 px" src="olivas.jpg"   alt="Vaso Olivas">
        <figcaption>
          <h3>Vaso Olivas</h3>
          <p class="descripcion">Es un vaso de 1L tiene tapa y es muy lindo</p>
          <p class="precio-oferta"><del>$1500</del>$1000</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Vaso Olivas2323)">Agregar al carrito</button>
        </figcaption>
      </figure>
      
       <figure class="productos">
        <img width="300 px" src="ramo.jpg"   alt="Ramo Olivas ">
        <figcaption>
          <h3>Ramo Olivas</h3>
          <p class="descripcion">Es un lindo ramo ,flores de tela e imagenes </p>
          <p class="precio-oferta"><del>$2500</del>$1500</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Ramo Olivas2323)">Agregar al carrito</button>
        </figcaption>
          </figure>
      
      <figure class="productos">
        <img width="300 px" src="peluche.jpg"   alt="Peluche Olivas">
        <figcaption>
          <h3>Peluche Olivas</h3>
          <p class="descripcion">Es un peluche tequijo a mano inspirado en el cantante</p>
          <p class="precio-oferta"><del>$4000</del>$2000</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Peluche Olivas2323)">Agregar al carrito</button>
        </figcaption>
          </figure>
      
       <figure class="productos">
        <img width="300 px" src="vaso2.jpg"   alt="Vaso Olivas">
        <figcaption>
          <h3>Vaso Olivas</h3>
          <p class="descripcion">Es un vaso de 1L tiene tapa y es muy lindo</p>
          <p class="precio-oferta"><del>$2000</del>$1000</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Vaso Olivas2323)">Agregar al carrito</button>
        </figcaption>
          </figure>
      
      <figure class="productos">
        <img width="300 px" src="funda.jpg"   alt="Funda Olivas">
        <figcaption>
          <h3>Funda Olivas</h3>
          <p class="descripcion">Funda bonita personalizada </p>
          <p class="precio-oferta"><del>$1500</del>$1000</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Funda Olivas2323)">Agregar al carrito</button>
        </figcaption>
          </figure>
      
       <figure class="productos">
        <img width="300 px" src="pastel.jpg"   alt="Pastel Olivas">
        <figcaption>
          <h3>Pastel Olivas</h3>
          <p class="descripcion">Pastel personalizado </p>
          <p class="precio-oferta"><del>$2000</del>$1500</p>
          <p class="rating">⭐⭐⭐⭐⭐</p>
          <button onclick="Agregaralcarrito(Pastel Olivas2323)">Agregar al carrito</button>
        </figcaption>
          </figure>
    </div>
  </section>    
    </main>
<footer> &copy;2025 Mi tienda </footer>
<script src="is/Main.js"></script>
</body>
</html>
