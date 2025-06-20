# Design-3-irmaos
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maquetes 3D</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
    }

    header {
      background-color: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #333;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .galeria {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .galeria img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    footer {
      background-color: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Maquetes e Projetos 3D</h1>
    <p>Transformamos ideias em realidade</p>
  </header>

  <nav>
    <a href="#">Início</a>
    <a href="#galeria">Galeria</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="galeria">
    <h2>Projetos Recentes</h2>
    <div class="galeria">
      <img src="https://www.bmmaquetes.com/_files/ugd/1c77b3_3f63739b99984db2aeeed75d3b7c9838~mv2.jpg" alt="Maquete 1">
      <img src="https://www.bmmaquetes.com/_files/ugd/1c77b3_9323462e88cf4e2a869dc0b741df4be1~mv2.jpg" alt="Maquete 2">
      <img src="https://www.bmmaquetes.com/_files/ugd/1c77b3_5b0806cb29a8487e84b7ff7f01ad960b~mv2.jpg" alt="Maquete 3">
    </div>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>📞 (31) 99612-6215</p>
    <p>📧 contato@maquetes3d.com.br</p>
  </section>

  <footer>
    <p>&copy; 2025 Maquetes 3D - Todos os direitos reservados.</p>
  </footer>

</body>
</html>
