<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Telefonía Express</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f7f7f7;
      color: #333;
    }
    header {
      background-color: #003087;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
    }
    .hero {
      background-color: #004bbd;
      color: white;
      padding: 3rem 2rem;
      text-align: center;
    }
    .hero h2 {
      margin: 0 0 1rem;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }
    .producto {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 1rem;
      text-align: center;
    }
    .producto img {
      max-width: 100%;
      height: auto;
    }
    .producto h3 {
      margin: 0.5rem 0;
    }
    .producto button {
      background-color: #003087;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #003087;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Telefonía Express</h1>
    <nav>
      <a href="#productos">Productos</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>
  <section class="hero">
    <h2>Distribuidor Autorizado</h2>
    <p>Teléfonos y accesorios al mejor precio. Compra segura y rápida.</p>
  </section>
  <section id="productos" class="productos">
    <div class="producto">
      <img src="https://via.placeholder.com/200x200?text=Tel%C3%A9fono+1" alt="Teléfono 1">
      <h3>Teléfono Galaxy A14</h3>
      <p>$4,299 MXN</p>
      <button>Comprar</button>
    </div>
    <div class="producto">
      <img src="https://via.placeholder.com/200x200?text=Tel%C3%A9fono+2" alt="Teléfono 2">
      <h3>iPhone 13</h3>
      <p>$16,999 MXN</p>
      <button>Comprar</button>
    </div>
    <!-- Agrega más productos aquí -->
  </section>
  <section id="contacto" class="hero">
    <h2>Contacto</h2>
    <p>WhatsApp: 55 1234 5678<br>Correo: contacto@telefoniaexpress.com</p>
  </section>
  <footer>
    <p>&copy; 2025 Telefonía Express. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
